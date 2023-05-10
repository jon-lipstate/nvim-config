install from here:
https://github.com/neovim/neovim/wiki/Installing-Neovim#install-from-download

fork:
https://github.com/nvim-lua/kickstart.nvim

edit theme:
https://github.com/Shatur/neovim-ayu

install/build OLS
https://github.com/DanielGavin/ols

add to .bashrc PATH
`nvim ~/.bashrc`
`export PATH=$PATH:/home/mjolnir/Odin:/home/mjolnir/.local/bin:/home/mjolnir/ols`

add to `init.lua`
```lua
local lspconfig = require('lspconfig')
lspconfig.ols.setup({})
```

Add Syntax Highlighting:
https://github.com/Tetralux/odin.vim
TODO: