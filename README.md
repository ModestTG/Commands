# Github
#### Create SSH Key
`ssh-keygen -t rsa -b 4096 -C "elliotweishaar27@gmail.com"`

#### Starting ssh-agent Manually
`eval $(ssh-agent -s)`

#### Add SSH Private Key to the SSH agent
`ssh-add ~/.ssh/id_rsa`