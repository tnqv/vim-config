My VIM config repository.

## Installation

Install [neovim](https://neovim.io/)

Check my init.vim to see my config.

Copy init.vim to ~/.config/nvim/init.vim

Run `nvim +PlugInstall`

### Requirements:
- the_silver_searchers: https://github.com/ggreer/the_silver_searcher
- vim-plug: https://github.com/junegunn/vim-plug
- nerd-font for vim-devicon

## Plugin

### Theme:
- Dracular theme

### Liked IDE Tools:

- [NERDTree](https://github.com/preservim/nerdtree) - For files explorer tree
- [Vim-Devicon](https://github.com/ryanoasis/vim-devicons) - For NERDTree icons
- [Vim-Easymotion](https://github.com/easymotion/vim-easymotion) - For fast motion cursor to words
- [FZF](https://github.com/junegunn/fzf) with The-silver-searcher - For search files
- [vim-airline]() - Coloring commands type in Vim 

### Language Client support Tools:
- [vim-go](https://github.com/fatih/vim-go)
- [typescript-vim](https://github.com/leafgarland/typescript-vim)
- [coc.nvim](https://github.com/neoclide/coc.nvim)

### Shortkeys Note:
- Control + P: Open search files
- <Leader> + 1,2,3,4,5,6,..: Switch to tab 1,2,3,4,5,6,...
- <Leader> + words + <Enter>: Use vimmotion to direct to searched words
- <Leader> + g: Use gitblame
- Ctrl + G: Search contains in files
- alt + hjkl: Move between split/vsplit panels
- Ctrl + n: Open new terminal in vertical tab
