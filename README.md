# datafun-03-analytics

#Changed Directory to Documents on MacOS
#cd ~/Documents

#Git command to clone repository down to Machine
#git clone https://github.com/mzl02/datafun-03-analytics.git

#Created a .gitignore file under the project (datafun-03-analytics)

#In the .gitignore file added the following two lines

# Exclude VS Code workspace settings
#.vscode/

# Exclude Python virtual environment folder
#.venv/

#Adds files to the local git repository
#git add .

#Commits changes
#git commit
#NOTE  I was get a weird popup.  Through me into VIM.
#I ran the following command to force nano
#git config --global core.editor "nano"

#git add .  #again
#git commit
#pasted 'git commit -m "initial commit"'
#git push origin main

#Changed editor back to VIM
#git config --global core.editor "vim"

#In VIM when I saved and quit correctly, I got different output as follows:
#XXX:datafun-03-analytics zachlawrence$ git commit
#[main 1d8c019] inital commit
# 1 file changed, 5 insertions(+)
# create mode 100644 .gitignore
#XXX:datafun-03-analytics zachlawrence$ git push
#Enumerating objects: 4, done.
#Counting objects: 100% (4/4), done.
#Delta compression using up to 8 threads
#Compressing objects: 100% (3/3), done.
#Writing objects: 100% (3/3), 359 bytes | 359.00 KiB/s, done.
#Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
#To https://github.com/mzl02/datafun-03-analytics.git
#   878ae62..1d8c019  main -> main
XXX:datafun-03-analytics zachlawrence$ 

#Now the gitingore appeared under the project in Github