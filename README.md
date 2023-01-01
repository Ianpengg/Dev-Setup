# Dev-Setup
This repository is for storing all my develope environment setting and automated script

# Nvim (with lua config)
Use this repository as my default initial settings 
https://github.com/nvim-lua/kickstart.nvim
- In order to use these settings we need latest nvim version : here I use nightly 
- And the installation with Appimage is different from usual installation with `apt-get`
  - Following are the steps
  - 1. Download the appimage from nvim's official Repository https://github.com/neovim/neovim/releases/tag/nightly
  - 2. `mv ./nvim.appimage ./nvim`
  - 3. `chmod +x nvim`
  - 4. `sudo chown root:root nvim`
  - 5. `mv nvim /usr/bin`
