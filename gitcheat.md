#Git Cheatsheet 
** Name ** R Nugent III
** Date ** 17 Jan 2017 

the pound names the heading. 

git config --global user.name "[NAME]"
configures the git with the user name rnugent

git --config --global user.email [email.address]
configures the git with email rnugent@gradcenter.cuny.edu

git config --list
this lists the configuration of username and email, should list rnugent and rnugent@gradcenter.cuny.edu

git init
initializes git
starts the git 

git remote add origin [URL of remote repo]
connects the repository to the git remote on the computer 

git remote -v
don't remember 

git status
what is the status of the git? connected (green) or not connected (red)

git log 

git add [and a dot or a file name]
add the files you want to be tracked 

then you could check the file status see if it is green 

git commit -m "[clear message describing the changes you made]"
so this is like a decided benchmark of changes versions  

git push origin master 
push the stuff 

So we change something in a file. We typetypetypetype. REACH A STOPPING POINT?
1) ADD
2) COMMIT (with -m and "clear message")
3) PUSH
------> REPEAT.