# nvchad-python

`nvchad-python` is a Neovim configuration tailored for Python development.

## Prerequisites

Before you can use `nvchad-python`, there are a few prerequisites you need to install:

### Neovim (unstable)
```bash
sudo add-apt-repository ppa:neovim-ppa/unstable
sudo nala upgrade -y; sudo nala install neovim
```
### Install nvchad
```bash
git clone https://github.com/NvChad/NvChad ~/.config/nvim --depth 1 && nvim
```
### Node.js and npm

You can install Node.js and npm using the Nala package manager with the following command:

```bash
sudo nala install nodejs npm -y
```
### Python Pip and venv

The Python package manager Pip and the venv module, which is used for creating virtual environments in Python, are also required. You can install them using Nala with the following commands:
```bash
sudo nala install python3-pip -y
sudo nala install python3-venv -y
```
### Open nvim in insert mode
```
:MasonInstallAll
```

