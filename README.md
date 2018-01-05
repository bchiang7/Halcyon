# Halcyon Theme for Sublime Text

![demo](https://raw.githubusercontent.com/bchiang7/Halcyon/master/images/demo.png)

## Installation

1. Open package control `Tools` → `Command Palette` and type `Install Package`
2. Search for Halcyon and hit enter
3. Then, open `Preferences` → `Settings - User`. Add the following lines.
  ```json
  "color_scheme": "Packages/Halcyon/Halcyon.tmTheme",
  "theme": "Halcyon.sublime-theme"
  ```
4. Finally, restart Sublime for the Theme to be fully applied.

`color_scheme` defines how the code looks and `theme` defines how the sidebar, tabs, search, command palette work.

## Manual Installation

1. Clone or download this repo
1. Move the downloaded folder inside your sublime `Packages` directory. `Preferences > Browse packages...`
1. Then, open `Preferences` → `Settings - User`. Add the following lines.
  ```json
  "color_scheme": "Packages/Halcyon/Halcyon.tmTheme",
  "theme": "Halcyon.sublime-theme"
  ```
1. Finally, restart Sublime for the Theme to be fully applied.

## Options

### Sidebar Font Size

Change the sidebar's font size by using these settings in your user config:

```json
"sidebar_font_small": true
"sidebar_font_big": true
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

## Colors

![colors](https://raw.githubusercontent.com/bchiang7/Halcyon/master/images/colors.png)

Theme Background `#191e27`

Editor Background `#212733`

Accent Yellow `#ffcc66`

Accent Grey `#738699`

White `#d9d7ce`

Blue `#5ccfe6`

Green `#bae67e`

Orange `#ffae57`

Yellow `#ffd580`

Purple `#c3a6ff`

Red `#f07178`

Grey `#abb2bf`

Dark Grey `#607080`

Seafoam `#95e6cb`

## Sublime User Settings

``` json
{
  "always_show_minimap_viewport": true,
  "bold_folder_labels": true,
  "caret_extra_bottom": 2,
  "caret_extra_top": 2,
  "caret_extra_width": 0,
  "caret_style": "phase",
  "color_scheme": "Packages/Halcyon/halcyon.tmTheme",
  "drag_text": false,
  "draw_minimap_border": true,
  "draw_shadows": false,
  "draw_white_space": "selection",
  "ensure_newline_at_eof_on_save": true,
  "fade_fold_buttons": false,
  "find_selected_text": true,
  "font_face": "Inconsolata",
  "font_options":
  [
    "subpixel_antialias"
  ],
  "font_size": 14,
  "highlight_line": true,
  "highlight_modified_tabs": true,
  "ignored_packages":
  [
    "Vintage"
  ],
  "indent_guide_options":
  [
    "draw_normal",
    "draw_active"
  ],
  "line_padding_bottom": 2,
  "line_padding_top": 2,
  "material_theme_compact_panel": true,
  "material_theme_compact_sidebar": true,
  "material_theme_tabs_autowidth": true,
  "original_color_scheme": "Packages/Color Scheme - Default/Monokai.tmTheme",
  "overlay_scroll_bars": "enabled",
  "scroll_past_end": true,
  "scroll_speed": 5.0,
  "show_full_path": true,
  "show_line_endings": true,
  "spell_check": false,
  "tab_size": 2,
  "theme": "halcyon.sublime-theme",
  "translate_tabs_to_spaces": true,
  "trim_trailing_white_space_on_save": true,
  "use_simple_full_screen": true,
  "word_wrap": true,
  "wrap_width": 80
}
```

## Reference

[Sublime UI Theme Reference](https://www.sublimetext.com/docs/3/themes.html)

[Sublime Color Scheme Reference](http://docs.sublimetext.info/en/latest/reference/color_schemes.html)

[Sublime Scope Naming](https://www.sublimetext.com/docs/3/scope_naming.html)

Colors based on [Ayu Mirage Theme](https://github.com/dempfi/ayu)
