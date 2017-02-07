#Trabajando con repositorio remoto

> Repositorio Remoto
```
git clone https://github.com/dotnet/core.git
git log --oneline
git log --oneline | wc -l
git log --oneline --graph
git shortlog
git shortlog -sne
git show HEAD
git show HEAD~2
git remote
git remote -v
cat .git/config
git branch
git branc -r
git tag
```

> Merge - Tags
```
git branch -r
git remote -v
git rtemote add origin <url remote>
git fetch
git log origin/master
git merge origin/master
git pull --allow-unrelated-histories origin master
git add .
git commit -m <mensaje>
git merge origin/master
git branch --set-upstream-to=origin/master master
git pull
vim Readme.txt
git status
git commit -am "<comentario>"
git status
git push
git tag v1.0
git tag
git log
git tag -a v1.0_With_Comments
git tag -d v1.0
git push
```