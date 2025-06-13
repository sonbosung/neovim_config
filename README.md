# neovim_config
neovim configuration files for easy setup

# How to setup?
```bash
sudo apt update
sudo apt install -y ninja-build gettext cmake unzip curl \
  build-essential tar libtool libtool-bin autoconf automake \
  pkg-config git
git clone https://github.com/neovim/neovim.git
cd neovim
git checkout stable
make CMAKE_BUILD_TYPE=RelWithDebInfo
sudo make install
nvim --version
cd ~
git clone https://github.com/sonbosung/neovim_config.git
cp -r neovim_config/lua ~/.config/nvim/.
```
Enjoy!
