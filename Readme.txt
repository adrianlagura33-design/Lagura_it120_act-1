
lenovo@DESKTOP-RFKMUIL MINGW64 ~ (master)
$ cd desktop

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop (master)
$ mkdir Lagura_it120_act-1

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop (master)
$ cd Lagura_it120_act-1

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ touch Profile.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ touch Education.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ touch Background.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ touch Readme.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ touch Test.py

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ ls
Background.txt  Education.txt  Profile.txt  Readme.txt  Test.py

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ notepad Profile.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ notepad Education.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ notepad Background.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ notepad Test.py

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ git init
Initialized empty Git repository in C:/Users/lenovo/Desktop/Lagura_it120_act-1/.
git/

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ git add .

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   Background.txt
        new file:   Education.txt
        new file:   Profile.txt
        new file:   Readme.txt
        new file:   Test.py


lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ adrianlagura33-design
bash: adrianlagura33-design: command not found

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ git config --global user.email "adrianlagura33@gmail.com"

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ git config --global username "adrianlagura33-design"
error: key does not contain a section: username

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ git config --global user.name "adrianlagura33-design"

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ git commit -m "Added Files Profile.txt Education.txt Background.txt Readme.txt Test.py"
[master (root-commit) a30ff5c] Added Files Profile.txt Education.txt Background.
txt Readme.txt Test.py
 5 files changed, 21 insertions(+)
 create mode 100644 Background.txt
 create mode 100644 Education.txt
 create mode 100644 Profile.txt
 create mode 100644 Readme.txt
 create mode 100644 Test.py

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ git status
On branch master
nothing to commit, working tree clean

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ git checkout -b Lagura_B
Switched to a new branch 'Lagura_B'

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B)
$ ls
Background.txt  Education.txt  Profile.txt  Readme.txt  Test.py

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B)
$ notepad Profile.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B)
$ git checkout -b Lagura_B1
Switched to a new branch 'Lagura_B1'

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B1)
$ git checkout -b Lagura_B2
Switched to a new branch 'Lagura_B2'

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B2)
$ git checkout -b Lagura_B3
Switched to a new branch 'Lagura_B3'

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B3)
$ ls
Background.txt  Education.txt  Profile.txt  Readme.txt  Test.py

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B3)
$ git checkout -b Lagura_B
fatal: a branch named 'Lagura_B' already exists

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B3)
$ notepad Profile.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B3)
$ git add Profile.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B3)
$ git commit -m "Added  Profile.txt in Lagura_B Branch "
On branch Lagura_B3
nothing to commit, working tree clean

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B3)
$ ls
Background.txt  Education.txt  Profile.txt  Readme.txt  Test.py

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B3)
$ notepad test.py

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B3)
$ notepad Education.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B3)
$ notepad Profile.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B3)
$ git checkout Lagura_B1
M       Education.txt
M       Profile.txt
Switched to branch 'Lagura_B1'

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B1)
$ git add Background.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B1)
$ git commit -m "Added Bacckground.txt in Lagura_B1 Branch"
On branch Lagura_B1
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Education.txt
        modified:   Profile.txt

