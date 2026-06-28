## Git hidden Folder

There is a `.git` hidden folder that tells project is agit repo  

If we want to creat a git repo in a new project, we ccreate the folder and then initialize that repo using 
```sh
git init
```

## cloning

3 ways: HTTPS, SSH, CLI

### HTTPS

```sh
 git clone https://github.com/Shibani-Patro/GitHub-Examples.git

```
### SSH

```sh
ssh-keygen -t rsa
```

### CLI

```sh
gh auth login
gh repo clone Shibani-Patro/GitHub-Examples
```

## commit

## branches

## remotes

we can add remote often via upstream when adding branch
```sh
git remote add .
git branch -u origin new-feature
```

## stashing
 ```sh
 git stash
 git stash list
 git stash pop
 git stash apply
 git stash save name
 ```


 
## merging

```sh
git checkout dev
git merge main
```

## Reset
allows to move staged changes to be unstaged.

## gitconfig file 

stores your global configuration for git such as email,name, editor and more.

## Remove file/folder using terminal

```sh
rm -rf <file/folder name>
```