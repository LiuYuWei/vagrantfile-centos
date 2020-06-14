# vagrantfile-centos-docker
Use vagrantfile to build the CentOS Linux environment and docker environment.

## Install Chocolatey
https://marcus116.blogspot.com/2019/02/chocolatey-windows-chocolatey.html

## Install software.

#### Install vagrant
```shell
choco install vagrant -y
```

#### Install virtualbox
```shell
choco install virtualbox -y
```
#### Upgrade Powershell to newer version
```shell
choco install powershell -y
```
#### Install git
```shell
choco install git -y
```

## Use it:
```shell
vagrant up
vagrant ssh
```

## Close it:
```shell
vagrant halt
```