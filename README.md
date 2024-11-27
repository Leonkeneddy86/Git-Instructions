## Git-Instructions
This is a more or less detailed guide to Git commands that I will update as I expand my knowledge as a developer.

## Documentation
- The official Git guide
- [Documentation](https://git-scm.com/docs)
## Initial configuration
```
git config --global user.name ‘Your Name’: Set your username for commits.
```
```
git config --global user.email ‘tu@email.com’: Set your email address for commits.
```
## Creating a repository
```
git clone https://github.com/usuario/repositorio.git: Clones a remote repository to the current folder.
```
```
git clone https://github.com/usuario/repositorio.git /path/to/repository: Clones a remote repository to the specified path.
```

## Working with files

Below is a list of Git commands along with a brief description of each

```git add .``` 
Adds all modified and new files to the preparation area.

```git commit -m "commit message"``` 
Creates a new commit with the changes in the staging area and a descriptive message.
git status: Displays the current status of the repository, including modified files, untracked files and the status of the staging area.

## Working with Branches
```git branch:``` 
Displays a list of existing branches in the repository.

```git branch <name>:``` Creates a new branch with the specified name.

```git checkout <name>:``` Switches to the specified branch.

```git checkout -b <name>:``` Create and switch to a new branch.

```git merge <name>:``` Join the specified branch with the current branch.

```git rebase <name>:``` Applies changes from the current branch to the specified branch.

## Working with Remote Repositories

```git fetch <name>:``` Fetches changes from the remote repository without applying them.

```git pull <name>``` <branch>: Fetches and merges changes from the remote repository to the current branch.

```git push <name>``` <branch>: Push changes from the local branch to the remote repository.

## Other Useful Commands

```git stash:``` Temporarily saves un-committed changes to a storage area.

```git cherry-pick <commit>:``` Applies changes from a specific commit to the current branch.

## Help Commands

```git help <command>:``` Displays help for a specific command.

```git --version:``` Displays the version of Git installed.

## conventional-commit-types
Companies value a lot the type of commit and the reason of the commit, it doesn't make sense to make commits if you haven't done anything in your project, the most experts make commits every 16-30 minutes, but for beginners I recommend to make commits for every important change, here I leave an external repository for you to apply the conventional commits.

- [Conventional commits](https://github.com/pvdlg/conventional-commit-types)






