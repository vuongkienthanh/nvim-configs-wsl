# IDE neovim config on WSL

## Install
### on windows side

```sh
winget install win32yank
```

### on wsl side

```sh
snap install nvim --edge --classic
```

```sh
sudo apt update
sudo apt install\
    software-properties-common\
    git curl wget\
    gzip tar unzip\
    ripgrep fd-find\
    gcc g++ make\
    python3-full python3-venv python3-pynvim\
    nodejs npm\

git clone --recurse-submodules git@github.com:vuongkienthanh/nvim-configs-linux.git ~/.config/nvim
```

## Update

```sh
git pull --recurse-submodules
```
