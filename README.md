# IDE neovim config on WSL

## Installation
### on windows side

use [`win32yank`](https://github.com/equalsraf/win32yank) instead of clip.exe ( doesn't support utf8)

```sh
choco install win32yank
```

### on wsl side
```sh
sudo add-apt-repository ppa:neovim-ppa/unstable
sudo apt update
sudo apt install
    neovim\
    unzip ripgrep fd-find\
    gcc g++ make\
    python3-full python3-venv python-pynvim\

git clone --recurse-submodules git@github.com:vuongkienthanh/nvim-configs-wsl.git ~/.config/nvim
```

## Update
```sh
git pull --recurse-submodules
```
