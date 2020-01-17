# homeAutomation
#
#
### Ansible on Windows 10 via WSL - working without issue
>Just wanted to share - especially for anyone who finds the Linux environment required to run Ansible a barrier to entry - in a few easy steps you can have Ansible up and running on Windows 10 via the Windows Subsystems for Linux (WSL).
>Have Win 10
>Install WSL via control panel programs and features
>Install Ubuntu from Microsoft Store
>Install Ansible in Ubuntu
>Git clone your repository with your playbooks into Ubuntu
>Update your repo permissions ( chmod 755 )
>From here you can run your Ansible playbooks !
>
>**Bonus!**
>
>Install VS Code
>Change your default terminal to WSL
>Run your playbooks from your Windows VS Code directly! This means you can write your playbooks / YAML / Jinja and run your playbooks from the editor directly !
> - [reddit user](https://www.reddit.com/r/ansible/comments/bpi3nr/ansible_on_windows_10_via_wsl_working_without/)