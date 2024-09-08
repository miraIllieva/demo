# demo
add new text
add new text nomer 2

How to use GitHub: 

Lenovo@DESKTOP-6MM6LE6 MINGW64 ~/OneDrive/Desktop/GitHub-DEMO/demo (main)
$ git branch
* main

Lenovo@DESKTOP-6MM6LE6 MINGW64 ~/OneDrive/Desktop/GitHub-DEMO/demo (main)
$ git checkout -b"my-first-branch"
M       README.md
Switched to a new branch 'my-first-branch'

Lenovo@DESKTOP-6MM6LE6 MINGW64 ~/OneDrive/Desktop/GitHub-DEMO/demo (my-first-branch)
$ git add .

Lenovo@DESKTOP-6MM6LE6 MINGW64 ~/OneDrive/Desktop/GitHub-DEMO/demo (my-first-branch)
$ git comit -m
git: 'comit' is not a git command. See 'git --help'.

The most similar command is
        commit

Lenovo@DESKTOP-6MM6LE6 MINGW64 ~/OneDrive/Desktop/GitHub-DEMO/demo (my-first-branch)       
$ git commit -m"add new row"
[my-first-branch 70fbd1c] add new row
 1 file changed, 2 insertions(+), 1 deletion(-)

Lenovo@DESKTOP-6MM6LE6 MINGW64 ~/OneDrive/Desktop/GitHub-DEMO/demo (my-first-branch)       
$ git add . 

Lenovo@DESKTOP-6MM6LE6 MINGW64 ~/OneDrive/Desktop/GitHub-DEMO/demo (my-first-branch)       
$ git commit -m"new row added for second time"
[my-first-branch 56f4c08] new row added for second time
 1 file changed, 3 insertions(+), 1 deletion(-)

Lenovo@DESKTOP-6MM6LE6 MINGW64 ~/OneDrive/Desktop/GitHub-DEMO/demo (my-first-branch)       
$ git push 
fatal: The current branch my-first-branch has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin my-first-branch

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.
ss


new one