                       What is Git and GitHub

 ### Git:
Git is a software that helps you track and manage changes in your files over time. It is like a version history for your work, so you can always go back to a previous version if something goes wrong.

 ### GitHub:
GitHub is an online hosting server where you can store your Git-managed projects. It allows you to share your code with others, collaborate on projects, and keep everything backed up in the cloud.


          *****************************************************
 ### GIT VS GITHUB 
![Git VS GitHUb ](image/Git-vs-GitHub.png)


          *****************************************************



In this section, we will learn about the "git add" command for adding files.

### There are three methods for adding files:

1. git add file_one file_two...

   Example: Add specific files such as 
   `git add index.html, style.css, script.js`.  
   Use this command to add only the files you want to include.

2. git add .  
   Example: Use `git add .` to stage all changes in the current directory.  
  

3. git add -A 
   Example: Use `git add -A` to stage all changes in the repository, including changes to files in the current directory and subdirectories.



### Simple Explanation for Each Method:

1.git add file_one file_two...
   This method is like picking specific toys (files) you want to show to your friend (Git).  
   Example: If you want to show `index.html, style.css, script.js`, you write:  
   ```
   git add index.html style.css script.js
   ```

2. git add .  
   This method is like telling Git to look at everything in your current room (folder) and pick up all the toys (files).  
   The command is:  
   ```
   git add .
   ```

3. git add -A
   This method is like telling Git to look at the entire house (project) and pick up all the toys (files) that you’ve changed, added, or even deleted.  
   The command is:  
   ```
   git add -A
   ```

         