#  Essential Git Commands for Machine Learning Engineers!

In the professional world, we often work under tight deadlines. It's crucial for all engineers to be aware of certain Git commands that can help us save time and streamline our tasks.
There are specific Git commands that can save time and are essential for all engineers to be familiar with.

### Stage and Commit Multiple Files with One Command
Instead of running two separate commands to stage and commit all changed files, the -am flag allows you to do both in one step.
This saves time and effort, and makes your Git workflow more efficient.
```
git commit -am "Commit_Message"

```
Check the git.md file for individual commands.


### Create and Switching branch with One Command
Suppose you want to create a branch and also switch your current branch to a new branch. Instead of doing individual commands 
you can try  this following commands.
The -b flag with the git checkout command allows you to not only create a new branch but also switch you to it immediately.

```
git checkout -b branch_name
```
### Renaming Branch without any hassel
To rename a branch, you can use the git branch -m command followed by the current branch name and the new desired branch name. For example, if you want to rename a branch called Dev to dev, you would run:
```
git branch -m Dev dev

```


If you wish to rename the branch you are currently working on without explicitly specifying its previous name, you can utilize the following command.Here, you don’t need to specify the old branch name because Git will assume that you want to rename the current branch to the new name. Suppose the current branch is Dev now run the command to change the branch name to Dev.
```
git branch -m dev
```

### Discarding Changes to a Specific File
If you want to get the file back to how it was before any recent changes, then this command is your solution. It's a simple way to start fresh with that file while leaving everything else untouched.
```
git checkout -- filename
```


