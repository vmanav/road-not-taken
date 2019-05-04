# Road not Taken
Path Suggester.

## How to install on your ubuntu system
```
sudo apt-get install graphviz

sudo apt-get install w3m

git clone https://github.com/Code-with-ease/road-not-taken.git

cd road-not-taken

g++ setup.cpp -std=c++11 -o a.o

./a.o
```
### create and do work in your own branch
```
git branch banchname

git checkout branchname

edit your code

git checkout branchname

git merge branchname
```
### Before you Push
```
git pull origin master

git add .

git commit -m "commit message"

git push origin master
```

### if not correctly pulled
```
git stash

git pull origin master
```

## if x commit ahead and y commit behind
```
copy your changed files first for safety somewhere else

git remote add upstream https://github.com/Code-with-ease/rode-not-taken.git

git pull --rebase upstream master

git push --force-with-lease origin master
```

### Developer Team
[Akshara Nigam](https://github.com/aksharanigam1112)

[Ayush Nagar](https://github.com/ayushnagar123)

[Kapil Kumar Israni](https://github.com/090max)

[Manav Verma](https://github.com/vmanav)
