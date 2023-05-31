# HostingTest and Pushish to GitHub
Trying to test the hosting using Pages

## How to push ur code from local to github??
create a new repository in ur github then follow these steps:-
1. Make sure you have Git installed on your computer. You can download and install Git from the official website: https://git-scm.com/downloads

2. Open a terminal or command prompt on your computer.

3. Navigate to the folder that contains the files and folders you want to upload to the GitHub repository. You can use the cd command to change directories.

4. Initialize a new Git repository in your local folder by running the following command:
    git init
5. Connect your local repository to the GitHub repository by adding the remote repository URL:
    git remote add origin https://github.com/rahimunshaik/iPod.git
    
6. Add the files and folders in your local directory to the Git repository[folder next to the main files]:
    git add .
7. Commit the changes with a meaningful commit message:
    git commit -m "Initial commit"
8. Push the changes to the remote repository on GitHub:
    git push -u origin master
Note: If you are using a different branch instead of the master branch, replace master with the name of your branch.

9.Enter your GitHub username and password (or token) when prompted.

========================#############################################################################+===========================
git init
git remote add origin ur_repo_linkhere
git add .
git commit -m "Initial commit"
git push -u origin master

PS C:\Users\n1606\Desktop\Rahim_CodingNinjas\MileStone-9_React\9.Mini_project\My_1\my_1> git init
Reinitialized existing Git repository in C:/Users/n1606/Desktop/Rahim_CodingNinjas/MileStone-9_React/9.Mini_project/My_1/my_1/.git/
PS C:\Users\n1606\Desktop\Rahim_CodingNinjas\MileStone-9_React\9.Mini_project\My_1\my_1> git remote add origin https://github.com/rahimunshaik/iPod.git
PS C:\Users\n1606\Desktop\Rahim_CodingNinjas\MileStone-9_React\9.Mini_project\My_1\my_1> git add .
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in package-lock.json.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in package.json.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in public/index.html.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in src/App.js.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in src/index.css.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in src/index.js.
The file will have its original line endings in your working directory
PS C:\Users\n1606\Desktop\Rahim_CodingNinjas\MileStone-9_React\9.Mini_project\My_1\my_1> git commit -m "Initial commit"
[master 3f16a0d] Initial commit
 22 files changed, 32071 insertions(+), 29987 deletions(-)
 rewrite package-lock.json (61%)
 delete mode 100644 src/App.css
 rewrite src/App.js (82%)
 delete mode 100644 src/App.test.js
 create mode 100644 src/Artists.js
 create mode 100644 src/Games.js
 create mode 100644 src/Home.js
 create mode 100644 src/Ipod.js
 create mode 100644 src/Music.js
 create mode 100644 src/MyMusic.js
 create mode 100644 src/Screen.js
 create mode 100644 src/Settings.js
 create mode 100644 src/assets/images/Rahim.jpg
 create mode 100644 src/assets/images/zarzzara.jpg
 create mode 100644 src/assets/music/Zarazara.mp3
 rewrite src/index.js (79%)
 delete mode 100644 src/logo.svg
 delete mode 100644 src/reportWebVitals.js
 delete mode 100644 src/setupTests.js
PS C:\Users\n1606\Desktop\Rahim_CodingNinjas\MileStone-9_React\9.Mini_project\My_1\my_1> git push -u origin master
Enumerating objects: 46, done.
Counting objects: 100% (46/46), done.
Delta compression using up to 8 threads
Compressing objects: 100% (45/45), done.
Writing objects: 100% (46/46), 4.07 MiB | 2.63 MiB/s, done.
Total 46 (delta 8), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (8/8), done.
To https://github.com/rahimunshaik/iPod.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
PS C:\Users\n1606\Desktop\Rahim_CodingNinjas\MileStone-9_React\9.Mini_project\My_1\my_1>
