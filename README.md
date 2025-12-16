# Ansible Playbook for setting up My Arch Linux env.

This repository contains an Ansible playbook to automate the setup of an Arch Linux system for a specific workflow. The playbook installs necessary software packages and performs system configurations.

## Prerequisites
- Arch Linux: Ensure the system has a fresh Arch Linux installation.
- Ansible: Install Ansible on your control machine using `sudo pacman -S ansible`.

## Usage
1. Clone the repository: Run 
```sh
ansible-pull -U https://github.com/kambic/ansible-playbook.git
```

2. Run the Playbook: Execute
```sh
ansible-playbook --ask-become-pass --ask-vault-password main.yaml
```

3. Verification: Check that the Arch Linux system is set up according to your workflow requirements.

## Components Installed
The playbook sets up the following components for my workflow:
- Hyprland (Wayland Compositor)
- Waybar
- Zsh
