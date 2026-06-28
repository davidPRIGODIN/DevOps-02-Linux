# DevOps-Linux-SSH

A shell script to execute on a remote server for example.<br>
<br>

## Setting up a secure connection
For added security, you can use SSH keys to connect to a remote server.<br>
`cd .ssh`<br>
`ssh-keygen -t rsa`<br>

Then copy the public key content in the server's `.ssh/authorized_keys` file.
