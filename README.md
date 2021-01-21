# VS Code LaTeX template

Template for writing latex with vscode

## Setup

### Mac

1. Install [homebrew](https://brew.sh/)
2. Install Docker and setup

```bash
brew install docker
brew install --cask docker
open /Applications/Docker.app
```

3. Share this folder for docker

Open Docker Desktop `Preferences -> Resources -> FILE SHARING` and add this folder.

### Win

1. Install [chocolatey](https://chocolatey.org/)
2. Install Docker and setup

```bash
choco install docker-desktop
```

3. Logout and login to Windows

### Common

1. Setup docker containers

```bash
docker pull nshun/latex
```

2. Install vscode extension

- James-Yu.latex-workshop

```bash
code --install-extension James-Yu.latex-workshop
```

### Update

```bash
docker pull nshun/latex
```
