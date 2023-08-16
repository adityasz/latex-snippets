## Vim configuration

Copy `tex.snippets` to `~/.vim/UltiSnips/` and assuming you're using [Vim Plug](https://github.com/junegunn/vim-plug), add the following to your `.vimrc`:

```vim
Plug 'sirver/ultisnips'
    let g:UltiSnipsExpandTrigger = '<tab>'
    let g:UltiSnipsJumpForwardTrigger = '<tab>'
    let g:UltiSnipsJumpBackwardTrigger = '<s-tab>'

Plug 'lervag/vimtex'
    let g:tex_flavor='latex'
    let g:vimtex_view_method='zathura'
    let g:vimtex_quickfix_mode=0
```
