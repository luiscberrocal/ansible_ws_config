# Ansible workstation configuration
Install ansible 

```shell
git clone git@github.com:luiscberrocal/ansible_ws_config.git

```

```shell
sudo nala install ansible
```

```shell
sudo ansible-playbook docker-configuration.yml
```


You need to restart the computer so your user will be part of the `docker` group.

#important  The use group addition does not seem to be working.

Last used in Pop Os jammy on 2022-08-14 10:48
