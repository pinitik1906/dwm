**dwm v6.5**

## dependencies
(if it does not build, you might need to install the `*-devel` packages also)

+ `libX11`
+ `libXft`
+ `libXinerama`
+ `freetype`
+ `fontconfig`

## patches

+ actualfullscreen
+ alwayscenter
+ attachbottom
+ hide vacant tags
+ refreshrate
+ swallow
+ uselessgap

## install
to install my dwm, type

```
git clone --depth 1 https://github.com/pinitik1906/dwm.git $HOME/stuffs/git/dwm
cd $HOME/stuffs/git/dwm
sudo make clean install
```

## configure
to edit my dwm build, please only configure in `config.h`
