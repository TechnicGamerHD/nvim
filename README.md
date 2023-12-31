## NeoVIM
My Neovim configuration  
Written to be installed on Debian 12/Ubuntu 22.04

# Prepare your system:
Update
```bash
sudo yay -Syu
```
Install dependencies
```bash
sudo yay -S git -y
```

Install neovim (by building it from source)  
```bash
sudo yay -S base-devel cmake unzip ninja curl
```
```bash
sudo cd /usr/local
```
```bash
sudo git clone https://github.com/neovim/neovim.git
```
```bash
make CMAKE_BUILD_TYPE=Release
```
```bash
sudo make install
```
Neovim should now be installed on your system

# Install the config
Go into the right folder
```bash
cd ~/.config/
```

Clone the nvim config
```bash
git clone https://github.com/TechnicGamerHD/nvim.git
```

First time opening neovim will install all the dependencies and plugins.  

After all the plugins are installed you should restart neovim and then you are rdy to go!
