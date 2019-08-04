# Github
#### Create SSH Key
```bash
ssh-keygen -t rsa -b 4096 -C "elliotweishaar27@gmail.com"
```
#### Starting ssh-agent Manually
```bash
eval $(ssh-agent -s)
```
#### Add SSH Private Key to the SSH agent
```bash
ssh-add ~/.ssh/id_rsa
```
# Docker
#### See running instances
```bash
docker ps
```
#### Login to Docker Container
```bash
docker exec -it <dockerID> /bin/bash # same to execute any command
```
# Docker-Compose
#### Login to Docker
```bash
docker login
```
#### Add Docker Group to Login
```bash
sudo groupadd docker
sudo usermod -a -G docker $USER
sudo reboot now
```
# Mount
#### Mount nfs Drive
```bash
mount -t nfs <ip>:/path/to/share /path/to/mount
<ip>:/path/to/share	/path/to/mount	nfs	defaults	0	0	# /etc/fstab entry
```