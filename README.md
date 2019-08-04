# Github
#### Create SSH Key
`ssh-keygen -t rsa -b 4096 -C "elliotweishaar27@gmail.com"`

#### Starting ssh-agent Manually
`eval $(ssh-agent -s)`

#### Add SSH Private Key to the SSH agent
`ssh-add ~/.ssh/id_rsa`

# Docker
#### See running instances
`docker ps`

# Docker-Compose
#### Login to Docker
`docker login`

#### Add Docker Group to Login
`sudo groupadd docker
sudo usermod -a -G docker $USER
sudo reboot now`

# Mount
#### Mount nfs Drive
`mount -t nfs <ip>:/path/to/share /path/to/mount
<ip>:/path/to/share	/path/to/mount	nfs	defaults	0	0	# /etc/fstab entry`