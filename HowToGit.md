# How to GIT
First, set up an account in Github (https://github.com). 

Second, create a repository in Github. You can create at the same time basic versions of a README.md (Initial documentation) and .gitignore (List of files to NOT back-up in github).

Lastly, follow the instructions on how to create a public key and upload it to Github (https://github.com/settings/keys)

In HPC, a public key is created the first time you log in, and is in the file ~/.ssh/rsa_id.pub (you can copy and paste the contents of that faile into github as a SSH key to use). By using this option, you will not need to type your username and password every time you synchronize your files with Github.


## Cloning
In the repository, copy the SSH Code (ex. git@github.com:madhut015/gis_python.git)

In Wendian, go to a directory where you want to clone, and run
git clone git@github.com:madhut015/gis_python.git

## Modifiying file
Just make changes!

At the end, make sure to add them to the Github list with 
git add <filename_1> <filename_2>

## Committing
git commit -m "Your message here"

## Pushing
git push

## Pulling
git pull


## Other
You can get the current status
git status

Add and change to a new branch, etc.....
The sky is the limit!
