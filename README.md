- init.lua is the main file where we call all plugins at neovim startup.

- lua directory contains individual plugin files and a file called plugins.lua.

- plugins.lua tells packer to import the plugins from git.


# Directory structure of .config/nvim:

<img width="721" alt="Screenshot 2023-07-01 at 2 37 40 AM" src="https://github.com/gitynity/nvim-config/assets/23361845/f0646fc5-2bfd-4145-9aee-1781823f7827">








##### Note: Make sure not to keep the name of the plugin file same as the name of plugin, it can cause integration issues at nvim startup. 

##### For example, name of mason plugin file can be mason-config.lua instead of mason.lua.
