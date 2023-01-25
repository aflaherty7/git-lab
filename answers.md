Answer 1: 

git version 2.17.1

Answer 2: 

user.name=Aidan Flaherty
user.email=af674321@ohio.edu
core.repositoryformatversion=0
core.filemode=true
core.bare=false
core.logallrefupdates=true
remote.origin.url=https://github.com/aflaherty7/git-lab.git
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*
aflahert@odd19:~/git-lab$ 


Answer 3:

It opens up the Git Manual for all the help

Answer 4:

On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   README.md
	modified:   answers.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	git-lab-2/

no changes added to commit (use "git add" and/or "git commit -a")

Answer 5: 

On branch main
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   README.md

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   answers.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	git-lab-2/

Answer 6: 

On branch main
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   README.md
	modified:   answers.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	git-lab-2/


Answer 7: 

[main 32041dd] Initil commit
 1 file changed, 1 insertion(+)
 create mode 100644 git-lab-2/README.md
aflahert@odd19:~/git-lab$ git status
On branch main
nothing to commit, working tree clean



Answer 8:

commit 32041dd48470598cab796a478d3062c3109f6415 (HEAD -> main)
Author: Aidan Flaherty <af674321@ohio.edu>
Date:   Tue Jan 24 21:56:34 2023 -0500

Answer 9:

Counting objects: 15, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (11/11), done.
Writing objects: 100% (15/15), 2.29 KiB | 292.00 KiB/s, done.
Total 15 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/aflaherty7/git-lab.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.

Answer 10: 

No, because we haven't pushed it yet

Answer 11:

It rejected me because the files havne't been pulled locally yet 

To https://github.com/aflaherty7/git-lab.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/aflaherty7/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
aflahert@odd19:~/git-lab$ 


Answer 12:
It merged my files

All modified files have been saved.
Merge made by the 'recursive' strategy.

Answer 13:

aflahert@odd19:~/git-lab$ ls -a
.  ..  answers.md  DEADJOE  .git  git-lab-2  README.md