no changes added to commit (use "git add" and/or "git commit -a")

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B1)
$ notepad Background.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B1)
$ notepad Education.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B1)
$ git checkout Lagura_B
M       Background.txt
M       Education.txt
M       Profile.txt
Switched to branch 'Lagura_B'

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B)
$ notepad Education.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B)
$ notepad Profile.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B)
$ git checkout mmaster
error: pathspec 'mmaster' did not match any file(s) known to git

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B)
$ git checkout master
M       Background.txt
M       Education.txt
M       Profile.txt
Switched to branch 'master'

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ git checkout Lagura_B2
M       Background.txt
M       Education.txt
M       Profile.txt
Switched to branch 'Lagura_B2'

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B2)
$ ls
Background.txt  Education.txt  Profile.txt  Readme.txt  Test.py

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B2)
$ git rm Test.py
rm 'Test.py'

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B2)
$ git checkout Lagura_B3
M       Background.txt
M       Education.txt
M       Profile.txt
D       Test.py
Switched to branch 'Lagura_B3'

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B3)
$ git checkout Lagura_B2
M       Background.txt
M       Education.txt
M       Profile.txt
D       Test.py
Switched to branch 'Lagura_B2'

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B2)
$ git commit -m "remove Test.py in Lagura_B2 Branch"
[Lagura_B2 d950652] remove Test.py in Lagura_B2 Branch
 1 file changed, 2 deletions(-)
 delete mode 100644 Test.py

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B2)
$ ls
Background.txt  Education.txt  Profile.txt  Readme.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B2)
$ git checkout Lagura_B3
M       Background.txt
M       Education.txt
M       Profile.txt
Switched to branch 'Lagura_B3'

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B3)
$ ls
Background.txt  Education.txt  Profile.txt  Readme.txt  Test.py

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B3)
$ git rm Test.py
rm 'Test.py'

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B3)
$ git commit -m "remove Test.py in Lagura_B3 Branch"
[Lagura_B3 9902c19] remove Test.py in Lagura_B3 Branch
 1 file changed, 2 deletions(-)
 delete mode 100644 Test.py

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B3)
$ ls
Background.txt  Education.txt  Profile.txt  Readme.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B3)
$ notepad Education.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B3)
$ git checkout master
M       Background.txt
M       Education.txt
M       Profile.txt
Switched to branch 'master'

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ notepad profile.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ notepad Education.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ notepad Background.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ notepad Test.py

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ git checkout Lagura_B2
M       Background.txt
M       Education.txt
M       Profile.txt
Switched to branch 'Lagura_B2'

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B2)
$ notepad Readme.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B2)
$ git add Readme.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B2)
$ git commit -m "Add all command in Readme.txt in Lagura_B2 Branch"
[Lagura_B2 7fba1fd] Add all command in Readme.txt in Lagura_B2 Branch
 1 file changed, 1 insertion(+)

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B2)
$ notepad Readme.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B2)
$ git checkout master
error: Your local changes to the following files would be overwritten by checkou
t:
        Readme.txt
Please commit your changes or stash them before you switch branches.
Aborting

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B2)
$ git add Readme.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B2)
$ git checkout master
error: Your local changes to the following files would be overwritten by checkou
t:
        Readme.txt
Please commit your changes or stash them before you switch branches.
Aborting

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B2)
$ git commit -m "Update Readme.txt"
[Lagura_B2 96ebe75] Update Readme.txt
 1 file changed, 304 insertions(+), 1 deletion(-)

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B2)
$ git checkout master
M       Background.txt
M       Education.txt
M       Profile.txt
Switched to branch 'master'

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ https://github.com/adrianlagura33-design/Lagura_it120_act-1.git
bash: https://github.com/adrianlagura33-design/Lagura_it120_act-1.git: No such file or directory

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ git remote add origin https://github.com/adrianlagura33-design/Lagura_it120_act-1.git

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ git push -u origin master
info: please complete authentication in your browser...
remote: Repository not found.
fatal: repository 'https://github.com/adrianlagura33-design/Lagura_it120_act-1.g
it/' not found

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ git push -u origin master
info: please complete authentication in your browser...
remote: Repository not found.
fatal: repository 'https://github.com/adrianlagura33-design/Lagura_it120_act-1.g
it/' not found

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ git push -u origin Lagura_B
info: please complete authentication in your browser...
remote: Repository not found.
fatal: repository 'https://github.com/adrianlagura33-design/Lagura_it120_act-1.g
it/' not found

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ git push -u origin master
remote: Repository not found.
fatal: repository 'https://github.com/adrianlagura33-design/Lagura_it120_act-1.g
it/' not found

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ git push -u Lagura_B
fatal: 'Lagura_B' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ git push -u Lagura_B2
fatal: 'Lagura_B2' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ git push -u Lagura_B1
fatal: 'Lagura_B1' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ git push -u Lagura_B master
fatal: 'Lagura_B' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ git remote add Lagura_it120_act-1 https://github.com/adrianlagura33-design/Lagura_it120_act-1.git

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ git remote add origin https://github.com/adrianlagura33-design/Lagura_it120_act-1.git
error: remote origin already exists.

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ git push -u origin master
info: please complete authentication in your browser...
remote: Repository not found.
fatal: repository 'https://github.com/adrianlagura33-design/Lagura_it120_act-1.g
it/' not found

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ git push -u origin Lagura_B1
remote: Repository not found.
fatal: repository 'https://github.com/adrianlagura33-design/Lagura_it120_act-1.g
it/' not found

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ git config user.name
adrianlagura33-design

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ git config user.email
adrianlagura33@gmail.com

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ git remote add Lagura_it120_act-1 https://github.com/adrianlagura33-design/Lagura_it120_act-1.git
error: remote Lagura_it120_act-1 already exists.

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ git push -u origin Lagura_B2
Enumerating objects: 15, done.
Counting objects: 100% (15/15), done.
Delta compression using up to 4 threads
Compressing objects: 100% (12/12), done.
Writing objects: 100% (15/15), 2.68 KiB | 196.00 KiB/s, done.
Total 15 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), done.
To https://github.com/adrianlagura33-design/Lagura_it120_act-1.git
 * [new branch]      Lagura_B2 -> Lagura_B2
