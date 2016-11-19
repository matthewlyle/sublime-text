# Matt's Sublime Text Setup

This guide will walk through how I set [Sublime Text](https://www.sublimetext.com) up on all my machines.

![Screenshot](/screenshot.png.jpg?raw=true)

## Package Control
[Package Control](https://packagecontrol.io) allows you to install and manage packages directly from Sublime Text, and will be used to install everything following. Follow the very simple instructions on the website to get it installed, which can all be done directly in Sublime Text.

After it's installed, use `Shift + CMD + P` and then type _Package Control_ to see the available commands. __Install Package__ will be the most useful one for this guide.

## Material Theme
There are other themes that look nice but the [Material Theme](https://github.com/equinusocio/material-theme
) is by far my favourite and I use it on all my machines. Make sure to install the extra App Bar and White Inputs. All three can be installed via Package Control.

## Preferences
The following settings can be added to User Preferences to turn on the theme and make a lot of things more readable. The font I prefer is [Roboto Mono](https://fonts.google.com/specimen/Roboto+Mono).
```
{
	"color_scheme": "Packages/Material Theme/schemes/Material-Theme.tmTheme",
	"ensure_newline_at_eof_on_save": true,
	"folder_exclude_patterns":
	[
		".git",
		".sass-cache",
		"node_modules",
		"_site",
		".Trash"
	],
	"font_face": "Roboto Mono",
	"font_options":
	[
		"gray_antialias",
		"subpixel_antialias"
	],
	"font_size": 12,
	"ignored_packages":
	[
		"Vintage"
	],
	"indent_guide_options":
	[
		"draw_normal",
		"draw_active"
	],
	"line_padding_bottom": 3,
	"line_padding_top": 3,
	"material_theme_accent_red": true,
	"material_theme_appbar_red": true,
	"material_theme_tree_headings": true,
	"overlay_scroll_bars": "enabled",
	"theme": "Material-Theme.sublime-theme",
	"trim_trailing_white_space_on_save": true
}
```
## Plugins
I only use a few plugins, but I find them pretty integral. All of them can be installed via Package Control.

### Sidebar Controls
This should be included in Sublime Text. This plugin allows you to do Finder-like operations (e.g rename, move, open in browser) via right click.

### Emmett
[Emmett](http://emmet.io) let's you write HTML with CSS-inspired shorthand that can greatly improve any front-end developers workflow.

### Languages
Install support for whatever languages that you use that aren't included by default. For me right now that's Sass, Jade and Vue.

### PrettyJSON
JSON is very particular to how it's formatted and I'm too cool for all that so this lets you highlight a block of JSON and type `CTRL + CMD + J` to keep it perfect.

### Markdown Preview
When writing README's or blog posts it's nice to see what Markdown looks like before committing. This plugin lets you open up a preview in your browser by typing __HTML Markdown Preview__ in Package Control.

