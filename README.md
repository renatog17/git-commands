This repo was created as a way to study git. Here, I'll explain git commands that I have been learning.
```
git commit -m '<message>'
```
This command is used to save a state of a project.

---
```
git push -u origin main
```
This command is used when a new project is created. The -u means a link between a local branch and remote branch. It is only needed at the first time, afterwards only ```git push``` can be used.

---

```
git pull
```
Git pull is used to update a local repository with the latest changes from a remote repository.
Another way to do a ```git pull``` is using ```git fetch``` and ```git merge``` commands.

----

```
git restore <commit hash>
```

This command is used when it's necessary to go back to a previous state in a project.

---

Git branch is used to do some operations related to branchs.
```
git branch
```
This command lists all local branchs in a repository.

```
git branch <branch-name>
```
With this param is possible to create a new branch.

```
git branch -d <branch-name>
```
This command will delete a branch passed in param.

```
git branch -r
```
It will shows all branchs in remote repository.

```
git branch -a
```
It will shows all branchs both remote and local repository.
