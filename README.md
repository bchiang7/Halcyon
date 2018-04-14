# Halcyon Theme for Sublime Text

![demo](https://raw.githubusercontent.com/bchiang7/Halcyon/master/images/demo.png)

## Installation

### Package Control

1.  Open package control `Tools` → `Command Palette` and type `Install Package`
2.  Search for Halcyon and hit enter
3.  Then, open `Preferences` → `Settings - User`. Add the following lines.

```json
"color_scheme": "Packages/Halcyon Theme/halcyon.tmTheme",
"theme": "halcyon.sublime-theme"
```

4.  Finally, restart Sublime for the Theme to be fully applied.

`color_scheme` defines how the code looks and `theme` defines how the sidebar, tabs, search, command palette work.

### Manual Installation

1.  Clone or download this repo

    `git clone git@github.com:bchiang7/Halcyon.git Halcyon\ Theme`

1.  Make sure the downloaded folder is named `Halcyon Theme`. Don't forget the space!
1.  Move the `Halcyon Theme` folder inside your sublime `Packages` directory. `Preferences > Browse packages...`
1.  Then, open `Preferences` → `Settings - User`. Add the following lines.

```json
"color_scheme": "Packages/Halcyon Theme/halcyon.tmTheme",
"theme": "halcyon.sublime-theme"
```

1.  Finally, restart Sublime for the theme to be fully applied.

## Options

### Sidebar Font Size

Change the sidebar's font size by using these settings in your user config:

```json
"sidebar_font_small": true
"sidebar_font_large": true
```

### Sidebar Padding

Adjust the sidebar's padding by using these settings in your user config:

```json
"sidebar_small": true
"sidebar_large": true
```

### Tab Size

Change the size of the tabs by using these settings in your user config:

```json
"tabs_small": true
"tabs_large": true
```

## Reference

[Sublime UI Theme Reference](https://www.sublimetext.com/docs/3/themes.html)

[Sublime Color Scheme Reference](http://docs.sublimetext.info/en/latest/reference/color_schemes.html)

[Sublime Scope Naming](https://www.sublimetext.com/docs/3/scope_naming.html)

Colors based on [Ayu Mirage Theme](https://github.com/dempfi/ayu)

## Shameless Plug

Halcyon is also available for Atom, VS Code, iTerm, and more! Check out all available options [here](https://brittanychiang.com/halcyon-site/).
