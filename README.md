# portfoliobootstrap 
This website displays the student portfolio of work for a fictitous Jane Doe. It makes use of the bootstrap framework. 
The main file index.html is released to the public domain. 

Follow these steps to use this repository (assumes a Linux / Apache2 server with public_html web folders and git):

1. To see your globals type: `git config --list`

2. If missing email or name then give the next two commands:

 a. `git config --global user.email "yourname@whereever.edu"` 

 b. `git config --global user.name "First Last"` 

3. Change into your public_html folder and type:

 `git clone https://github.com/profphillips/portfoliobootstrap.git`

4. `cd portfoliobootstrap`

5. Create a new empty (don't even have a readme file) repository on GitHub -- perhaps named portfolio2.

6. `git remote -v`

7. Change the remote to your new repository: 

 `git remote set-url origin https://github.com/youraccountname/portfolio2.git` 

8. Check the remote again and make sure it points to your repository: `git remote -v`

9. Make some changes to index.html and save

10. `git status`

11. `git add .`

12. `git status`

13. `git commit -am "your comment here"`

14. `git status`

15. `git push -u origin master`

16. Make more changes. If no new files are added you can just type:

 a. `git commit -am "new comment"`

 b. `git push`

17. Verify your files are in your new repository on GitHub.
