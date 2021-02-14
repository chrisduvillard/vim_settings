call plug#begin()
" Solarized Theme
Plug 'lifepillar/vim-solarized8'
Plug 'SirVer/ultisnips'
Plug 'honza/vim-snippets'
"Plug 'vim-scripts/indentpython.vim'
Plug 'valloric/python-indent'
Plug 'nvie/vim-flake8'
Plug 'scrooloose/nerdtree'
Plug 'jistr/vim-nerdtree-tabs'
call plug#end()

" Coloring
set background=dark
colorscheme solarized8

set encoding=utf-8
set nu

"split navigations
nnoremap <C-J> <C-W><C-J> "ctrl + j move to the split below
nnoremap <C-K> <C-W><C-K>
nnoremap <C-L> <C-W><C-L>
nnoremap <C-H> <C-W><C-H>

"au BufNewFile,BufRead *.py
"    \ set tabstop=4
"    \ set softtabstop=4
"    \ set shiftwidth=4
"    \ set textwidth=79
"    \ set expandtab
"    \ set autoindent
"    \ set fileformat=unix

"au BufNewFile,BufRead *.js, *.html, *.css
"    \ set tabstop=2
"    \ set softtabstop=2
"    \ set shiftwidth=2

" Press CTRL+R to run python script into separate term window 
nnoremap <C-R> :sp <CR> :term python % <CR>
nnoremap <C-W> :bd!<CR>

"Buffer management
:nnoremap <Tab> :n<cr>
:nnoremap <S-Tab> :N<cr>

" Tab management
nnoremap tn :tabnew<Space>
nnoremap tk :tabnext<CR>
nnoremap tj :tabprev<CR>
nnoremap th :tabfirst<CR>
nnoremap tl :tablast<CR>

" Remap Esc key
inoremap kj <Esc>
