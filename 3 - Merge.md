#Merge

> Repositorio Remoto

```
git log --graph --oneline --all --decorate
git config --global alias.lga "log --graph --oneline --all --decorate"
cat ~/.gitconfig
git branch feature1
git checkout feature1
git lga
echo "Feature 1" >> README.txt
git commit -am "<mensaje>"
git lga
git checkout master
git lga
git branch fix1 <commit id>
git chckout fix1
git lga
echo "Fix Bug:#1234" >> README.txt
git commit -am "Se arregla el bug #1234"
git checkout master
git branch -m fix1 bug-1234
git checkout master
git branch -d bug-1234
git branch -D bug-1234
git checkout -b feature2
echo "Feature 2" >> Readme.txt
git commit -am "Se agrega feature 2"
git lga
```

> Commits eliminados

```
git reflog
git branch bug1234 <commit id bug1234>
git checkout bug1234
git show HEAD
```

> Stashing

```
git checkout feature2
echo "Feature 2 changes" >> Readme.txt
git status
cat Readme.txt
git stash
cat Readme.txt
git stash list
git branch -m  bug-123-A
echo "Error bug-123-A ARREGLADO" >> Readme.txt
git commit -am "Se arregla Bug 1234 A"
git stash list
git stash pop
echo "Mas cambios" > NewFileFeature2.txt
git stash
git add NewFileFeature2.txt
git stash
git stash branch feature2_new_file
echo "Nuevo file" >> Readme.txt
```

> Merge
```
git checkout master
git lga
git merge feature1
git branch -d feature1
git merge feature2
git mergefeature
git diff --cached
git commit -m "Merge de Feature 2 con Master"
rm Readme.txt.orig
```
