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

git init<br>
git add README.md<br>
git commit -m "first commit"<br>
git remote add origin https://github.com/wsmr/Ionic_app_01.git<br>
git push -u origin master<br>
…or push an existing repository from the command line<br>
git remote add origin https://github.com/wsmr/Ionic_app_01.git<br>
git push -u origin master<br>
…or import code from another repository<br>
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

<br><br>
#####################################<br>
Show your Git username and email<br>
git config user.name<br>
git config user.email<br>
git config --list<br>

Change your Git username and email<br>
git config --global user.name "first last"<br>
git config --global user.email [your email address here]<br>

<br><br>
#####################################<br>
list all the files in a commit<br>
$ git diff-tree --no-commit-id --name-only -r bd61ad98<br>

<br><br>
#####################################<br>
https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls<br>
git clone https://github.com/username/want-some-java.git<br>
git clone git@github.com:username/repo.git<br>
