# Ansible Repo for management linux servers

## List ansible roles
- base-config
- bootstrap-server
- sshd-with-ports
- update-pkgs

## Role base-config
Done tasks:
[X] Add/remove users
[X] Add/remove user to groups
[X] Add/remove ssh key for users
[X] Turn off ipv6 and apply settings
[X] Install software
[X] Configure UFW for sshd

## Role bootstrap-server
Done tasks:
- [X] Add new system user for ansible
- [X] Configuration sudoers for system user
- [X] Add ssh key for system user

## Role sshd-with-ports
Done tasks:
- [X] Configuration sshd
  - [X] отключается авторизация по паролю
  - [X] включается авторизация только по ключу
  - [X] disable auth root
  - [X] change sshd port
  - [X] restart sshd service if configuration changed

## Role update-pkgs
Done tasks:
- [X] Update packages for Alpine Linux


### TODO Tasks
- [X] Add and configuration logrotate
- [X] Add and configuration failt2ban with sshd
- [X] Add and configuration Docker
- [X] Add and configuration Podman
- [ ] Add and coniguration VPN-server
