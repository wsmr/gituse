# gituse
Git Commends 
Get started by creating a new file or uploading an existing file. We recommend every repository include a README, LICENSE, and .gitignore.


…or create a new repository on the command line


echo "# Ionic_app_01" >> README.md

git status<br>
git branch<br>
git remote add origin URL
&nbsp;&nbsp;&nbsp;&nbsp;
#set a new remote<br>
git remote -v
&nbsp;&nbsp;&nbsp;&nbsp;
#Verify new remote<br>
git remote set-url origin URL
&nbsp;&nbsp;&nbsp;&nbsp;
#Instead of removing and re-adding - NEW URL
<br>
git fetch && git checkout GIT_BRANCH_NAME<br>

git init

git add README.md

git commit -m "first commit"

git remote add origin https://github.com/wsmr/Ionic_app_01.git

git push -u origin master



…or push an existing repository from the command line



git remote add origin https://github.com/wsmr/Ionic_app_01.git

git push -u origin master



…or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
