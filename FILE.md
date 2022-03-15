1 git init
2 git add FILE.md
3 git commit -m "Commit 0"
4 git checkout -b bug-fix
5 git checkout master
6 git commit -a -m "Commit 1"
7 git commit -a -m "Commit 2"
8 git checkout bug-fix
9 git commit -a -m "Commit 3"
10 git commit -a -m "Commit 4"
11 git checkout -b bug-fix-experimental
12 git checkout bug-fix
13 git commit -a -m "Commit 5"
14 git merge master
15 git mergetool
16 git commit -a -m "Commit 6"
17 git checkout bug-fix
18 git commit -a -m "Commit 11"
