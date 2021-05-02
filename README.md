# testrepo
test repository to test git commands for better understanding

Note: These are my first change to Readme.md file

some more changes to test pull request.

**Problem of git push** 
403 error

on git push faced below error:
remote: You must verify your email address.
remote: See https://github.com/settings/emails.
fatal: unable to access 'https://github.com/xs2harpreetgithub/testrepo.git/': The requested URL returned error: 403

`Solution:`
 
git remote set-url origin https://xs2harpreetgithub:xs2github@github.com/xs2harpreetgithub/testrepo.git

<git remote set-url origin https://username:password@github.com/username/testrepo.git>

**Common Git Commands**
-git checkout <branch_name>       change branch
-git add .                        all files
-git add <filename>
-git commit -m "msg"
-git push
 
 create a new local feature branch
 -git checkout -b <new_feature_branch>
 or
 -git branch <branch-name>
 Push local changes to remote
 -git push origin <feature branch name>
 
 Removing branch locally
 -git branch -d <branch-name>
 
 -D for force fully (if it's not fully merged)
 
 
