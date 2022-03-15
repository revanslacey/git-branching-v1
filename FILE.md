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
12 git commit -a -m "Commit 7"
13 git commit -a -m "Commit 8"
14 git commit -a -m "Commit 9"
15 git checkout bug-fix
16 git commit -a -m "Commit 5"
17 git merge master
18 git mergetool
19 git commit -a -m "Commit 6"
20 git checkout bug-fix
21 git commit -a -m "Commit 11"
22 git merge bug-fix-experimental
23 git mergetool
24 git commit -a -m "Commit 12"
