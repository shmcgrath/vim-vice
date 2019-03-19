# vim-vice
![logo][logo]
<p align="center"><i>“No one gossips about others' secret virtues.”</i></p>

Vice is a dark and vibrant colorscheme for vim.

![screencap][screencap]

## Installing

Install vim-vice using your plugin manager of choice:
```
" Vundle
Plugin 'shmcgrath/vim-vice'
" vim-plug
Plug 'shmcgrath/vim-vice'
" NeoBundle
NeoBundle 'shmcgrath/vim-vice'
```

Or install manually:
```
curl -Lo ~/.vim/colors/vice.vim https://raw.githubusercontent.com/shmcgrath/vim-vice/master/colors/vice.vim
```

And activate in your `.vimrc`:
```
colorscheme vice
```

## Other Platforms

Vice colorscheme ports to other terminal emulators and applications can be found in the `contrib/` dir

### Xresources

Copy the contents of [xresources/vice](xresources/vice) into your `~/.Xresources` config file.

Then run `xrdb ~/.Xresources` to reload the config.

### Terminator

Backup your existing terminator config:
```bash
cp -v ~/.config/terminator/config{,.bk}
```

Then copy [terminator/vice](terminator/vice) to `~/.config/terminator/config` or `$XDG_CONFIG_HOME/terminator/config` if you're running OS X.

Restart terminator to load the Vice colorscheme.

### Sublime

Install to the default Sublime directory:

```bash
cd contrib/sublime
make install
```

And select the Vice theme in `Preferences > Color Scheme`.

### [gotop](https://github.com/cjbassi/gotop)

Provide the `-c` option to use the Vice colorscheme:
```bash
gotop -c vice
```

[logo]: http://i.imgur.com/HWvyN7M.png "vice"
[screencap]: http://i.imgur.com/WPRvqy4.png "vice"

## [shmcgrath](https://github.com/shmcgrath/vim-vice) changes
- Add information for FoldColumn
- Add iTerm2 colorscheme
