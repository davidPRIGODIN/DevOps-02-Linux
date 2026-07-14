# DevOps-02-Linux

A simple shell script to run on a remote server via SSH.

## Setting Up a Secure Connection

For enhanced security, you can use SSH keys to authenticate to a remote server.

```bash
cd ~/.ssh
```

```bash
ssh-keygen -t rsa
```

Then, copy the contents of the public key (`id_rsa.pub` by default) to the remote server's `.ssh/authorized_keys` file.

## Acknowledgements

This demo project was created as part of the DevOps Bootcamp by **TechWorld with Nana**.<br>
Many thanks to Nana for creating such a comprehensive and practical learning experience.
