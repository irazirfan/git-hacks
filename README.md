# **Git Hacks**
> git necessary cli commands and approach


## **delete commits by ~~mistake~~ from local working tree**

```
git reset HEAD~<n commit/s>
git checkout <last correct commit sha> -- filename.ext
```

## **delete commits by ~~mistake~~ from github remote working tree**

```
git reset HEAD~<n commit/s>
git checkout <last correct commit sha> -- filename.ext
git push origin master -f
```

## **update remote branch list from origin**

```
git remote update origin --prune
```


## **fix powershell error of running ng commands**

```
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```
