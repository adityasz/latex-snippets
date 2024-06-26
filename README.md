## Configuration

Copy `tex.snippets` to `~/.vim/UltiSnips/`. Assuming you're using [Vim Plug](https://github.com/junegunn/vim-plug), add the following to your `.vimrc`:

```vim
Plug 'sirver/ultisnips'
    let g:UltiSnipsExpandTrigger = '<Tab>'
    let g:UltiSnipsJumpForwardTrigger = '<Tab>'
    let g:UltiSnipsJumpBackwardTrigger = '<S-Tab>'
```
