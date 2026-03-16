# dotfiles

my personal dotfiles for my Debian system. use these, or don't. if you do, make sure to comment out line 313 in `.config/oxwm/config.lua`

## dependancies

install the deps before following the installation guide

```
$ sudo apt install lua5.4 libx11-dev libxft-dev libfreetype-dev fontconfig pkg-config kitty 
```

also dont forget to grab brave

```
curl -fsS https://dl.brave.com/install.sh | CHANNEL=nightly sh
```

then install oxwm with the Manual Build instructions listed on https://ox-docs.vercel.app/docs/installation.

## installation

if you DO want to use these, use these commands:

```
$ git clone git@github.com:regedit-sys/dotfiles.git
$ cd dotfiles
```

then use GNU stow to create symlinks

```
$ stow .
```


### credits

dreamsofautonomy for creating the guide i followed to actually put these up: https://www.youtube.com/watch?v=y6XCebnB9gs

@tony-btw on youtube for making oxwm @ https://github.com/tonybanters/oxwm

and YOU for being able to understand BUZZWORD BUZZWORD BUZZWORD BUZZWORD




licensed under the unlicense, 2026 fruqal
