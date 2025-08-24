
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
