## Links

http://www.yolinux.com/TUTORIALS/LinuxTutorialSysAdmin.html#FIND

## Commands

get your public ip

`
curl -Ss icanhazip.com
`

changing dirs

`
cd -
push /home
`

back to /home

`
popd
`

files

`
nautilis .
`

similar to grep 

```
sudo yum install the_silver_searcher
ag TODO
```

## Copy & Paste 
Environment: Fedora 25 terminal with default shortcuts enabled
(without shortcuts, Shift+Ctrl+C & Shift+Ctrl+V do not work, while Shift+Insert always works)

#### Primary (mouse)

```
Copy: select area with mouse
Copy: cat file | xclip
Copy: ls | xclip
Paste: central mouse button
Paste: Shift+Insert
Paste: xclip -o > file.txt
```

#### Secondary (clipboard)

```
Copy:  mouse right click, Copy
Copy:  Shift+Ctrl+C
Copy:  ls | xclip -selection clipboard
Paste: mouse right click, Paste
Paste: Shift+Ctrl+V
```

#### Primary & Secondary

```
Copy: select with mouse & Shift+Ctrl+C
```

#### Chrome ULR bar links

```
Note: first mouse selection (the authomatic one) does not goes into Primary

Copy to Primary:  you need to re-select 
Copy to Secondary: CTRL+C (not Shift+Ctrl+C

Paste from Primary: cetral mouse button
Paste from Secondary: CTRL+V, Shift+Ctrl+V
```

## Byobu

```
Shift-F1  Display help
Shift-F2  Horizontal split
Ctrl-F2   Vertical split
Shift-Left/Right/Up/Down     Move focus among splits
Shift-Alt-Left/Right/Up/Down Resize a split
Ctrl-F3/F4                   Move a split

Alt-PageUp/PageDown          Enter and move through scrollback (in splits)
    Alt-F11                      Expand split to a full window
    Shift-F11                    Zoom into a split, zoom out of a split
    
```

more at https://gist.github.com/devhero/7b9a7281db0ac4ba683f
