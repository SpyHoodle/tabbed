# tabbed
My build of suckless's tabbed, with better keybinds and colours.

![tabbed screenshot](https://file.coffee/u/nb0c4GY8kLv84y.png)

# installation
Clone the git repository
```sh
git clone https://github.com/SpyHoodle/tabbed
```
Change directory to tabbed
```sh
cd tabbed
```
Make and install tabbed
```sh
make install
```
**Final step:** Add a colourscheme to `~/.config/cols/tabbed.h`. This is where tabbed will read a colorscheme.<br>
This should be in the usual form tabbed would have a colourscheme in it's own source code, as `tabbed.h` is included at compile time.<br>
Alternatively, you could change the location of the colourscheme in `config.h`.
