# Debian-9-LAMP
A quick guide to setup a LAMP on Debian 9 Strech 
- - - -

## Securise the server
- - - -

### Change the port

First, we need to connect to ssh and change the connection port (Wich is by default 22). For this, open the file `ssh_config` and change it. Reload the ssh config, then reconnect using the port you choose before like this 

### Add a new user & add it to the sudo group

Add a user like this 
`useradd username`

Add it to the sudo group
`useradd username sudo`

Reconnect with the new user

### Remove access with user root


### Enable access by ssh key RSA

### Remove access by password

### Install fail2ban

## Install Apache
`apt-get install apache2`

### Virtualhost config

### Enabled sites & rewritemod

### Install Php & MySQL

## Tools
### Composer

### Npm

### Vim

### Git

**configure git hooks & remote**







