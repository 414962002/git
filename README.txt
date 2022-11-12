
░██████╗░██╗████████╗
██╔════╝░██║╚══██╔══╝
██║░░██╗░██║░░░██║░░░
██║░░╚██╗██║░░░██║░░░
╚██████╔╝██║░░░██║░░░
░╚═════╝░╚═╝░░░╚═╝░░░

create a new repository using the terminal      
without local pass - first initialization  
(run & search git key: Credential Manager  
Control Panel\UserAccounts\CredentialManager)    

———————————————————————

█▀▀ █ ▀█▀
█▄█ █ ░█░

1
create new repo
start https://github.com/new  

```
- open terminal
- Win + X + A
```  

create folder
mkdir <name>

move to folder
cd <name>

create files
touch <name>

2
create local git rep
git init

create user
git config --local user.name <user name>

create email
git config --local user.email <user email>

3
to add a new remote  
(creates a new remote called origin)
git remote add origin https://github.com/
<name user>/<name repo>.git

add files or changes
git add .

commit
git commit -m message

to push commits to server
(push the commits in the local branch 
named main to the remote)
git push -u origin main  

                                 ***
create a new repository using the terminal  
————————————————————-
     

local_create local git repository    
git init

remote_create new web repo  
start https://github.com/new

local_to add a new remote  creates 
a new remote called origin  
git remote add origin 
https://github.com/<name user>/<name repo>.git

local_add files or changes    
git add .

local_commit    
git commit -m message

local_to push commits to server  
push the commits in the local branch 
named main to the remote named origin  
git push -u origin main
