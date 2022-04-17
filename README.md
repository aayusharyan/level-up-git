READ ME -> First file of any code which is supposed to be read by the engineer / developer.

1. What is Git?
-> Git is a tool to maintain version. (VCS -> Version Control System). It will track all things inside your folder where you have initialized it.

How to initialize:
https://git-scm.com/downloads
Open the command prompt in your folder.

Initialize git
> git init

To check for changed files
git status

To add any file
git add <file_path> <file_path>

git add . (For all files, not recommended)

To commit
git commit -m "<Meaningful message>"


To check history
git log

Github is a place where we can add git managed code.

The parent foder is equivalent to 1 repository.

Remote -> A different place.

upstream origin main abcd1234

Added the remote
git remote add <name> <repository URL>

View remotes -> git remote -v

git push -u origin master

branches
-> Same code multiple copies.

git branch -> List of all branches, green color is active.


1. git status -> Check for changes.
2. git add -> Add the specific files for the commit.
3. git commit -> Make a commit (like a checkpoint)
4. git push -> Push it to remote (github)

git branch <new_branch_name>
