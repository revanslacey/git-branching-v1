1 git init
2 git add FILE.md
2.5 git checkout bug-fix
3 git commit -a -m "Commit 3"
4 git commit -a -m "Commit 4"
5 git checkout -b bug-fix-experimental
6 git checkout bug-fix
7 git commit -a -m "Commit 5"