branch 'Lagura_B2' set up to track 'origin/Lagura_B2'.

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (master)
$ git checkout Lagura_B3
M       Background.txt
M       Education.txt
M       Profile.txt
Switched to branch 'Lagura_B3'

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B3)
$ git push -u origin Lagura_B3
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 243 bytes | 243.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'Lagura_B3' on GitHub by visiting:
remote:      https://github.com/adrianlagura33-design/Lagura_it120_act-1/pull/ne
w/Lagura_B3
remote:
To https://github.com/adrianlagura33-design/Lagura_it120_act-1.git
 * [new branch]      Lagura_B3 -> Lagura_B3
branch 'Lagura_B3' set up to track 'origin/Lagura_B3'.

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B3)
$ git checkout Lagura_B
M       Background.txt
M       Education.txt
M       Profile.txt
Switched to branch 'Lagura_B'

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B)
$ git push -u origin Lagura_B
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'Lagura_B' on GitHub by visiting:
remote:      https://github.com/adrianlagura33-design/Lagura_it120_act-1/pull/ne
w/Lagura_B
remote:
To https://github.com/adrianlagura33-design/Lagura_it120_act-1.git
 * [new branch]      Lagura_B -> Lagura_B
branch 'Lagura_B' set up to track 'origin/Lagura_B'.

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B)
$ git checkout Lagura_B1
M       Background.txt
M       Education.txt
M       Profile.txt
Switched to branch 'Lagura_B1'

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B1)
$ git push -u Lagura_B1
fatal: 'Lagura_B1' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B1)
$ git push -u origin Lagura_B1
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'Lagura_B1' on GitHub by visiting:
remote:      https://github.com/adrianlagura33-design/Lagura_it120_act-1/pull/ne
w/Lagura_B1
remote:
To https://github.com/adrianlagura33-design/Lagura_it120_act-1.git
 * [new branch]      Lagura_B1 -> Lagura_B1
branch 'Lagura_B1' set up to track 'origin/Lagura_B1'.

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B1)
$ git status
On branch Lagura_B1
Your branch is up to date with 'origin/Lagura_B1'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Background.txt
        modified:   Education.txt
        modified:   Profile.txt

no changes added to commit (use "git add" and/or "git commit -a")

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B1)
$ git checkout Lagura_B2
M       Background.txt
M       Education.txt
M       Profile.txt
Switched to branch 'Lagura_B2'
Your branch is up to date with 'origin/Lagura_B2'.

