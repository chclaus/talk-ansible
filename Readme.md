# Ansible - deployment and configuration management

Example repository for the Micromata TECH-TALK [Ansible - a brief introduction](https://www.micromata.de/blog/ansible-agile-softwareentwicklung).

The slides to this repository can be found at https://slides.com/chclaus/ansible

## Docker environment

To set up the docker environment please replace the file `docker/sshd/.ssh/authorized_keys` with your ssh public-key

## Ansible execution prerequisites 

To resolve the _pseudo_ hostnames via the ansible ssh-execution, add the config parameters of `ssh_config` to your `~/.ssh/config`. If your ssh-keypair name isn't `id_rsa`, you have to change the reference to your identity file.
