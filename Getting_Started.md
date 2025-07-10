# Getting Started with My Linux Environment

This guide will help you set up a similar Linux learning environment to mine.

## 1. Install WSL 2 on Windows

- Follow Microsoft's official guide: https://learn.microsoft.com/en-us/windows/wsl/install  
- Install Ubuntu from the Microsoft Store

## 2. Set up AWS EC2 Instance

- Create a free-tier AWS EC2 instance (Ubuntu)  
- Generate SSH keys and configure your security groups for SSH access  
- Connect using `ssh` from your local machine (or WSL)

## 3. Configure ZSH on EC2

- Install ZSH: `sudo apt-get install zsh`  
- Install Oh My Zsh: https://ohmyz.sh/  
- Configure Powerlevel10k theme: https://github.com/romkatv/powerlevel10k  
- Customize your `.zshrc` with aliases and plugins

## 4. Useful Tips

- Use SSH agent forwarding to manage keys securely  
- Backup your config files regularly  
- Refer to the `RESOURCES.md` for tutorials and documentation links  
