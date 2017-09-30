# Ansible - deployment and configuration management

Early draft of example files for a Micromata tech-talk.

## Docker environment

To set up the docker environment please replace the file `docker/sshd/.ssh/authorized_keys` with your ssh public-key

## Ansible execution prerequisites 

To resolve the _pseudo_ hostnames via the ansible ssh-execution, add the config parameters of `ssh_config` to your `~/.ssh/config`. If your ssh-keypair name isn't `id_rsa`, you have to change the reference to your identity file.
