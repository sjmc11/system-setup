# Dev Workstation Setup

[![Mac](https://github.com/ainsleyclark/system-setup/actions/workflows/mac.yml/badge.svg?branch=master)](https://github.com/ainsleyclark/system-setup/actions/workflows/mac.yml)
[![Ubuntu](https://github.com/ainsleyclark/system-setup/actions/workflows/ubuntu.yml/badge.svg?branch=master)](https://github.com/ainsleyclark/system-setup/actions/workflows/ubuntu.yml)

Forked from fellow dev [Ainsley Clarks System Setup](https://github.com/ainsleyclark/system-setup) 💡

Tweaked for personal preference.


## How to use
Simply download this repo or clone it and run the following:

**macOS:**
```bash
sudo chmod +x ./mac.sh
sh mac.sh
```

**Ubuntu:**
```bash
sudo chmod +x ./ubuntu.sh
sudo sh ubuntu.sh
```

## Git
Git will be configured and a username and email address will be read at the beginning of the script and set globally.
The  `.gitignore` file that resides under `./git` will be copied and used globally to exclude any large library files from
new repositories.

## ZSH
[Oh My ZSH](https://ohmyz.sh/) will be installed and aliases and functions will be copied from the `zsh` folder if the
`post-install.sh` script is run. Please feel free to clone this repo and edit.

## Versions
You are able to set the specific versions of GoLang and PHP at the very top of the install scripts.

## What's installed

### macOS

- Curl
- wget
- Git
- Chrome
- Firefox
- Edge
- iTerm2
- GoLang
- Node
- PHP
- Python
- MySQL
- MySQL Client
- VS Code
- GoLand
- PhpStorm
- DataGrip
- WebStorm
- Slack
- WhatsApp
- Zoom
- Bash 5
- Zsh
- Oh My ZSH
- KubeCTL
- Go Releaser
- Hugo
- Postman
- Simplenote
- Adobe Creative Cloud
- Spotify
- VLC
- Plex
- Transmission
- Carbon Copy Cloner
- Geekbench
- Handbrake
- Neofetch
- Webp
- OptiPNG
- JpegOptim
- libavif
- ffmpeg
- Shpotify

### Ubuntu

- Curl
- Git
- Chrome
- Edge
- GoLang
- Node
- PHP
- Python
- MySQL
- MySQL Client
- Nginx
- VS Code
- Jetbrains Toolbox
- Zsh
- Oh My ZSH
- KubeCTL
- Go Releaser
- Hugo
- Postman
- Simplenote
- Spotify
- VLC
- Webp
- OptiPNG
- JpegOptim
- ffmpeg
