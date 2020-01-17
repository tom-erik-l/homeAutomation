# homeAutomation
#
#
### Ansible on Windows 10 via WSL - working without issue
>Just wanted to share - especially for anyone who finds the Linux environment required to run Ansible a barrier to entry - in a few easy steps you can have Ansible up and running on Windows 10 via the Windows Subsystems for Linux (WSL).
>
> 1.Have Win 10
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
> - [reddit user](https://www.reddit.com/r/ansible/comments/bpi3nr/ansible_on_windows_10_via_wsl_working_without/)