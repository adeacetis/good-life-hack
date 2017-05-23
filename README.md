# good-life-hack
CL commands that will save your life.


## GIT

- Remove all merged local branches: 
`git branch --merged | egrep -v "(^\*|master|dev)" | xargs git branch -d`


- Will create a git alias that allows to see your latest commits
`git config --global alias.idid 'log --all --oneline --no-merges --author=<your_email>`

Credits @HarryRoberts:
https://csswizardry.com/2017/05/little-things-i-like-to-do-with-git/

## SSH

- Will copy your ssh key to server
`ssh-copy-id SSHUSER@SSHSERVER`
