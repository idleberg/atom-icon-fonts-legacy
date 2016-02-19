# Icon Fonts for Atom

[![apm](https://img.shields.io/apm/l/icon-fonts-legacy.svg?style=flat-square)](https://atom.io/packages/icon-fonts-legacy)
[![apm](https://img.shields.io/apm/v/icon-fonts-legacy.svg?style=flat-square)](https://atom.io/packages/icon-fonts-legacy)
[![apm](https://img.shields.io/apm/dm/icon-fonts-legacy.svg?style=flat-square)](https://atom.io/packages/icon-fonts-legacy)
[![Travis](https://img.shields.io/travis/idleberg/atom-icon-fonts-legacy.svg?style=flat-square)](https://travis-ci.org/idleberg/atom-icon-fonts-legacy)
[![David](https://img.shields.io/david/dev/idleberg/atom-icon-fonts-legacy.svg?style=flat-square)](https://david-dm.org/idleberg/atom-icon-fonts-legacy#info=devDependencies)

Atom snippets for all icon fonts that have been removed from the [main package](https://atom.io/packages/icon-fonts) ([see details](#prefixes)).

## Installation

### apm

* Install package `apm install icon-fonts-legacy` (or use the GUI)

### GitHub

1. Change directory `cd ~/.atom/packages/`
2. Clone repository `git clone https://github.com/idleberg/atom-icon-fonts-legacy icon-fonts-legacy`

## Usage

Snippets are limited to the `.text.html` scope. Typing the class name of an icon using the designated prefix will complete to a tag containing the icon class.

### Prefixes

Prefix         | Icon Font                           | Version
---------------|-------------------------------------|--------
`filetypes`    | [Glyphicons Filetypes][filetypes]   | 1.9.0
`foundico`     | [Foundation Icons][foundico]        | 1.0.0
`glyphicons`   | [Glyphicons Pro][glyphicons]        | 1.9.0
`halflings`    | [Glyphicons Halflings][halflings]   | 1.9.0
`line`         | [Elegant Theme Line Icons][line]    | –
`social`       | [Glyphicons Social][social]         | 1.9.0

Examples:

* `foundicon-checkmark`+<kbd>Tab</kbd> completes to `<i class="foundicon-checkmark"></i>`
* `glyphicons-check`+<kbd>Tab</kbd> completes to `<span class="glyphicons glyphicons-check"></span>`
* well, you get the idea

## License

This work is licensed under the [The MIT License](LICENSE.md).

## Donate

You are welcome support this project using [Flattr](https://flattr.com/submit/auto?user_id=idleberg&url=https://github.com/idleberg/atom-icon-fonts-legacy) or Bitcoin `17CXJuPsmhuTzFV2k4RKYwpEHVjskJktRd`


[filetypes]: http://glyphicons.com
[foundico]: https://github.com/zurb/foundation-icons/tree/original-implementation
[glyphicons]: http://glyphicons.com
[halflings]: http://glyphicons.com
[line]: http://www.elegantthemes.com/blog/resources/how-to-use-and-embed-an-icon-font-on-your-website
[social]: http://glyphicons.com
