# How to use Git
When we want to create a new git repository...

## CMD - Commands
`mkdir <Directory Name>` - Create Directory<br>
`rename <Old Name> <New Name>` - Rename File <br>
`echo <file-Content> >> <Filename>.<Extention>` - Create new file

## Setting up remote  
Before we begin we need to tell the command promt where we want to pull / Push our repository to. We can do that by writing `git remote add origin https://github.com/<username>/<repository>`

## Add
We begin by selecting the files we later want to commit this can by done by either: `git add --all` or by writing `git add <file>`. By sepperating the files we are able to have multiple commits with different messages ex -> 

``` batch
git add ReadMe.md
git commit -m "fixed ReadMe typo"
git push
git add Program.exe "Directory with long name"
git commit -m "Fixed Bug"
git push
```

_note: with `git add` you can add multiple files or directories by sepperating the names with a " " (space), when using names longer than 1 word you have to wrap them in quotes._

## Commiting
`git commit -m "<message>"`

## Push (Update)
If we want to update our whole repository we can simpy write `git push -u origin master`

## Delete files

## Pull 
make sure you are on the correct branch by typing `git branch`, you wil get list of all branches where the current branch is hilighted in green whith a star in front (*)

## Description
To add Description type `git commit -a -m "<title>" -m "<Description>"`

## Change Branch
`git checkout <Branch Name>`