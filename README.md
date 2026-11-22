# ALU System Engineering & DevOps

## Description
This repository contains projects and exercises completed as part of the System Engineering and DevOps curriculum at the African Leadership University (ALU).

The projects focus on understanding Linux systems, shell commands, networking, server administration, SSH configuration, and basic DevOps practices.

## Project: SSH

The `ssh` directory contains exercises focused on Secure Shell (SSH), public-key authentication, and secure remote server access.

### Tasks

| File | Description |
|---|---|
| `0-use_a_private_key` | Bash script that connects to a remote server using a specified private SSH key. |
| `1-create_ssh_key_pair` | Bash script that generates a 4096-bit RSA key pair protected with a passphrase. |
| `2-ssh_config` | SSH client configuration that specifies the private key and disables password authentication. |

### SSH Concepts Covered
- Generating RSA public and private key pairs.
- Understanding public-key and private-key authentication.
- Connecting to remote Ubuntu servers using SSH.
- Configuring SSH client settings.
- Managing authorized public keys using `authorized_keys`.
- Setting appropriate permissions for SSH files.

## Repository Structure

```text
alu-system_engineering-devops/
│
└── ssh/
    ├── 0-use_a_private_key
    ├── 1-create_ssh_key_pair
    └── 2-ssh_config
```

## Learning Objectives
The main objective of these exercises is to develop practical skills in Linux system administration, secure remote connections, authentication, and automation using Bash.

## Author
**Vladimir Ndayisaba**

