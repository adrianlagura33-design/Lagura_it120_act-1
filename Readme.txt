
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
