# Github-Examples
A repo containing GitHub for programmatic examples

## Git Hidden Folder

There is a hidden foler called `.git` which tells you that our project is a git repo.

## Cloning

We can clone in 3 ways:
- HTTPS
- SSH
- Github CLI

Since we are using SSH, you can create a new directory for your workspace.

```sh
mkdir Github-Cert
cd Github-Cert
```

### HTTPS

```sh
git clone https://github.com/DonMcQueen/Github-Examples.git
```

### SSH

```sh
git clone git@github.com:DonMcQueen/Github-Examples.git
```

### GitHub CLI

```sh
gh repo clone DonMcQueen/Github-Examples
```

### SSH

## Commits

When we want to commit code, we can write git commit which will open up the commit edit messsage in the editor of choice.

```sh
git commit
```

## Branches

## Remotes

## Stashing

## Merging

## Add

When we want to stage changes that will be included in the commit.
We can use the . to add all possible files.
```
git add Readme.md
git add .
```

## Reset

Reset allows you to move Staged changes to be unstaged.
This is useful when you want to revert all files to not be committed.
```sh
git add .
git reset
```

> git reset will revert a git add.

## Status

Git status show you what files will or will not be committed.
```
git status
```

## Gitconfig file

The gitconfig file is what stores your global configurations for git such as email, name, editor and more.

Showing the contents of our .gitconfig file.
```
git config --list
```

When you first install Git on a machine, you are suppose to set up your name and email.
```sh
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```

## Log

Git log will show recent git commits to the git tree.

```sh
git log
```

## Push

When we want to push a repo to our remote origin