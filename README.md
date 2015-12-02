#Git_Command
Git Command to Use usually
##1.initial work on ubuntu
a.install git:
  sudo apt-get install git-core
b.set env:
  git config --global user.name "username"
  git config --global user.email "useremail"
c.generate ssh-key:
  ssh-keygen -C 'you email address@gmail.com' -t rsa
d.copy ssh-key to github:
  ~/.ssh/id_rsa.pub
e.test git:
  ssh -v git@github.com
##2.Clone from github
git clone git@github.com:michaelliao/gitskills.git
##3.Push to github
git add files  
git commit -m "comments"  
git push origin master
##4.Add all untracked files
git add -A .



