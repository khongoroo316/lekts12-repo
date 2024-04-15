khongoroo

Admin@DESKTOP-BP9VF06 MINGW64 ~
$ git clone https://github.com/khongoroo316/lekts12-repo.git
Cloning into 'lekts12-repo'...
warning: You appear to have cloned an empty repository.

Admin@DESKTOP-BP9VF06 MINGW64 ~
$ ls
'3D Objects'/
 AppData/
'Application Data'@
'Cisco Packet Tracer 8.2.1'/
 Contacts/
 Cookies@
 Desktop/
 Documents/
 Downloads/
 Favorites/
 IntelGraphicsProfiles/
 Links/
'Local Settings'@
 Music/
'My Documents'@
 NTUSER.DAT
 NTUSER.DAT{95f0a7ae-2c6c-11ed-94e9-7412b3e07656}.TM.blf
 NTUSER.DAT{95f0a7ae-2c6c-11ed-94e9-7412b3e07656}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{95f0a7ae-2c6c-11ed-94e9-7412b3e07656}.TMContainer00000000000000000002.regtrans-ms
 NetHood@
 Pictures/
 PrintHood@
 Recent@
'Saved Games'/
 Searches/
 SendTo@
'Start Menu'@
 Templates@
 Videos/
 eclipse/
 eclipse-workspace/
 lekts12-repo/
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 ntuser.ini
 source/

Admin@DESKTOP-BP9VF06 MINGW64 ~
$ cd lekts12-repo

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ vi index.html

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ git commit -m "add index.html"
On branch main

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html

nothing added to commit but untracked files present (use "git add" to track)

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ git add index.html
warning: in the working copy of 'index.html', LF will be replaced by CRLF the next time Git touches it

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ git commit -m "add index"
[main (root-commit) 6c9cc8c] add index
 1 file changed, 1 insertion(+)
 create mode 100644 index.html

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ ls
index.html

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ vi README.txt

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ git add README.txt
warning: in the working copy of 'README.txt', LF will be replaced by CRLF the next time Git touches it

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ git commit -m "add readme"
[main 538f2d8] add readme
 1 file changed, 1 insertion(+)
 create mode 100644 README.txt

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ ls
README.txt  index.html

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ git checkout -b tix-5
Switched to a new branch 'tix-5'

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (tix-5)
$ code .

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (tix-5)
$ git status
On branch tix-5
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (tix-5)
$ git add -A
warning: in the working copy of 'index.html', LF will be replaced by CRLF the next time Git touches it

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (tix-5)
$ git commit -m "#5 updated the text"
[main 281309f] #5 updated the text
 1 file changed, 12 insertions(+), 1 deletion(-)

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ git push -u origin tix-5
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (6/6), 468 bytes | 468.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/khongoroo316/lekts12-repo.git
 * [new branch]      tix-5 -> tix-5
branch 'tix-5' set up to track 'origin/tix-5'.

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ git checkout -b main
fatal: a branch named 'main' already exists

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ code .

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ git add -A
warning: in the working copy of 'index.html', LF will be replaced by CRLF the next time Git touches it

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ git commit -m "mian"
[main 9206424] mian
 1 file changed, 1 insertion(+)

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$  git push -u origin main
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 12 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 755 bytes | 755.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
remote:
remote: Create a pull request for 'main' on GitHub by visiting:
remote:      https://github.com/khongoroo316/lekts12-repo/pull/new/main
remote:
To https://github.com/khongoroo316/lekts12-repo.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ git pull origin main
From https://github.com/khongoroo316/lekts12-repo
 * branch            main       -> FETCH_HEAD
Already up to date.

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ git checkout main
Already on 'main'
Your branch is up to date with 'origin/main'.

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ git pull
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (1/1), 885 bytes | 29.00 KiB/s, done.
From https://github.com/khongoroo316/lekts12-repo
   538f2d8..0610494  tix-5      -> origin/tix-5
