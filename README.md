# How to use
1. Install this `nvim` repository into your `~/.config/nvim`
2. Open a [packer.lua](./lua/huna/packer.lua) and type `:so` and sync dependencies with `:PackerSync`
3. If you want to install `pyright`, you should install the node.js

# Simple Usage
- When you want to go to a definition, you can type as shown below:
  - Move directly to the definition: `gd`
    - You can return to the previous location by pressing `C-o`, or move forward with `C-i`
  - Open the definition in a hover window: `K`
