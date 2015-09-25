# Winamp Skin Developer

[![The MIT License](https://img.shields.io/badge/license-MIT-orange.svg?style=flat-square)](http://opensource.org/licenses/MIT)
[![GitHub release](https://img.shields.io/github/release/idleberg/Winamp-Skin-Dev-Sublime-Text.svg?style=flat-square)](https://github.com/idleberg/Winamp-Skin-Dev-Sublime-Text/releases)
[![Travis](https://img.shields.io/travis/idleberg/Winamp-Skin-Dev-Sublime-Text.svg?style=flat-square)](https://travis-ci.org/idleberg/Winamp-Skin-Dev-Sublime-Text)

[Sublime Text](http://www.sublimetext.com/) syntax completions and snippets for [Winamp](http://winamp.com) skin developers, supporting both Classic and Modern skins.

## Installation

### Package Control

1. Make sure you already have [Package Control](https://packagecontrol.io/) installed
2. Choose “*Install Package*” from the Command Palette (<kbd>Super</kbd>+<kbd>Shift</kbd>+<kbd>p</kbd>)
3. Type “*Winamp Skin Developer*” and press <kbd>Enter</kbd>

### GitHub

1. Change to your Sublime Text `Packages` directory
2. Clone repository `git clone https://github.com/idleberg/Winamp-Skin-Dev-Sublime-Text.git 'Winamp Skin Developer'`

### Manual installation

1. Download the latest [stable release](https://github.com/idleberg/Winamp-Skin-Dev-Sublime-Text/releases)
2. Unzip the archive to your Sublime Text `Packages` directory

## Usage

### Completions

Start typing any XML tag or property, then hit the `Tab` key to complete it. Since by default the completion pop-up shows up only for the `source` scope , there are two options to make use of it:

1. Press `Ctrl+Space` to force showing the completion pop-up
2. Add the appropriate scopes (`text.plain` for classic and `text.xml`for modern skins) to the `auto_complete_selector` user setting

Also included are completions for colors in RGB and hexadecimal format, all [CSS3 colors](http://www.w3.org/TR/css3-color/) will be completed to the respective format.

### Snippets

This package currently includes three scaffolding snippets for developers of Classic Skins. To trigger these use the `ClassicSkin`-prefix and select a configuration file you want to create (`pledit.txt`, `region.txt`, or `viscolor.txt`)

## License

This work is licensed under the [The MIT License](LICENSE).

## Donate

You are welcome support this project using [Flattr](https://flattr.com/submit/auto?user_id=idleberg&url=https://github.com/idleberg/Winamp-Skin-Dev-Sublime-Text) or Bitcoin `17CXJuPsmhuTzFV2k4RKYwpEHVjskJktRd`