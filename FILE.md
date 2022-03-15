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
17 git checkout bug-fix-experimental
18 git commit -a -m "Commit 7"
19 git commit -a -m "Commit 8"
20 git commit -a -m "Commit 9"
21 git checkout master
22 git commit -a -m "Commit 10"
23 git checkout bug-fix
24 git commit -a -m "Commit 11"
25 git merge bug-fix-experimental
26 git mergetool
27 git commit -a -m "Commit 12"
28 git checkout master
29 git merge bug-fix
30 git mergetool
31 git commit -a -m "Commit 13"
