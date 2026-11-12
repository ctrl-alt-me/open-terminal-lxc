# open-terminal (Proxmox LXC)

An automated Proxmox LXC installation script for the open-terminal tool.

## Quick Start
To create a new LXC container and automatically install `open-terminal`, run the following command in your Proxmox shell:

```bash
bash -c "$(curl -sLo- https://github.com/ctrl-alt-me/open-terminal-lxc/raw/main/install.sh)"
```

## Description
`open-terminal` is a tool designed to give your AI agents a computer. See more at the open-terminal repo [here](https://github.com/open-webui/open-terminal).

This repository provides a streamlined way to deploy it on Proxmox using a lightweight LXC container instead of a standard installation.

## Features
- **Automated Setup:** Handles all dependency installations (Python, pip, etc.).
- **Isolated Environment:** Installs `open-terminal` into a dedicated Python virtual environment.
- **Fast Performance:** Runs in a lightweight LXC container for minimal overhead.

## Requirements
- A running Proxmox (PVE) environment.
- Access to the Proxmox shell (via web GUI or SSH).

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing
If you have suggestions for the installation script or want to improve the setup process, feel free to open an issue or submit a pull request.
```
