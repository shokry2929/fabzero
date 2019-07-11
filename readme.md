
![alt text](sho1.png)
# Welcome fab lab menofia 
 - vinly cutter
 
 - leaser cutte
- shopbot
- electronic bench 
- 3d printer


- ![alt text](sho.png)    
Generating a new SSH key and adding it to the ssh-agent
# Steps of dealing with github

1. Sign up github
2. Confirm email
3. login with the registered email
4. Create new respotory (prefet names fabzero for now)
5. There are steps are shown on the new respotory page you should follow as you inside your local folder that contains your readme.md file like
    - git init
      - If the first command faced a problem caused by absent of git, you should follow the instructions appear to fix it
   - git add readme.md
   - git commit -m "first commit"
     - The message between the two symbols "" should be related to the editing
   - git remote add origin https://github.com/monfia/fab.git
     - fablabgharbiya: depending on your user name and respotory name
   - git push -u origin master
     - used to push the file to the respotory
6. If you want to edit the readme.md
   - Edit your file
   - Open your terminal
   - Change your directory to the readme.md file
   - Write the following commands
     - git add .
        - used to add all modified files only
    - git commit -m "modified i have made"
    - git push 
7. If you want to delete files and recover it again, in case some thing happend and you want to back to earlier point
8. Deleting data is useful to recover when it lose

[Go back to readme file](readme.md)
# Convert from  http to ssh

1. ssh-keygen -t rsa -b 4096 -C "your_email@example.com" : This creates a new ssh key, using the provided email as a label.
2. Enter a file in which to save the key (/home/you/.ssh/id_rsa): [Press enter]
3. Enter passphrase (empty for no passphrase): [Type a passphrase]
4. Enter same passphrase again: [Type passphrase again]
5. eval "$(ssh-agent -s)" : Start the ssh-agent in the background, Agent pid 59566
6. ssh-add ~/.ssh/id_rsa : Add your SSH private key to the ssh-agent
7. Then add ssh to my github
8. sudo apt-get install xclip : to copy the ssh key to my github
9. xclip -sel clip < ~/.ssh/id_rsa.pub
10. then head to github website and choose setting from the ubber left
11. ssh and gpg keys
12. new ssh key
13. paste the key
14. add ssh key
15. confirm password
16. get the ssh from get clone button
16. then head to termianl and check the remote site by using git remote -v
17. begin to replace http by ssh we get from the get clone button using command : git remote set-url origin "paste the link here"
18. done >>> weeeeeeeeeeeeeee

[Go back to readme file](readme.md)
- set ssh
- git pull
add
## inkscape
1 - open  inkscap and set size 10*5 cm 

2 -open google and download imag

3- 