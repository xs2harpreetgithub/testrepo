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
