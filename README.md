Neovim commands

## Git in with fugitive
 [Doc for fugitive](https://github.com/tpope/vim-fugitive/blob/master/doc/fugitive.txt)

["\<leader>gs"] go into gitmode (fugitive)

##### git add, commit and push:

["s"]   to add press over file
["cc"] to commit press to open file of commit and write save
["P"]   to push

["co\<leader>"]  setter ":Git checkout "

##### Git diff fugitvite
###### Git diff before push
[dp] To get ordinary diff above window
[dd] To get side by side diff
[=] Get diff in same window

###### Git diff open window, when ready to push:
[o]    will open horizontal
[gO] will open verticall

###### Exit commands
[:bd] exit if screwd and not exit neovim
[:q] exit normaly if more windows/ exit neovim
[ctrl+w + o] Will close all windows but the one you are inn

###### Stash commands (make a "local" branch ish)
[czz] stash changes
[czA] will force pop both changes from stash
####################################
[gu] use the diff on left
[gh] use the diff on right
## Jumping and manipulation

##### C comand
[ci"]  removes text inside ""
[ciw] removes word
[ca"] removes "" when inside

##### Jumping
[gd] go to definition
[f"] jump to the first "
[F"] jump backwords to "
[ctrl+d] go back after jumping?
##### Search
[*] searches for word in document like / but for the word your curser is on

##### Autofix
[\<leader>vca] autofix with lsp (need to be set up right)
[=] auto indents


