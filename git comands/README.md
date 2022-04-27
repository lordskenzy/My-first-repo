# Basic Git commands
*This file contains every basic gitcommands for everyday use*

## Cloning a Repo
To clone a repo we use the `git clone` command
- This command can be use to clone our repo as well as other people's repo
### The synthax
> For personal repo
```
git clone
https://{PAT}@github.com/{your username}/{repository name}.git
```
> for other people's repo
```
git clone https://github.com/{username}/{repository}.git
```
# Stagging/Adding a file
to stage or add a file for git to track
use `git add .` This is used to make git track a file andd follow all changes
### The Synthax
> To add one file
```
git add filename
```
>to add multiple file
```
git add .
```

## Checking file status
The git command `git status` is used to check the status of a file. whether it have been staged or not and commited or not. also checks the status of working tree.
### The Synthax
```
git status
```

## committing a file
The command for commiting aa file  is `git commit`. this is used to commit all stage file to git. a commited file can be tracked with it's automaatically generated hash key for later use 
### The Synthax
> To commit witth a message
```
git commit -m "message" 
```
- the flag *-m* stands for message with the expected message within a quotation marks
- the messages aare identifies for what that commit is all about
> To add and commit an already tracked file
```
 git commit -a -m "message"
 ```
 - the *-a* is for add

 ## pushing to github or any remote repo
 the command `git push` is used to push
 our  commit to any remote repositories like github or gitbucket
 ### The Synthax
 > Repo with single branch and automatic upsteam
 ```
 git push
 ```
 > Repo with multiple branch and non generic upstream *i.e: origin*
 ```
 git push upstream-name branch-name
 ```