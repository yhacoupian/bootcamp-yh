## Naming a new branch 

git checkout -b branch_name


## Git common commands for when...

You want to download a new repo for the first time:

```
git clone https://url-copied-from-website
```


You're starting work on a shared project. You should

```
git pull
```

You're trying to remember if you are up to date or not, or what is ready to upload.

```
git status
```

You got a new feature working or a bug fixed. It is time to check that in.

```
git status
git checkout -b new_branch_name
git add .
git commit -m "commit message here"
git push
```

**The last command will show you another command you'll need to copy/paste/run**

After checking in, your github manager will need to do the merge on the website.

git push origin master 

### List all the branches 
git branch 

### Check out a branch 
git checkout -b branch_name 

fetch (gets all the branches) vs pull (gets the updates on a specific branch) 


## ***Branching***

git checkout -b my_branch_name
git add README.md
git commit -m "my message"
git push --set-upstream origin my_branch_name

## Tips and Tricks!
Create a `.gitkeep` file within each subfolder so that git knows to retain the empty folder. (Remember, empty folders are not added to git repos by default.)

Before you can clone your repository from the command line, you will need to configure the command line to your GitHub username and email address.  To do this run the following two commands, substituting your own GitHub username and the email you used to set up GitHub:<br>
`git config --global user.name "YOUR_USERNAME"`<br>
`git config --global user.email "your_email_address@example.com"`