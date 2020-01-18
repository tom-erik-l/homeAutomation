# homeAutomation
#
### Transfer Windows 10 SSH keys into Ubuntu 
From https://peteoshea.co.uk/setup-git-in-wsl/:
>If you have an SSH key already setup on Windows you could reuse it rather than creating a new one. (Note that PuTTY keys do not work here). To do this you can just copy the key from the Windows filesystem into the WSL’s filesystem. Linux has some rules about how visible the key is. So you need to make sure the access levels are strict enough to meet these requirements:
```
> $ cd ~
> $ mkdir .ssh
> $ chmod 700 .ssh
> $ cd .ssh
> $ cp /mnt/c/Users/user/.ssh/id_rsa* .
> $ chmod 600 id_rsa
> $ chmod 644 id_rsa.pub
```

### Ansible on Windows 10 via WSL - working without issue
From [reddit user](https://www.reddit.com/r/ansible/comments/bpi3nr/ansible_on_windows_10_via_wsl_working_without/):
>Just wanted to share - especially for anyone who finds the Linux environment required to run Ansible a barrier to entry - in a few easy steps you can have Ansible up and running on Windows 10 via the Windows Subsystems for Linux (WSL).
>
> 1. Have Win 10
> 1. Install WSL via control panel programs and features
> 1. Install Ubuntu from Microsoft Store
> 1. Install Ansible in Ubuntu
> 1. Git clone your repository with your playbooks into Ubuntu
> 1. Update your repo permissions ( chmod 755 )
> 1. From here you can run your Ansible playbooks !
>
>**Bonus!**
>
> 1. Install VS Code
> 1. Change your default terminal to WSL
> 1. Run your playbooks from your Windows VS Code directly! This means you can write your playbooks / YAML / Jinja and run your playbooks from the editor directly !