# TemporaryRepo
Techolympics Training
 git branch lab_1
 git checkout lab_1
 echo "change 1" >> tmp.txt
 git add tmp.txt
 git commit -m "commit 1"
 echo "change 2" >> tmp.txt
 git add tmp.txt
 git commit -m "commit 2"
 git commit -m "commit 3"
 cat tmp.txt
 git status
 git log
 git rebase -i HEAD~3
 pick a81bb1 "commit 1"
 squash 069a09b "commit 2"
 squash 941e2d "commit 3"
 
