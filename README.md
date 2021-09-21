# vim-config: .vimrc

# Deactivate visual mode
set mouse=

# Activate syntax coloration
syntax on

# set the number of each line
set number

# Set a vertical line after 120 caracters 
set cc=120

# Set a line under the cursor
set cursorline

# Theme industry
colorscheme industry

# Generic identation
set tabstop=4
set autoindent
set expandtab
set softtabstop=4

# Yaml specific indentation
autocmd FileType yaml setlocale tabstop=2 shiftwidth=2 softtabstop=2 expandtab

# Highlight remaining space at the end of lines
highlight endline ctermbg=magenta
match endline /\s\+$/
