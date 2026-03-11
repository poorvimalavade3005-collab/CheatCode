1. **Project in local and remote repository**



1.Create a Folder in desktop and create a text folder inside it.

2\. In Git Bash - cd desktop/FolderName.

                 git init

                 git remote add origin https://github.com/poorvimalavade3005-collab/DevopsLab.git

                 git add .

                 git commit -m "my new commit

                 \*\*git config --local user.name "poorvimalavade3005-collab"\*\*

&nbsp;                \\\*\\\*git config --local user.email "poorvimalavade3005@gmail.com"\\\*\\\*

                 git commit -m "my new commit

                 git push origin master

                 git config --local user.email "poorvimalavade3005@gmail.com"

                 git push origin master

                 git log

                 git status

     (Create another new text document in folder)

                 git status

                 git add .

                 git status

                 git clone https://github.com/poorvimalavade3005-collab/DevopsLab.git

                 git reset --hard

**(error regarding another account in GitHub - go to settings > credential manager> git > remove)**



**\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_**



**2. Fork, merge**



1.Create a folder in desktop and repo in GitHub

2\. In Gitbash

&nbsp;  cd desktop/Folder name

&nbsp;  git init

&nbsp;  git remote add origin https://github.com/poorvimalavade3005-collab/Rose.git

&nbsp;  $ git config --local user.name "poorvimalavade3005-collab"

&nbsp;  $ git config --local user.email "poorvimalavade3005@gmail.com"
   echo "Naman">new.txt

&nbsp;  git add .

&nbsp;  git commit -m "my new commit"

&nbsp;  git push origin master\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_>

&nbsp;  git checkout -b branch1

&nbsp;  echo "Jyoti">new2.txt

&nbsp;  git add .

&nbsp;  git commit -m "my new commit"

&nbsp;  git checkout master

&nbsp;  git merge branch1\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_(fast forward)

&nbsp;  echo "mahi">new.txt

&nbsp;  git add .

&nbsp;  git commit -m "my new commit"

&nbsp;  git checkout branch1

&nbsp;  echo "Heloo">new.txt

&nbsp;  git add .

&nbsp;  git commit -m "my new commit"

&nbsp;  git checkout master

&nbsp;  git merge branch1

&nbsp;  (**Here go and change entirely the new.txt file content and save)**

   git add .

&nbsp;  git commit -m "my new commit'

&nbsp;  git push origin master

&nbsp;  git push origin branch1

&nbsp;  git diff branch1\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_(merge conflict)

&nbsp;**Fork**,**Pull requests**

**\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_**



**3.Jenkins**



Configuration:

1.Create a new Repository in GitHub and create a file with java code and commit changes.

2.Open Jenkins(localhost:/8080) sign in

3.Create, add repository url, GitHub project, git, specify branch,

4\. Build steps- execution window batch command

     javac HelloWorld.java

     java HelloWorld

          or

     python Hello.py

   (**if debugger is not  there, then type where python/java in command prompt**

    \*\*copy it and paste in execution window batch)\*\*



5.Save

6.Build Now

For Automatic

7.Configure-Poll SCM - H/2 \* \* \* \*

Save

