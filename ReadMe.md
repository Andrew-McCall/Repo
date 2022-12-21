# Repo 4

andre@TALUS MINGW64 /e/Documents/Scripts/QA
$ rm -rf Repo4/

andre@TALUS MINGW64 /e/Documents/Scripts/QA
$ ls
ExpressDemo/   QAExpressDemo/  ReactDemo2/     ReactQuizPlayer/
ExpressDemo2/  ReactDemo/      ReactExamples/

andre@TALUS MINGW64 /e/Documents/Scripts/QA
$ git clone https://github.com/Andrew-McCall/Repo4
Cloning into 'Repo4'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

andre@TALUS MINGW64 /e/Documents/Scripts/QA
$ ls
ExpressDemo/   QAExpressDemo/  ReactDemo2/     ReactQuizPlayer/
ExpressDemo2/  ReactDemo/      ReactExamples/  Repo4/

andre@TALUS MINGW64 /e/Documents/Scripts/QA
$ cd Re
bash: cd: Re: No such file or directory

andre@TALUS MINGW64 /e/Documents/Scripts/QA
$ cd Repo4/

andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (main)
$ nano ReadMe.md

andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ReadMe.md

no changes added to commit (use "git add" and/or "git commit -a")

andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (main)
$ git add ReadMe.md

andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (main)
$ git commit -m "Updated ReadMe"
[main e6f7b97] Updated ReadMe
 1 file changed, 4 insertions(+), 1 deletion(-)
g
andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 270 bytes | 270.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Andrew-McCall/Repo4
   bba5eaf..e6f7b97  main -> main

andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (main)
$ git branch David

andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (main)
$ git checkout David
Switched to branch 'David'

andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (David)
$ nano ReadMe.md

andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (David)
$ git add ReadMe.md

andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (David)
$ git commit -m "changed name to david"
[David 3857115] changed name to david
 1 file changed, 1 insertion(+), 1 deletion(-)
g
andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (David)
$ git puhs
git: 'puhs' is not a git command. See 'git --help'.

The most similar command is
        push

andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (David)
$ git push
fatal: The current branch David has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin David

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (David)
$ git push -u origin David
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 272 bytes | 272.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'David' on GitHub by visiting:
remote:      https://github.com/Andrew-McCall/Repo4/pull/new/David
remote:
To https://github.com/Andrew-McCall/Repo4
 * [new branch]      David -> David
branch 'David' set up to track 'origin/David'.

andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (David)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (main)
$ git branch Andrew

andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (main)
$ git checkout Andrew
Switched to branch 'Andrew'

andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (Andrew)
$ nano ReadMe.md

andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (Andrew)
$ git add ReadMe.md

andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (Andrew)
$ git commit -m "Full Name"
g[Andrew 02730df] Full Name
 1 file changed, 1 insertion(+), 1 deletion(-)
i
andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (Andrew)
$ git push
fatal: The current branch Andrew has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin Andrew

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (Andrew)
$ git push -u origin Andrew
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 273 bytes | 273.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'Andrew' on GitHub by visiting:
remote:      https://github.com/Andrew-McCall/Repo4/pull/new/Andrew
remote:
To https://github.com/Andrew-McCall/Repo4
 * [new branch]      Andrew -> Andrew
branch 'Andrew' set up to track 'origin/Andrew'.

andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (Andrew)
$ git branch Andrew-Two

andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (Andrew)
$ git checkout Andrew-Two
Switched to branch 'Andrew-Two'

andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (Andrew-Two)
$ nano ReadMe.md

andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (Andrew-Two)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (main)
$ git merge David
Updating e6f7b97..3857115
Fast-forward
 ReadMe.md | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)

andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (main)
$ git merge Andrew
Auto-merging ReadMe.md
CONFLICT (content): Merge conflict in ReadMe.md
Automatic merge failed; fix conflicts and then commit the result.

andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (main|MERGING)
$ nano ReadMe.md

andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (main|MERGING)
$ git add ReadMe.md

andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (main|MERGING)
$ git commit -m "Manually Resuloved Merge"
[main 5730657] Manually Resuloved Merge

andre@TALUS MINGW64 /e/Documents/Scripts/QA/Repo4 (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Writing objects: 100% (3/3), 313 bytes | 313.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Andrew-McCall/Repo4
   e6f7b97..5730657  main -> main
