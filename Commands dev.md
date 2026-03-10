1. **Project in local and remote repository** 



1.Create a Folder in desktop and create a text folder inside it.

2\. In Git Bash - cd desktop/FolderName.

&nbsp;                git init

&nbsp;                git remote add origin https://github.com/poorvimalavade3005-collab/DevopsLab.git

&nbsp;                git add .

&nbsp;                git commit -m "my new commit

                 **git config --local user.name "poorvimalavade3005-collab"**

                 **git config --local user.email "poorvimalavade3005@gmail.com"**

                 git commit -m "my new commit

&nbsp;                git push origin master

&nbsp;                git config --local user.email "poorvimalavade3005@gmail.com"

&nbsp;                git push origin master

&nbsp;                git log

&nbsp;                git status

&nbsp;    (Create another new text document in folder)

&nbsp;                git status

&nbsp;                git add .

&nbsp;                git status

&nbsp;                git clone https://github.com/poorvimalavade3005-collab/DevopsLab.git

&nbsp;                git reset --hard

 **(error regarding another account in GitHub - go to settings > credential manager> git > remove)**



**\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_**



**2.**





















**\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_**



**3.Jenkins**



Configuration:

1.Create a new Repository in GitHub and create a file with java code and commit changes.

2.Open Jenkins(localhost:/8080) sign in

3.Create, add repository url, GitHub project, git, specify branch,

4\. Build steps- execution window batch command

     javac HelloWorld.java

     java HelloWorld

&nbsp;         or

&nbsp;    python Hello.py

&nbsp;  (**if debugger is not  there, then type where python/java in command prompt**

    **copy it and paste in execution window batch)**

5.Save

6.Build Now

For Automatic

7.Configure-Poll SCM - H/2 \* \* \* \*

Save



























