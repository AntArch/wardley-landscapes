# git process

git clone https://github.com/AntArch/wardley-landscapes

## Housekeeping

https://github.com/AntArch/wardley-landscapes

cd /wardley-landscapes && git add . && git commit -m "deed processing christmas work" && git push -u origin master

cd /wardley-landscapes && git add . && git commit -m "First push" && git push -u origin master


# Branching

## branch for a weekly update

I've created a branch to represent a single story with:

> git checkout -b 20190227-laptop

General use is:

``` go into branch
git checkout 20190227-laptop
git status
git add .
git status
git commit -m 'Bulk Update'
```

To push: 

first push is:

```
git push --set-upstream origin 20190227-laptop
```

subsequent push is:

```
git push -u origin 20190227-laptop
```


## branch for a single story

I've created a branch to represent a single story with:

> git checkout -b single_narrative

General use is:

``` go into branch
git checkout single_narrative
git status
git add .
git status
git commit -m 'refactored ETL scripts'
git push
```


