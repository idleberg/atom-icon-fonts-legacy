# Icon Fonts (Legacy) for Atom

[![apm](https://img.shields.io/apm/l/icon-fonts-legacy.svg?style=flat-square)](https://atom.io/packages/icon-fonts-legacy)
[![apm](https://img.shields.io/apm/v/icon-fonts-legacy.svg?style=flat-square)](https://atom.io/packages/icon-fonts-legacy)
[![apm](https://img.shields.io/apm/dm/icon-fonts-legacy.svg?style=flat-square)](https://atom.io/packages/icon-fonts-legacy)
[![CircleCI](https://flat.badgen.net/circleci/github/idleberg/atom-icon-fonts-legacy)](https://circleci.com/gh/idleberg/atom-icon-fonts-legacy)

Snippets for icon fonts that have been deprecated from the main [Icon Fonts](https://github.com/idleberg/atom-icon-fonts) package ([see details](https://github.com/idleberg/atom-icon-fonts-legacy#prefixes)).

This package is also available for [Sublime Text](https://github.com/idleberg/sublime-icon-fonts-legacy) and [Visual Studio Code](https://github.com/idleberg/vscode-icon-fonts-legacy).

## Installation

### apm

* Install package `apm install icon-fonts-legacy` (or use the GUI)

### Using Git

1. Change directory `cd ~/.atom/packages/`
2. Clone repository `git clone https://github.com/idleberg/atom-icon-fonts-legacy icon-fonts-legacy`

## Usage

Snippets are limited to the `.text.html`, `source.(css|less|sass|scss|stylus)` and `.source.js.jsx` scope. Typing the class name of an icon using the designated prefix will complete to a tag containing the icon class.

### Prefixes

| Prefix         | Icon Font                           | Version |
|----------------|-------------------------------------|---------|
| `brandico`     | [Brandico Font][brandico]           | –       |
| `fi`           | [Foundation Icons v3][fi]           | 3.0     |
| `filetypes`    | [Glyphicons Filetypes][filetypes]   | 1.9.0   |
| `fa`           | [Font Awesome][fontawesome]         | 4.7.0   |
| `foundico`     | [Foundation Icons][foundico]        | 1.0.0   |
| `geomicon`     | [Geomicons Open][geomicon]          | 2.0.0   |
| `glyphicons`   | [Glyphicons Pro][glyphicons]        | 1.9.0   |
| `halflings`    | [Glyphicons Halflings][halflings]   | 1.9.0   |
| `icofont`      | [ShapeBootstrap IcoFont][icofont]   | 1.0.0b  |
| `line`         | [Elegant Theme Line Icons][line]    | –       |
| `social`       | [Glyphicons Social][social]         | 1.9.0   |
| `ratchicon`    | [Ratchicons][ratchicon]             | 2.0.2   |
| `ui`           | [Semantic UI Icons][ui]             | 2.0.7   |

Examples:

* `foundicon-checkmark`+<kbd>Tab</kbd> completes to `<i class="foundicon-checkmark"></i>`
* `glyphicons-check`+<kbd>Tab</kbd> completes to `<span class="glyphicons glyphicons-check"></span>`
* well, you get the idea

## License

This work is licensed under the [The MIT License](LICENSE.md).

[brandico]: https://github.com/fontello/brandico.font
[fi]: https://github.com/zurb/foundation-icons
[filetypes]: http://glyphicons.com
[fontawesome]: https://fontawesome.com
[foundico]: https://github.com/zurb/foundation-icons/tree/original-implementation
[geomicon]: https://github.com/jxnblk/geomicons-open
[glyphicons]: http://glyphicons.com
[halflings]: http://glyphicons.com
[icofont]: http://icofont.com/
[line]: https://www.elegantthemes.com/blog/resources/elegant-icon-font
[ratchicon]: http://github.com/twbs/ratchet
[social]: http://glyphicons.com
[ui]: http://semantic-ui.com/elements/icon.html
