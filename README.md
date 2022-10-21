## vim-lsp-settings-adapter

#### What?
This vim plugin allows using [mattn/vim-lsp-settings](https://github.com/mattn/vim-lsp-settings) with [yegappan/lsp](https://github.com/yegappan/lsp) to easily install and manage LSP servers.

Its basically emulating the parts of `vim-lsp` that are required by `vim-lsp-settings` and sending the commands to `lsp` instead.

#### Caveats
Quick and dirty hack, some servers don't work that well.