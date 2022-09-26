# demo
============================
1. Fetch all remote branches
============================
git fetch origin

OU

fbacher@ITEM-S94247 MINGW64 /c/workspaceFormationGit/Git_faybac/demo (main)
$ git remote add origin https://github.com/faybac/demo.git

============================
2. Pull changes from a remote branch
============================
fbacher@ITEM-S94247 MINGW64 /c/workspaceFormationGit/Git_faybac/demo (main)
$ git checkout 1-opération-sur-les-merges
Switched to a new branch '1-opération-sur-les-merges'
Branch '1-opération-sur-les-merges' set up to track remote branch '1-opération-sur-les-merges' from 'origin'.








error: remote origin already exists.

fbacher@ITEM-S94247 MINGW64 /c/workspaceFormationGit/Git_faybac/demo (main)
$ git branch
* main

fbacher@ITEM-S94247 MINGW64 /c/workspaceFormationGit/Git_faybac/demo (main)
$ git checkout 1-opération-sur-les-merges
error: Your local changes to the following files would be overwritten by checkout:
        README.md
Please commit your changes or stash them before you switch branches.
Aborting

fbacher@ITEM-S94247 MINGW64 /c/workspaceFormationGit/Git_faybac/demo (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md


fbacher@ITEM-S94247 MINGW64 /c/workspaceFormationGit/Git_faybac/demo (main)
$ git commit -m "commit du readme : ajout des commandes"
[main 19a9344] commit du readme : ajout des commandes
 1 file changed, 23 insertions(+)

fbacher@ITEM-S94247 MINGW64 /c/workspaceFormationGit/Git_faybac/demo (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

fbacher@ITEM-S94247 MINGW64 /c/workspaceFormationGit/Git_faybac/demo (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

fbacher@ITEM-S94247 MINGW64 /c/workspaceFormationGit/Git_faybac/demo (main)
$ git push README.md
fatal: invalid gitfile format: README.md
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

fbacher@ITEM-S94247 MINGW64 /c/workspaceFormationGit/Git_faybac/demo (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

fbacher@ITEM-S94247 MINGW64 /c/workspaceFormationGit/Git_faybac/demo (main)
$ git branch
* main

fbacher@ITEM-S94247 MINGW64 /c/workspaceFormationGit/Git_faybac/demo (main)
$ git add README.md

fbacher@ITEM-S94247 MINGW64 /c/workspaceFormationGit/Git_faybac/demo (main)
$ git commit -m "ajout de commandes dans README.md"
[main f4aabc1] ajout de commandes dans README.md
 1 file changed, 7 insertions(+), 1 deletion(-)

fbacher@ITEM-S94247 MINGW64 /c/workspaceFormationGit/Git_faybac/demo (main)
$ git statu
git: 'statu' is not a git command. See 'git --help'.

The most similar commands are
        status
        stage
        stash

fbacher@ITEM-S94247 MINGW64 /c/workspaceFormationGit/Git_faybac/demo (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 3 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

fbacher@ITEM-S94247 MINGW64 /c/workspaceFormationGit/Git_faybac/demo (main)
$ git branch
* main

fbacher@ITEM-S94247 MINGW64 /c/workspaceFormationGit/Git_faybac/demo (main)
$ git checkout 1-opération-sur-les-merges
Switched to a new branch '1-opération-sur-les-merges'
Branch '1-opération-sur-les-merges' set up to track remote branch '1-opération-sur-les-merges' from 'origin'.

fbacher@ITEM-S94247 MINGW64 /c/workspaceFormationGit/Git_faybac/demo (1-opération-sur-les-merges)
$
