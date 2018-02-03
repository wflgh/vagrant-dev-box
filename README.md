# vagrant-devbox

This builds a Centos dev box

## Prereqs

* vagrant
* Centos 7.x box

## Provisioners

This vagrantfile uses an ansible_local provisioner to configure the box

#### ansible roles

- ansible-role-c-development
- ansible-role-ruby-development
