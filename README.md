# A02
Danny Do IS117 Section 4 

**What's Git?**
  Git is like a memory book, it keeps track of your code and keeps different versions of it, think of it like restore points on your computer or iCloud backups, you're given multiple different previous verions to your code
  
**What is Github?**
  Similar to a library or something like your google drive, github is a way for you to store your code, share it amongst others and never lose it (unless you delete it)
  Github is a great way for you to keep track of your progress, share your code and collatborate with peers or help others online!

**What is WebStorm?**
  Webstorm is a tool, similar to google extensions! You can use WebStorm to help you write your code, it displays your mistakes and helps you optimize your time and coding instead of figuring it all out on your own digging through piece by piece.  It has a built in relationship with Git and Github so it's very useful if you're using either of the two.  

  For you to get Git you need to download the latest version of their website (https://git-scm.com/downloads)
1. Go to the website link
2. Choose what operating system you're on
3. Click the link to download the latest version

For you to get webstorm you download it on the web as well, it's from jetbrains (https://www.jetbrains.com/webstorm/download/#section=windows)
1. Go to the website link and choose your operating system for the download
2. After downloading webstorm you want to link your git to webstorm do the shortcut(CTRL + ALT + S)
3. This should open up the settings, and from there you want to go to Version Control and select Git
4. You want to put C:\Program Files\Git\cmd\git.exe in the blank.
5. Click the test button beside it, it should say 2.8.1 (the most updated version CAN CHANGE)

**Make a repository! **
1. You want to create a new project in Webstorm and you want to go to File > New > HTML.
2. Afterwards you want to name the file whatever you'd like and we should now save it to our Git or upload it to github
3. Commit is like a memory of your code, this is important to know when using git.  Open the terminal in Webstorm on the bottom left panel
4. Type in "git init" (this tells git what you want to save and initializes it)
5. then "git add ." (this will save all the files to be committed)
6. then "git commit -m (Whatever you'd like)" (this saves your progress and tells you what you did)
7. Now create a repository in github by creating an account, going to repository and creating a new one.  (https://github.com/) Register Here
8. Now let's link the two, we want to go back in the terminal and type "git remote add origin https://github.com/dtd34/A02.git" In this example, I put dtd34 because that's my github account, you want to put what your account name is and where i put A02.git, you would change if your name for your files or projects or different!
9. you can use codes like git branch -M (name) to change your branch but most of the time you want it to be Main
10. "git push -u origin Main" will push your files to github
11. "git pull origin main" to avoid merge conflicts
12. "git add ." and "git commit -m "(message)" to make sure you save changes and show your progress!
    **Cloning, Merging and fetching**
1. If you wanted to do something like get a copy of someone elses work or your work, you can clone.
2. "git clone https://github.com/username/repository-name.git" is a way that you can do that, if you type that in your terminal and replcae username with whoever's username you want to copy the work of and their repository name.  this will give your computer a copy of the work and it won't interfere with the persons work.
3. Now if you made changes to it and wanted to push it on to who made the code originally, you can merge your code with theirs by asking for permission.
4. The author can look at your code, and fetch it, this means he can see the changes made in the code before he decides to apply it to his.
5. You do this by using the command "git fetch origin" and lastly if you want to combine the changes you would do, "git merge origin"

  **Summary**
Today, we set up Git in WebStorm and linked it to GitHub. We created a Repository, committed changes, and pushed them to GitHub using git add, commit, and push. We also learned how to Clone an existing repository, Fetch updates from GitHub, and Merge changes into our local project. Lastly, we discussed Branches, handling Merge Conflicts, and working with a Remote repository.

**Glosary**
Branch – A separate version of a repository where you can develop features or fixes without affecting the main code.
Clone – A command (git clone) that creates a copy of a GitHub repository on your local computer.
Commit – A saved snapshot of your changes in Git, similar to a checkpoint in a game.
Fetch – A command (git fetch) that checks for updates from a remote repository but doesn’t apply them yet.
Git – A version control system that tracks changes in your code, allowing you to save, revert, and manage versions.
GitHub – A cloud-based platform that stores Git repositories and enables collaboration with others.
Merge – A command (git merge) that combines changes from different branches or updates from GitHub into your local project.
Merge Conflict – An issue that occurs when Git cannot automatically combine changes from different branches, requiring manual resolution.
Push – A command (git push) that sends your committed changes from your local machine to a remote GitHub repository.
Pull – A command (git pull) that fetches and applies updates from a remote repository to your local project.
Remote – A link between your local Git repository and a version stored on GitHub.
Repository – A storage location where Git keeps track of all versions of your project files.

Thank you!




