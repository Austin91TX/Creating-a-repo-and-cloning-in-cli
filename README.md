# Creating-a-repo-and-cloning-in-cli

#in CLI
ssh-keygen
#create ssh keys

cd ~\.ssh
#change directory to ssh folder

cat id_rsa.pub
#concatenates public key. Copy this and upload into https://github.com/settings/keys


#in https://github.com/new
Create the repo in github


#in CLI
git clone git@github.com:Austin91TX/powershell-scripts.git
#git clone [link is from repo page on github, code > ssh]

cd 'C:\Users\Austin George\powershell-scripts\'
#change directory to the powershell-scripts folder
