# DevOps-Linux-SSH

A shell script to run on a remote server.<br>
<br>

## Setting up a secure connection
For added security, you can use SSH keys to connect to a remote server.<br>
```bash
cd .ssh
```
```bash
ssh-keygen -t rsa
```
Then copy the public key content in the server's `.ssh/authorized_keys` file.

## Acknowledgements

This project was created as part of the DevOps Bootcamp by TechWorld with Nana.
