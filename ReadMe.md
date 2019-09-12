# HOMEWORK - Testing Git and Repo
## Explain Git VS Github
The key difference between Git and GitHub is that Git is an open-source tool developers install locally to manage source code, while GitHub is an online service to which developers who use Git can connect and upload or download resources.
##	Common Git Commands
#### Working with local repositories
Working with Git on the command line can be daunting. To help with that, we’ve put together a list of common Git commands, what each one means, and how to use them

### git init.
This command turns a directory into an empty Git repository. This is the first step in creating a repository. After running git init, adding and committing files/directories is possible.

### git add.
Adds files in the to the staging area for Git. Before a file is available to commit to a repository, the file needs to be added to the Git index

### git commit.
Record the changes made to the files to a local repository. For easy reference, each commit has a unique ID.It’s best practice to include a message with each commit explaining the changes made in a commit. Adding a commit message helps to find a particular change or understanding the changes.

### git status.
git status will return the current working branch. If a file is in the staging area, but not committed, it shows with git status. Or, if there are no changes it’ll return nothing to commit, working directory clean.
### git config.
git remote.
To connect a local repository with a remote repository. A remote repository can have a name set to avoid having to remember the URL of the repository
git checkout.
To start working in a different branch, use git checkout to switch branches.

##	Explain AND have a .gitignore file
The .gitignore file is a text file that tells Git which files or folders to ignore in a project. A local .gitignore file is usually placed in the root directory of a project
