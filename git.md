### `git clone` 

Downloads a copy of a remote repository to your local machine. This command is used to create a local copy of a shared repository so that you can work on it locally.

### `git init` 

Initializes a new Git repository in the current directory. This command creates a new .git subdirectory that contains all the necessary files for Git to track changes in your project.

### `git remote` 

Shows the remote repositories that are associated with the current repository. This command is used to manage connections to remote repositories, such as adding or removing a remote repository. Common way to use is:

```
git remote add origin https://github.com/you/your-project
```
which will connect the local directory with the repo made at Github.

### `git status` 

Shows the current status of the repository, including any changes that have been made, files that have been added to the staging area, and files that have been modified but not yet staged.

### `git add` 

Adds files to the staging area. Files in the staging area are not yet committed but are ready to be committed. You can add files individually (`git add <filename>`) or add all files in the current directory (`git add .`).

### `git commit` 

Commits the changes in the staging area to the repository. Each commit should have a descriptive message that summarizes the changes made. Common way to use it is:

```
git commit -m “description of change” -m “optional extended description..."
```

### `git push` 

Uploads local changes to a remote repository. This command requires write access to the remote repository and is typically used to push changes to a shared repository on GitHub or another hosting service. Common way to use it is:

```
git push origin master/main #etc.
```
### `git log` 

Shows a log of all the commits in the repository. This command is used to view the history of changes made to the repository, including who made the changes and when they were made.

### `git pull` 

Downloads changes from a remote repository and merges them with the local repository. This command is typically used to update the local repository with changes made by others. Common way to use it is:

```
git pull origin master
```

### `git branch` 

Shows a list of branches in the repository. You can create a new branch (`git branch <branchname>`) or switch to an existing branch (`git checkout <branchname>`).

### `git checkout`

Switches to a different branch or restores files to a previous version. This command is used to navigate between different branches or restore files to a previous state. Common way to use it to create a new branch and switch to it is:

```
git checkout -b new-branch
```

### `git diff`

Shows the differences between the working directory and the staging area or the staging area and the repository. This command is used to review changes before committing them.

### `git merge` 

Merges changes from one branch into another branch. This command is typically used to integrate changes from a feature branch into the main branch of the repository.

### ```git reset```

Removes files from the staging area or resets the repository to a previous state. This command is used to undo changes that have not yet been committed. Common way to use it to go back to a state before commit is (unstage and uncommit):

```
git reset HEAD~1 
```
Or to go back before a certain commit, put hex number of that commit instead of `HEAD~1`.








