# Git





## git clone
download the latest remote repo

```
git clone [remote url]
```

example : `$ git clone https://github.com/iosum/Git`


## perform change

1. check the status of the current repo

```
git status
```

2. add the file to the staging area

```
git add [fileName]
```

3. commit the changes

```
git commit -m "your message here"
```

if we omit the -m it will pop up the text editor where
we can write multi lines messages.


![](images/git-perform-changes.png)


## remove the file after the commit

1. remove the file 

```
git rm [fileName]
```

2. commit the change

```
git commit -m "your message"

```

3. push to remote repo

```
git push origin master
```

![git-rm-image](images/git-rm.png)

## git log

- view every commit messages


![git-rm-image](images/git-log.png)

## git show

- view the commit detail


## git diff

- review the changes in the file

![git-rm-image](images/git-diff.png)

> exit git show : press q

## git commit --amend -m

- change the latest commit message

## git push

- The `Push` operation stores data permanently to the Git repository.

`$ git push origin master`

## git pull

- update the local projects

- executes the `git pull` command to synchronize the local repository with the remote one. 

git pull | git clone
-|-
you have the project in your local repo and only want to see the changes | you don't have the project in your local machine and you will need clone all project files|
multiple times | probably only once

