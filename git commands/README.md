# Basic Git commands
*This file contains every basic git command for everyday use*

## Cloning a Repo
To clone a repo we use the `git clone` command
- this command can be used to clone our repo as well as other people's repo
### The syntax 
>for personal repo
```
git clone https://{PAT}@github.com/{your username}/{repository}.git...
```
>for other people's repo
```
git clone https//:github.com/{username}/{repository}.git
```
## Staging/Adding d file
to stage or add a file for git to track use `git add` this is used to make git track a file and follow all changes

### The syntax
> To add filename
```
git add filename
```
> to add multiple
```
git add .
```
### Checking file status
the git command `git status` is used to check the status of a file. whether it have been staged or not ans commited or not. also checks the status of working tree

### The syntax
```
git status
```

## Commiting a file
the command for commiting a file is `git commit`.  This is uded to commit all statged file to git. a comitted file can be tracked with its automaticallygenerated hash key or later use

### The Syntax
> to just commit with a message
```
git commit -m  message
```

-the flag *-m* stands for messgage with the expected message within a quotation marks
-the messages are identifies for what that commit is all about
>to add and commit an already tracked file
```
git commit -a -m "message"
```
- the *-a* is for add

## Pushing to github or any remote repo
The command `git push` is used to push our commit to any remote repositories like github or gitbucket
### The Syntax
>Repo with single branch and automatic upsteam
```
git push
```
>Repo with multiple branch and non generic upstream name *i.e: origin*
```
git push upstream-name branch-name
```