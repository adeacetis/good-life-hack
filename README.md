# good-life-hack
CL commands that will save your life.


## GIT

- Remove all merged local branches: 
`git branch --merged | egrep -v "(^\*|master|dev)" | xargs git branch -d`


## SSH

- Will copy your ssh key to server
`ssh-copy-id SSHUSER@SSHSERVER`
