# Home Server
An Ansible playbook that sets up a Debian-based server.

It assumes a fresh Debian Server 12 install, access to a non-root user with sudo privileges and a public SSH key. This can be configured during the installation process.

The playbook is mostly being developed for personal use, so stuff is going to be constantly changing and breaking. Use at your own risk and don't expect any help in setting it up on your machine.

## Special thanks
* Wolfgang for his [infra repository and videos](https://github.com/notthebee/infra).
* Jeff Geerling for his book, [Ansible for DevOps](https://www.ansiblefordevops.com/) and his [Ansible 101 series](https://www.youtube.com/watch?v=goclfp6a2IQ&list=PL2_OBreMn7FqZkvMYt6ATmgC0KAGGJNAN) on YouTube.
* Jonathan Hanson for his [SSH port juggling](https://gist.github.com/triplepoint/1ad6c6060c0f12112403d98180bcf0b4) implementation.
```