Already up to date.

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ git branch -0 tix-5
error: unknown switch `0'
usage: git branch [<options>] [-r | -a] [--merged] [--no-merged]
   or: git branch [<options>] [-f] [--recurse-submodules] <branch-name> [<start-point>]
   or: git branch [<options>] [-l] [<pattern>...]
   or: git branch [<options>] [-r] (-d | -D) <branch-name>...
   or: git branch [<options>] (-m | -M) [<old-branch>] <new-branch>
   or: git branch [<options>] (-c | -C) [<old-branch>] <new-branch>
   or: git branch [<options>] [-r | -a] [--points-at]
   or: git branch [<options>] [-r | -a] [--format]

Generic options
    -v, --verbose         show hash and subject, give twice for upstream branch
    -q, --quiet           suppress informational messages
    -t, --track[=(direct|inherit)]
                          set branch tracking configuration
    -u, --set-upstream-to <upstream>
                          change the upstream info
    --unset-upstream      unset the upstream info
    --color[=<when>]      use colored output
    -r, --remotes         act on remote-tracking branches
    --contains <commit>   print only branches that contain the commit
    --no-contains <commit>
                          print only branches that don't contain the commit
    --abbrev[=<n>]        use <n> digits to display object names

Specific git-branch actions:
    -a, --all             list both remote-tracking and local branches
    -d, --delete          delete fully merged branch
    -D                    delete branch (even if not merged)
    -m, --move            move/rename a branch and its reflog
    -M                    move/rename a branch, even if target exists
    -c, --copy            copy a branch and its reflog
    -C                    copy a branch, even if target exists
    -l, --list            list branch names
    --show-current        show current branch name
    --create-reflog       create the branch's reflog
    --edit-description    edit the description for the branch
    -f, --force           force creation, move/rename, deletion
    --merged <commit>     print only branches that are merged
    --no-merged <commit>  print only branches that are not merged
    --column[=<style>]    list branches in columns
    --sort <key>          field name to sort on
    --points-at <object>  print only branches of the object
    -i, --ignore-case     sorting and filtering are case insensitive
    --recurse-submodules  recurse through submodules
    --format <format>     format to use for the output


Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ git branch -D tix-5
Deleted branch tix-5 (was 538f2d8).

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ code .

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ git add -A
warning: in the working copy of 'index.html', LF will be replaced by CRLF the next time Git touches it

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ git checkout
M       index.html
Your branch is up to date with 'origin/main'.

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ git checkout tix-10
error: pathspec 'tix-10' did not match any file(s) known to git

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ ^C
bash: :s^C: substitution failed

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ ^C

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   index.html


Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ git checkout tix-10
error: pathspec 'tix-10' did not match any file(s) known to git

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ git checkout tix-10
error: pathspec 'tix-10' did not match any file(s) known to git

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ git pull
From https://github.com/khongoroo316/lekts12-repo
 * [new branch]      tix-10     -> origin/tix-10
Already up to date.

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ git checkout tix-10
Switched to a new branch 'tix-10'
M       index.html
branch 'tix-10' set up to track 'origin/tix-10'.

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (tix-10)
$ code .

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (tix-10)
$ git add -A
warning: in the working copy of 'index.html', LF will be replaced by CRLF the next time Git touches it

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (tix-10)
$ git commit -m "#10 fixed"
[tix-10 d5bf41b] #10 fixed
 1 file changed, 3 insertions(+), 3 deletions(-)

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (tix-10)
$ git push -u origin tix-10
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 368 bytes | 368.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/khongoroo316/lekts12-repo.git
   0610494..d5bf41b  tix-10 -> tix-10
branch 'tix-10' set up to track 'origin/tix-10'.

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (tix-10)
$ git pull origin main
From https://github.com/khongoroo316/lekts12-repo
 * branch            main       -> FETCH_HEAD
Already up to date.

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (tix-10)
$ git add -A
warning: in the working copy of 'index.html', LF will be replaced by CRLF the next time Git touches it

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (tix-10)
$ git commit -m "merge conflict ressolved"
[tix-10 3847374] merge conflict ressolved
 1 file changed, 1 deletion(-)

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (tix-10)
$ git commit -m "merge conflict resolved"
On branch tix-10
Your branch is ahead of 'origin/tix-10' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (tix-10)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 331 bytes | 331.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/khongoroo316/lekts12-repo.git
   d5bf41b..3847374  tix-10 -> tix-10

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (tix-10)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
$ git pull
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (1/1), 898 bytes | 47.00 KiB/s, done.
From https://github.com/khongoroo316/lekts12-repo
   0610494..661d617  tix-5      -> origin/tix-5
Already up to date.

Admin@DESKTOP-BP9VF06 MINGW64 ~/lekts12-repo (main)
