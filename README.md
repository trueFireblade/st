# trueFireblade's build of st - the suckless terminal

My build of the [suckless terminal (st)](https://st.suckless.org/)

## Optical Stuff

+ **3 themes:** [gruvbox](https://github.com/morhetz/gruvbox), [dark solarized](https://ethanschoonover.com/solarized) and [light solarized](https://ethanschoonover.com/solarized)
+ **font:** system "mono" at 16pt

## Features using dmenu

+ **follow urls** by pressing `alt-l`
+ **copy urls** in the same way with `alt-y`
+ **copy the output of commands** with `alt-o`

## Bindings

+ **switch theme** with `alt-t`
+ **scrollback** with `alt-↑/↓` or `alt-pageup/down` or `shift` while scrolling the mouse
+ OR **vim-bindings**: scroll up/down in history with `alt-k` and `alt-j`. Faster with `alt-u`/`alt-d`.
+ **zoom/change font size**: same bindings as above, but holding down shift as well. `alt-home` returns to default
+ **copy text** with `alt-c`, **paste** is `alt-v` or `shift-insert`

## Other st patches

+ Vertcenter
+ Scrollback
+ font2


## Dependencies

+ `libX11` and `libXft` and `fontconfig` are required for building
+ For the *features using dmenu* you obviously need `dmenu`.
+ For *following ulrs* you need to set a `BROWSER` in `~/.profile`.
+ For *transparency* you need a composite manager (`xcompmgr`, `compton`, etc.).
