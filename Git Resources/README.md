### Daily Used Git Command
1. git init
  * Initializes a Git repository in the current directory.
``` git init ```
2. git clone
* Clones an existing Git repository from a remote location to your local machine.
```git clone https://github.com/user/repo.git ```
3. git status
* Checks the status of the working tree, including modified files, staged changes, and untracked files.
```git status```
4. git add

* Adds files or changes to the staging area, preparing them for the next commit.
``` git add file1.txt file2.js git add .   # Adds all changes to the staging area ```
5. git commit

* Creates a snapshot of the current changes in the staging area, along with a message describing the changes.
```git commit -m "Initial commit" ```
6. git push

* Sends committed changes from your local repository to the remote repository.
```git push origin master ```
7. git pull

* Fetches and merges changes from the remote repository to your local repository.
```git pull origin master```
8. git branch
* Manages branches, allowing you to create, list, delete, and switch between different versions of your code.
``` git branch dev   # Creates a new branch named "dev"
git branch       # Lists all branches
git checkout dev # Switches to the "dev" branch
```
9. git merge
* Combines changes from one branch into another.
```git merge dev```
10. git log
* Views the history of commits in the repository.
```git log```


### Step to create new repo and push to Github

1. Create a new repository on GitHub:
 * Go to the GitHub website, log in, and click on the "+" sign in the top right corner. Choose "New repository" and follow the instructions to create a new repository. Do not initialize it with a README since you already have an existing project.

2. Open your terminal or command prompt.
   * Navigate to your local project directory using the cd command. For example:
   * ``` cd path/to/your/local/project ```
3. Initialize a new Git repository: 
  *  `git init`

4. Add all the files in your project to the Git repository:
  * `git add .`
  * If you want to add specific files, you can replace . with the file names.

5. Commit the changes:
 * ```git commit -m "Initial commit"```
 * Replace "Initial commit" with an appropriate commit message.

6. Add the GitHub repository as a remote. Replace username and reponame with your GitHub username and the name of the repository you created:
 * `git remote add origin https://github.com/username/reponame.git`
7. Push the code to GitHub:
* `git push -u origin master`

### Git command to clone existing repo from github
``` git clone "gitrepo.url" ```


### Links to Video Links
 - ##### Working Remotely with Git
 - [Working with Remote branches](https://youtu.be/6D_YArepsuo)
 - [What is origin in git](https://youtu.be/LIHIRBz5ZXk)
 - [What is HEAD](https://youtu.be/ZaI1co-rt9I)
 - [Fetching from remote](https://youtu.be/dABVkph4zo0)
 - [Push and pull](https://youtu.be/csHeaYWspic)
### Links to Text docs.
