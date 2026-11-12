# open-terminal (Proxmox LXC)

An automated script to provision a Proxmox LXC container and install the `open-terminal` tool.

## Quick Start
To create a new LXC container and automatically install `open-terminal` using the automated provisioner, run the following command in your Proxmox shell:

```bash
bash -c "$(curl -sLo- https://github.com/ctrl-alt-me/open-terminal-lxc/raw/main/install.sh)"
```

## Description
`open-terminal` is a tool designed to give your AI agents a computer. See more at the [official repository](https://github.com/open-webui/open-terminal).

This repository provides a one-click provisioning script for Proxmox. It automates the creation of a dedicated LXC container, configures the environment, and installs the `open-terminal` software.

## Features
- **One-Click Provisioning:** Automatically creates the LXC container and handles all setup.
- **Automated Environment:** Sets up a Python virtual environment and system links.
- **Optimized for LXC:** Designed to run efficiently in a lightweight container.

## Requirements
- A running Proxmox (PVE) environment.
- Access to the Proxmox shell (via web GUI or SSH).

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing
If you have suggestions for the provisioning script or want to improve the setup process, feel free to open an issue or submit a pull request.