lenovo@DESKTOP-RFKMUIL MINGW64 ~ (master)
$ cd desktop

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop (master)
$ cd Lagura_it120_act-1

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B3)
$ git checkout Lagura_B
M       Background.txt
M       Education.txt
M       Profile.txt
Switched to branch 'Lagura_B'
Your branch is up to date with 'origin/Lagura_B'.

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B)
$ notepad Profile.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B)
$ git add commit "update Readme.txt"
fatal: pathspec 'commit' did not match any files

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B)
$ git add commit -m "update Readme.txt"
error: unknown switch `m'
usage: git add [<options>] [--] <pathspec>...

    -n, --[no-]dry-run    dry run
    -v, --[no-]verbose    be verbose

    -i, --[no-]interactive
                          interactive picking
    -p, --[no-]patch      select hunks interactively
    -U, --unified <n>     generate diffs with <n> lines context
    --inter-hunk-context <n>
                          show context between diff hunks up to the specified nu
mber of lines
    -e, --[no-]edit       edit current diff and apply
    -f, --[no-]force      allow adding otherwise ignored files
    -u, --[no-]update     update tracked files
    --[no-]renormalize    renormalize EOL of tracked files (implies -u)
    -N, --[no-]intent-to-add
                          record only the fact that the path will be added later
    -A, --[no-]all        add changes from all tracked and untracked files
    --[no-]ignore-removal ignore paths removed in the working tree (same as --no
-all)
    --[no-]refresh        don't add, only refresh the index
    --[no-]ignore-errors  just skip files which cannot be added because of error
s
    --[no-]ignore-missing check if - even missing - files are ignored in dry run
    --[no-]sparse         allow updating entries outside of the sparse-checkout
cone
    --[no-]chmod (+|-)x   override the executable bit of the listed files
    --[no-]pathspec-from-file <file>
                          read pathspec from file
    --[no-]pathspec-file-nul
                          with --pathspec-from-file, pathspec elements are separ
ated with NUL character


lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B)
$ history
    1  mkdir Activity1
    2  cd Activity1
    3  git init
    4  touch profile.txt education.txt background.txt test.py readme.txt
    5  git add .
    6  git commit -m
    7  git -m "Initial commit with5 files"
    8  notepad profile.txt
    9  mrdir Activity1
   10  mkdir Activity1
   11  mkdir Activity-1
   12  cd Activity-1
   13  git init
   14  touch profile.txt education.txt background.txt test.py readme.txt
   15  git add .
   16  git commit -m "Initial commit with 5 files"
   17  notepad profile.txt
   18  mkdir Activity--1
   19  cd Activity--1
   20  git init
   21  touch profile.txt education.txt background.txt test.py readme.txt
   22  git add .
   23  git commit -m "Initial commit with 5 files"
   24  git config --global user.name "adrianlagura33-design"
   25  git config --global user.email "adrianlagura33@gmail.com
   26  notepad profile.txt
   27  git
   28  mkdir lagura_act1
   29  git init
   30  touch profile.text
   31  clear
   32  mkdir lagura_it120_act1
   33  git init
   34  touch profile.txt
   35  touch education.txt
   36  touch background.txt
   37  touch readme.txt
   38  touch test.py
   39  git add .
   40  mkdir lagura__it120_act1
   41  git init
   42  touch profile.txt
   43  touch education.txt
   44  touch background.txt
   45  touch readme.txt
   46  touch test.py
   47  git add .
   48  notepad profile.txt
   49  touch education.txt
   50  clear touch education.txt
   51  mkdir lagura_IT120_act1
   52  mkdir lagura_it120__act1
   53  git init
   54  touch profile.txt
   55  touch education.txt
   56  touch background.txt
   57  touch readme.txt
   58  touch test.py
   59  git add .
   60  notepad profile.txt
   61  notepad education.txt
   62  notepad background.txt
   63  git add education.txt
   64  cd desktop
   65  mkdir lagura_it120~act1
   66  git init
   67  touch profile.txt
   68  touch education.txt
   69  touch background.txt
   70  touch readme.txt
   71  touch test.py
   72  git add .
   73  notepad profile.txt
   74  notepad education.txt
   75  notepad background.txt
   76  notepad test.py
   77  git add .
   78  git commit -m "Save files"
   79  git commit -m "Save files" [master (root-commit) 2873c9f] Save file
   80  cd desktop
   81  clear
   82  cd desktop
   83  clear
   84  cd desktop
   85  mkdir Lagura_It120_act1
   86  cd Lagura_It120_act1
   87  touch Profile.txt
   88  touch Education.txt
   89  touch Background.txt
   90  touch Readme.txt
   91  touch test.py
   92  ls
   93  notepad Profile.txt
   94  notepad Education.txt
   95  notepad Background.txt
   96  notepad Test.py
   97  git init
   98  git add .
   99  git status
  100  git commit -m "Added Files Profile.txt Education.txt Background.txt Readme.txtTest.py"
  101  git commit -m
  102  $ git commit -m "Added Files Profile.txt Education.txt Background.txt Readme.txt Test.py"
  103  [master (root-commit) 50d7e1b] Added Files Profile.txt Education.txt Background.txt Readme.txt Test.py
  104  git commit -m "Added Files Profile.txt Education.txt Background.txt Readme.txt Test.py"
  105  [master (root-commit) 50d7e1b] Added Files Profile.txt Education.txt Background.txt Readme.txt Test.py
  106  git commit -m "Added Files Profile.txt Education.txt Background.txt Readme.txt Test.py"
  107  [master (root-commit) 50d7e1b] Added Files Profile.txt Education.txt Background.txt Readme.txt Test.py
  108   5 files changed, 16 insertions(+)
  109   create mode 100644 Background.txt
  110   create mode 100644 Education.txt
  111   create mode 100644 Profile.txt
  112   create mode 100644 Readme.txt
  113   create mode 100644 Test.py
  114  git commit -m "Added Files Profile.txt Education.txt Background.txt Readme.txt Test.py"
  115  clear
  116  cd Lagura_It120_act1
  117  clear
  118  cd desktop
  119  Lagura_it120_act-1
  120  clear
  121  cd desktop
  122  mkdir Lagura_it120_act-1
  123  cd Lagura_it120_act-1
  124  touch Profile.txt
  125  touch Education.txt
  126  touch Background.txt
  127  touch Readme.txt
  128  touch Test.py
  129  ls
  130  notepad Profile.txt
  131  notepad Education.txt
  132  notepad Background.txt
  133  notepad Test.py
  134  git init
  135  git add .
  136  git status
  137  adrianlagura33-design
  138  git config --global user.email "adrianlagura33@gmail.com"
  139  git config --global username "adrianlagura33-design"
  140  git config --global user.name "adrianlagura33-design"
  141  git commit -m "Added Files Profile.txt Education.txt Background.txt Readme.txt Test.py"
  142  git status
  143  git checkout -b Lagura_B
  144  ls
  145  notepad Profile.txt
  146  git checkout -b Lagura_B1
  147  git checkout -b Lagura_B2
  148  git checkout -b Lagura_B3
  149  ls
  150  git checkout -b Lagura_B
  151  notepad Profile.txt
  152  git add Profile.txt
  153  git commit -m "Added  Profile.txt in Lagura_B Branch "
  154  ls
  155  notepad test.py
  156  notepad Education.txt
  157  notepad Profile.txt
  158  git checkout Lagura_B1
  159  git add Background.txt
  160  git commit -m "Added Bacckground.txt in Lagura_B1 Branch"
  161  notepad Background.txt
  162  notepad Education.txt
  163  git checkout Lagura_B
  164  notepad Education.txt
  165  notepad Profile.txt
  166  git checkout mmaster
  167  git checkout master
  168  git checkout Lagura_B2
  169  ls
  170  git rm Test.py
  171  git checkout Lagura_B3
  172  git checkout Lagura_B2
  173  git commit -m "remove Test.py in Lagura_B2 Branch"
  174  ls
  175  git checkout Lagura_B3
  176  ls
  177  git rm Test.py
  178  git commit -m "remove Test.py in Lagura_B3 Branch"
  179  ls
  180  notepad Education.txt
  181  git checkout master
  182  notepad profile.txt
  183  notepad Education.txt
  184  notepad Background.txt
  185  notepad Test.py
  186  git checkout Lagura_B2
  187  notepad Readme.txt
  188  git add Readme.txt
  189  git commit -m "Add all command in Readme.txt in Lagura_B2 Branch"
  190  notepad Readme.txt
  191  git checkout master
  192  git add Readme.txt
  193  git checkout master
  194  git commit -m "Update Readme.txt"
  195  git checkout master
  196  https://github.com/adrianlagura33-design/Lagura_it120_act-1.git
  197  git remote add origin https://github.com/adrianlagura33-design/Lagura_it120_act-1.git
  198  git push -u origin master
  199  git push -u origin master
  200  git push -u origin Lagura_B
  201  git push -u origin master
  202  git push -u Lagura_B
  203  git push -u Lagura_B2
  204  git push -u Lagura_B1
  205  git push -u Lagura_B master
  206  git remote add Lagura_it120_act-1 https://github.com/adrianlagura33-design/Lagura_it120_act-1.git
  207  git remote add origin https://github.com/adrianlagura33-design/Lagura_it120_act-1.git
  208  git push -u origin master
  209  git push -u origin Lagura_B1
  210  git config user.name
  211  git config user.email
  212  git remote add Lagura_it120_act-1 https://github.com/adrianlagura33-design/Lagura_it120_act-1.git
  213  git push -u origin Lagura_B2
  214  git checkout Lagura_B3
  215  git push -u origin Lagura_B3
  216  git checkout Lagura_B
  217  git push -u origin Lagura_B
  218  git checkout Lagura_B1
  219  git push -u Lagura_B1
  220  git push -u origin Lagura_B1
  221  git status
  222  git checkout Lagura_B2
  223  notepad Readme.txt
  224  git add Readme.txt
  225  git commit -m "Update Readme.txt"
  226  git checkout master
  227  git notepad Readme.txt
  228  notepad Readme.txt
  229  git add Readme.txt
  230  git checkout Lagura_B
  231  notepad Readme.txt
  232  git add Readme.txt
  233  git commit -m "Update Readme.txt"
  234  notepad Readme.txt
  235  notepad Profile.txt
  236  git checkout master
  237  git add Readme.txt
  238  git commit -m "Update Readme.txt"
  239  git cheackout master
  240  git status
  241  git push -u origin master
  242  git checkout Lagura_B
  243  git push -u origin Lagura_B
  244  git checkout Lagura_B1
  245  git push -u origin Lagura_B1
  246  git push -u origin Lagura_B2
  247  git push -u origin Lagura_B3
  248  notepad Readme.txt
  249  cd Lagura_it120_act-1
  250  cd Lagura_B
  251  cd desktop
  252  cd Lagura_it120_act-1
  253  git notepad Lagura_B
  254  git commit -m Lagura_B
  255  notepad Profile.txt
  256  history
  257  git push -u origin Lagura_B1
  258  notepad Education.txt
  259  git push -u origin Lagura_B2
  260  history
  261  notepad Background.txt
  262  history
  263  git cheackout master
  264  cd Lagura_it120_act-1
  265  desktop
  266  clear
  267  cd desktop
  268  cd Lagura_it120_act-1
  269  Profile.txt
  270  history
  271  touch Profile.txt
  272  notepad Profile.txt
  273  git cheackout master
  274  git add
  275  git add .
  276  notepad
  277  notepad Profile.txt
  278  clear
  279  cd desktop
  280  cd Lagura_it120_act-1
  281  git checkout Lagura_B
  282  notepad Profile.txt
  283  git add commit "update Readme.txt"
  284  git add commit -m "update Readme.txt"
  285  history

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B)
$ git add Readme.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B)
$ git commit -m "update Readme.txt"
On branch Lagura_B
Your branch is up to date with 'origin/Lagura_B'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Background.txt
        modified:   Education.txt
        modified:   Profile.txt

no changes added to commit (use "git add" and/or "git commit -a")

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B)
$ git checkout Lagura_B1
M       Background.txt
M       Education.txt
M       Profile.txt
Switched to branch 'Lagura_B1'
Your branch is up to date with 'origin/Lagura_B1'.

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B1)
$ notepad education.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B1)
$ git add Readme.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B1)
$ git commit -m "update Readme.txt"
On branch Lagura_B1
Your branch is up to date with 'origin/Lagura_B1'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Background.txt
        modified:   Education.txt
        modified:   Profile.txt

no changes added to commit (use "git add" and/or "git commit -a")

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B1)
$ history
    1  mkdir Activity1
    2  cd Activity1
    3  git init
    4  touch profile.txt education.txt background.txt test.py readme.txt
    5  git add .
    6  git commit -m
    7  git -m "Initial commit with5 files"
    8  notepad profile.txt
    9  mrdir Activity1
   10  mkdir Activity1
   11  mkdir Activity-1
   12  cd Activity-1
   13  git init
   14  touch profile.txt education.txt background.txt test.py readme.txt
   15  git add .
   16  git commit -m "Initial commit with 5 files"
   17  notepad profile.txt
   18  mkdir Activity--1
   19  cd Activity--1
   20  git init
   21  touch profile.txt education.txt background.txt test.py readme.txt
   22  git add .
   23  git commit -m "Initial commit with 5 files"
   24  git config --global user.name "adrianlagura33-design"
   25  git config --global user.email "adrianlagura33@gmail.com
   26  notepad profile.txt
   27  git
   28  mkdir lagura_act1
   29  git init
   30  touch profile.text
   31  clear
   32  mkdir lagura_it120_act1
   33  git init
   34  touch profile.txt
   35  touch education.txt
   36  touch background.txt
   37  touch readme.txt
   38  touch test.py
   39  git add .
   40  mkdir lagura__it120_act1
   41  git init
   42  touch profile.txt
   43  touch education.txt
   44  touch background.txt
   45  touch readme.txt
   46  touch test.py
   47  git add .
   48  notepad profile.txt
   49  touch education.txt
   50  clear touch education.txt
   51  mkdir lagura_IT120_act1
   52  mkdir lagura_it120__act1
   53  git init
   54  touch profile.txt
   55  touch education.txt
   56  touch background.txt
   57  touch readme.txt
   58  touch test.py
   59  git add .
   60  notepad profile.txt
   61  notepad education.txt
   62  notepad background.txt
   63  git add education.txt
   64  cd desktop
   65  mkdir lagura_it120~act1
   66  git init
   67  touch profile.txt
   68  touch education.txt
   69  touch background.txt
   70  touch readme.txt
   71  touch test.py
   72  git add .
   73  notepad profile.txt
   74  notepad education.txt
   75  notepad background.txt
   76  notepad test.py
   77  git add .
   78  git commit -m "Save files"
   79  git commit -m "Save files" [master (root-commit) 2873c9f] Save file
   80  cd desktop
   81  clear
   82  cd desktop
   83  clear
   84  cd desktop
   85  mkdir Lagura_It120_act1
   86  cd Lagura_It120_act1
   87  touch Profile.txt
   88  touch Education.txt
   89  touch Background.txt
   90  touch Readme.txt
   91  touch test.py
   92  ls
   93  notepad Profile.txt
   94  notepad Education.txt
   95  notepad Background.txt
   96  notepad Test.py
   97  git init
   98  git add .
   99  git status
  100  git commit -m "Added Files Profile.txt Education.txt Background.txt Readme.txtTest.py"
  101  git commit -m
  102  $ git commit -m "Added Files Profile.txt Education.txt Background.txt Readme.txt Test.py"
  103  [master (root-commit) 50d7e1b] Added Files Profile.txt Education.txt Background.txt Readme.txt Test.py
  104  git commit -m "Added Files Profile.txt Education.txt Background.txt Readme.txt Test.py"
  105  [master (root-commit) 50d7e1b] Added Files Profile.txt Education.txt Background.txt Readme.txt Test.py
  106  git commit -m "Added Files Profile.txt Education.txt Background.txt Readme.txt Test.py"
  107  [master (root-commit) 50d7e1b] Added Files Profile.txt Education.txt Background.txt Readme.txt Test.py
  108   5 files changed, 16 insertions(+)
  109   create mode 100644 Background.txt
  110   create mode 100644 Education.txt
  111   create mode 100644 Profile.txt
  112   create mode 100644 Readme.txt
  113   create mode 100644 Test.py
  114  git commit -m "Added Files Profile.txt Education.txt Background.txt Readme.txt Test.py"
  115  clear
  116  cd Lagura_It120_act1
  117  clear
  118  cd desktop
  119  Lagura_it120_act-1
  120  clear
  121  cd desktop
  122  mkdir Lagura_it120_act-1
  123  cd Lagura_it120_act-1
  124  touch Profile.txt
  125  touch Education.txt
  126  touch Background.txt
  127  touch Readme.txt
  128  touch Test.py
  129  ls
  130  notepad Profile.txt
  131  notepad Education.txt
  132  notepad Background.txt
  133  notepad Test.py
  134  git init
  135  git add .
  136  git status
  137  adrianlagura33-design
  138  git config --global user.email "adrianlagura33@gmail.com"
  139  git config --global username "adrianlagura33-design"
  140  git config --global user.name "adrianlagura33-design"
  141  git commit -m "Added Files Profile.txt Education.txt Background.txt Readme.txt Test.py"
  142  git status
  143  git checkout -b Lagura_B
  144  ls
  145  notepad Profile.txt
  146  git checkout -b Lagura_B1
  147  git checkout -b Lagura_B2
  148  git checkout -b Lagura_B3
  149  ls
  150  git checkout -b Lagura_B
  151  notepad Profile.txt
  152  git add Profile.txt
  153  git commit -m "Added  Profile.txt in Lagura_B Branch "
  154  ls
  155  notepad test.py
  156  notepad Education.txt
  157  notepad Profile.txt
  158  git checkout Lagura_B1
  159  git add Background.txt
  160  git commit -m "Added Bacckground.txt in Lagura_B1 Branch"
  161  notepad Background.txt
  162  notepad Education.txt
  163  git checkout Lagura_B
  164  notepad Education.txt
  165  notepad Profile.txt
  166  git checkout mmaster
  167  git checkout master
  168  git checkout Lagura_B2
  169  ls
  170  git rm Test.py
  171  git checkout Lagura_B3
  172  git checkout Lagura_B2
  173  git commit -m "remove Test.py in Lagura_B2 Branch"
  174  ls
  175  git checkout Lagura_B3
  176  ls
  177  git rm Test.py
  178  git commit -m "remove Test.py in Lagura_B3 Branch"
  179  ls
  180  notepad Education.txt
  181  git checkout master
  182  notepad profile.txt
  183  notepad Education.txt
  184  notepad Background.txt
  185  notepad Test.py
  186  git checkout Lagura_B2
  187  notepad Readme.txt
  188  git add Readme.txt
  189  git commit -m "Add all command in Readme.txt in Lagura_B2 Branch"
  190  notepad Readme.txt
  191  git checkout master
  192  git add Readme.txt
  193  git checkout master
  194  git commit -m "Update Readme.txt"
  195  git checkout master
  196  https://github.com/adrianlagura33-design/Lagura_it120_act-1.git
  197  git remote add origin https://github.com/adrianlagura33-design/Lagura_it120_act-1.git
  198  git push -u origin master
  199  git push -u origin master
  200  git push -u origin Lagura_B
  201  git push -u origin master
  202  git push -u Lagura_B
  203  git push -u Lagura_B2
  204  git push -u Lagura_B1
  205  git push -u Lagura_B master
  206  git remote add Lagura_it120_act-1 https://github.com/adrianlagura33-design/Lagura_it120_act-1.git
  207  git remote add origin https://github.com/adrianlagura33-design/Lagura_it120_act-1.git
  208  git push -u origin master
  209  git push -u origin Lagura_B1
  210  git config user.name
  211  git config user.email
  212  git remote add Lagura_it120_act-1 https://github.com/adrianlagura33-design/Lagura_it120_act-1.git
  213  git push -u origin Lagura_B2
  214  git checkout Lagura_B3
  215  git push -u origin Lagura_B3
  216  git checkout Lagura_B
  217  git push -u origin Lagura_B
  218  git checkout Lagura_B1
  219  git push -u Lagura_B1
  220  git push -u origin Lagura_B1
  221  git status
  222  git checkout Lagura_B2
  223  notepad Readme.txt
  224  git add Readme.txt
  225  git commit -m "Update Readme.txt"
  226  git checkout master
  227  git notepad Readme.txt
  228  notepad Readme.txt
  229  git add Readme.txt
  230  git checkout Lagura_B
  231  notepad Readme.txt
  232  git add Readme.txt
  233  git commit -m "Update Readme.txt"
  234  notepad Readme.txt
  235  notepad Profile.txt
  236  git checkout master
  237  git add Readme.txt
  238  git commit -m "Update Readme.txt"
  239  git cheackout master
  240  git status
  241  git push -u origin master
  242  git checkout Lagura_B
  243  git push -u origin Lagura_B
  244  git checkout Lagura_B1
  245  git push -u origin Lagura_B1
  246  git push -u origin Lagura_B2
  247  git push -u origin Lagura_B3
  248  notepad Readme.txt
  249  cd Lagura_it120_act-1
  250  cd Lagura_B
  251  cd desktop
  252  cd Lagura_it120_act-1
  253  git notepad Lagura_B
  254  git commit -m Lagura_B
  255  notepad Profile.txt
  256  history
  257  git push -u origin Lagura_B1
  258  notepad Education.txt
  259  git push -u origin Lagura_B2
  260  history
  261  notepad Background.txt
  262  history
  263  git cheackout master
  264  cd Lagura_it120_act-1
  265  desktop
  266  clear
  267  cd desktop
  268  cd Lagura_it120_act-1
  269  Profile.txt
  270  history
  271  touch Profile.txt
  272  notepad Profile.txt
  273  git cheackout master
  274  git add
  275  git add .
  276  notepad
  277  notepad Profile.txt
  278  clear
  279  cd desktop
  280  cd Lagura_it120_act-1
  281  git checkout Lagura_B
  282  notepad Profile.txt
  283  git add commit "update Readme.txt"
  284  git add commit -m "update Readme.txt"
  285  history
  286  git add Readme.txt
  287  git commit -m "update Readme.txt"
  288  git checkout Lagura_B1
  289  notepad education.txt
  290  git add Readme.txt
  291  git commit -m "update Readme.txt"
  292  history

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B1)
$ git checkout Lagura_B2
M       Background.txt
M       Education.txt
M       Profile.txt
Switched to branch 'Lagura_B2'
Your branch is up to date with 'origin/Lagura_B2'.

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B2)
$ notepad Background.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B2)
$ git add Readme.txt

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B2)
$ git commit -m "Update Readme.txt"
On branch Lagura_B2
Your branch is up to date with 'origin/Lagura_B2'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Background.txt
        modified:   Education.txt
        modified:   Profile.txt

no changes added to commit (use "git add" and/or "git commit -a")

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B2)
$ git checkout Lagura_B3
M       Background.txt
M       Education.txt
M       Profile.txt
Switched to branch 'Lagura_B3'
Your branch is up to date with 'origin/Lagura_B3'.

lenovo@DESKTOP-RFKMUIL MINGW64 ~/desktop/Lagura_it120_act-1 (Lagura_B3)
$ notepad Readme.txt
