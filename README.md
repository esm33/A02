# A02

| Platform | Steps |
| --- | --- |
| Git: Set up & Configure | <ol><li>Install Git by downloading it from the official Git website. Create a GitHub account by navigating to https://github.com and signing up.</li><li>Configure Git by opening a terminal or command prompt. Set up your Git username by using the “git config” command: git config --global user.name "name"  git config --global user.email “youremail@email.com"</li><li>Initialize a new Git repositorythrough the terminal by navigating to the directory where you want it created and entering the git init command</li><li>Create branches (to make copies of the commit history) by entering either commands: git branch NewBranchName (which creates a new branch but keeps the previous one active) or git checkout -b NewBranchName (which creates a branch using -b, but switches to it simultaneously). Note: the command git branch reveals a list of existing local branches including your current branch.</li><li>Add files to the staging area by adding all of the files in the directory using “git add .”  or specific files using “git add fileName.” Commit the added files with a commit message using “git commit -m “Commit Message” To push your changes, run the “git push origin NameOfTargetedBranch” command.</li><li>The browser version of GitHub will ask if you would like to “Compare & Pull Request.” Select this button to start the pull request process. All of your commit history will be showcased here. You may merge the Pull Request and Confirm Merge once you are ready to combine all your work histories into a single branch.</li></ol>|
| GitHub: Install, Edit & Commit | <ol><li>Create an account or login to https://github.com. In order to create a new repository, you could either click the “+” icon in the top right and select New Repository or select the green “New” icon. Make sure to give the repository a relevant name and check the “Add a README file” to save from having to do extra work. Then. Click “Create Repository”</li><li>Install GitHub Desktop by downloading the best version for your operating system. Once downloaded, ensure that your account is authenticated by using the File menu and sleecting Options. In that window, select the “Sign in” button next to the “Github.com” and enter your information in the browser.</li><li>If you do not have Git installed, download the latest version of Git using https://git-scm.com/downloads and configure it.</li><li>To see, edit, and commit changes to remote repositories on Github Desktop, go to the File menu and click “Clone Repository.” Select the tab where your repositories are located, such as “GitHub.com,” and choose its local path.</li><li>After editing files, your changes will be visible under the “Changes” tab and can be committed to your repository by simply filling in the “Summary” text box to activate the “Commit to main” button. Finally, click the blue “Push origin” button to send these commits to your remote repository.</li></ol> |
| VS Code: Install, Clone & Create | <ol><li>Download and install the latest version of VS Code (that best suits your operating system) by navigating to https://code.visualstudio.com/download.</li><li>Once you’ve ensured that Git is installed in your computer, follow these steps: open VS code, go to the File menu, open folder, and select your repository folder.</li><li>Add GitHub to your VS Code by going to the “Source Control.” If you have not already cloned your repository to your machine, select “Clone Repository” and either enter the URL to your GitHubo repository or select “Clone from GitHub.” This will direct you to a browser, where you can log into your Github account.</li><li>Create new files or folders by hovering over your primary folder under the “Explorer” tab and selecting the “new file” or “new folder icon.” Once you’ve made edits to your code, hold the “Ctrl” key and press the “S” key to save your changes.</li><li>To commit your changes, return to the “Source Control” tab on the left-hand side, enter your commit message in the text box, and click on the carrot symbol to reveal a list of commit options. Choose “Commit & Push” to send your changes to Github.</li></ol> |


## Glossary/Definitions
### ***Branch***
+ A new/separate version of the main repository that points to a specific commit.

### ***Clone***
+ A command that is used to create a copy of a specific repository or branch within a repository.

### ***Commit***
+ A command that records changes to one or more files in a branch

### ***Fetch***
+ A command used to retrieve new work done by other people. This allows a repository to grab all new remote-tracking branches and tags without merging the changes into one’s own branches.

### ***GIT***
+ A version control system used for tracking changes in computer files.

### ***Github***
+ A web-based, code hosting platform for version control and collaboration.

### ***Merge***
+ A command that combines changes in a branch with another branch in order to create a new commit.

### ***Merge Conflict***
+ An event that occurs when one merges branches with competing commits, and requires one to decide what changes will be included in the final merge.

### ***Push***
+ A command that uploads all local branch commits to the corresponding remote branch.

### **Pull***
+ A command that updates one’s current local branch after interacting with a repository.

### ***Remote***
+ A command that manages the set of remote branches that one is tracking with their local repository.
Refers to the location where one’s code is stored.

## ***Repository***
+ The location where one stores their code, files, and each file’s history.

## Reference List
https://www.w3schools.com/git/git_branch.asp?remote=github
https://www.gitkraken.com/learn/git/git-checkout#:~:text=In%20Git%2C%20a%20branch%20is,a%20specific%20point%20in%20time.
https://github.com/git-guides/git-clone
https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits#:~:text=Similar%20to%20saving%20a%20file,Who%20created%20the%20changes
https://www.simplilearn.com/tutorials/git-tutorial/what-is-git#:~:text=Git%20is%20a%20version%20control,code%20management%20in%20software%20development. 
https://docs.github.com/en/get-started/quickstart/hello-world#:~:text=GitHub%20is%20a%20code%20hosting,%2C%20commits%2C%20and%20pull%20requests. 
https://www.geeksforgeeks.org/git-merge/ 
https://docs.github.com/articles/about-merge-conflicts#:~:text=Merge%20conflicts%20happen%20when%20you,branches%20and%20merge%20them%20automatically. 
https://github.com/git-guides/git-push 
https://github.com/git-guides/git-pull 
https://docs.github.com/articles/about-remote-repositories#:~:text=A%20remote%20URL%20is%20Git's,on%20a%20completely%20different%20server. 
https://github.com/git-guides/git-remote 
https://docs.github.com/repositories/creating-and-managing-repositories/about-repositories#:~:text=A%20repository%20is%20the%20most,be%20either%20public%20or%20private. 