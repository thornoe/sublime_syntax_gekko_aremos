# Gekko and Aremos package for Sublime Text
Package for syntax highligting in [Sublime Text 3.0](https://www.sublimetext.com/3) for AREMOS and [Gekko Timeseries And Modeling Software](https://github.com/thomsen67/GekkoTimeseries).

## Getting started

### 1. Manual installation
In Sublime go to ` Preferences -> Browse Packages... ` and either download and unzip this package into that directory, or use

``` bash
git clone https://github.com/thornoe/sublime_syntax_gekko_aremos "sublime-syntax-gekko-aremos"
```

### 2. Set syntax as default
Then move the two files ` aremos.sublime-settings ` and ` gekko.sublime-settings ` to the root of the User folder, e.g.

``` bash
C:\Users\%userprofile%\AppData\Roaming\Sublime Text 3\Packages\User\
```

### 3. Switch themes
Go to ` Preferences -> Color Scheme... ` and choose ` Monokai_Gekko_Aremos `.

## Acknowledgements
This package builds on Martin Bonde's package for syntax highlighting and remote build in Sublime for Gekko:
https://github.com/MartinBonde/gekko_sublime

It has been extended with different colours for commands for Gekko code as well as for Aremos code.

The Monokai theme is build using Allen Bargi's color scheme editor:
https://github.com/aziz/tmTheme-Editor
