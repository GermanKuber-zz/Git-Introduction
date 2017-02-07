#Trabajando con repositorio local

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

> Diff
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



touch file1.txt file2.txt
git status
git add -u
git add .
gitt status
git commit -m "Nuevos archivos"
git diff HEAD~1
vim file1.txt 
vim Readme.txt
git status
```

>Last

```
git add file1.txt
git status
git commit -m "Primer archivo"
git add .
git commit -m "Se agregue Readme.md"
rm file2.txt
git status
git add -u
mv file1.txt  new_file_name.txt
git status
git add -a
git commit -m "Se mueven archivos"
vim Readme.txt
git status
git checkout Readme.txt
car Readme.txt
vim Readme.txt
rm new_file_name.txt
git status
git reset --hard
git log
git reset --soft HEAD~1
git commit -m "Nuevo reset"
git reset --hard HEAD~1
git log
touch tmp1.txt tmp2.txt
git clean
git clean -n
git clean -f
git status
mkdir log
touch log/log.txt
git status
vim .gitignore
git status
git add .
git commit -m "Se agrega .gitignore"
git log
git add .
```