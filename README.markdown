# vim-colors-pencil

> A light (and dark) color scheme for Vim inspired by iA Writer

![markdown-example](screenshots/markdown-example2.png)

## Features

iA Writer is an elegant word processor, marred only by its lack of Vim. It
does have a nice color scheme, however.

The _pencil_ color scheme features: 

* Subtle indicators of changes in the gutter for Signify, git-gutter, etc.
* Use for both code and prose, though it’s definitely geared towards the latter
* Light and dark variants
* iTerm color scheme [available][it] for using this color scheme with terminal-based Vim
* Support for [tpope/vim-markdown][tm] and [plasticboy/vim-markdown][pm]

[tm]: http://github.com/tpope/vim-markdown
[pm]: http://github.com/plasticboy/vim-markdown

## Requirements

Currently requires vim >= 7.0

## Installation

Install using Pathogen, Vundle, Neobundle, or your favorite Vim package
manager.

Or simply copy the color scheme file to your `~/.vim/colors` directory.

## Configuration

### Contrast

If you’re looking for greater contrast, set the following in your
`.vimrc`:

```
let g:pencil_higher_contrast_ui = 0   " 0=low (def), 1=high
```

It currently only affects the blacks and grays.

### Headings color

Most notably, the ‘#’ heading text is shaded dark blue by default. This
compensates for the lack of a visual cue found in iA Writer where the
heading indicators are inside the left margin. 

If you’re looking for neutral heading colors, set the following in your
`.vimrc`:

```
let g:pencil_neutral_headings = 1   " 0=blue (def), 1=normal
```

### Parentheses matching

Those users who find the parentheses matching disconcerting can disable
this default Vim plugin in their `.vimrc` with:

```
let loaded_matchparen = 1
```

See `:help pi_paren.txt` for more details. 

## Usage

Just like any other color scheme:

```vim
:colorscheme pencil
```

You can toggle between the light and dark variants:

```vim
:set background=dark
:set background=light
```

## Font choices

iA Writer uses a typeface called ‘Nitti Light’ by Blue Monday. ($)

Free alternatives with **bold** and _italic_ support include:

* [Anonymous Pro](https://www.google.com/fonts/specimen/Anonymous+Pro) (serif)
* [Courier Prime](http://quoteunquoteapps.com/courierprime/) (serif)
* [Cousine](http://www.google.com/fonts/specimen/Cousine)
* [DejaVu Sans Mono](http://dejavu-fonts.org/wiki/Download)
* [Liberation](https://fedorahosted.org/liberation-fonts/)
* [Luxi Mono Regular](http://www.fontsquirrel.com/fonts/Luxi-Mono) (serif)
* [Ubuntu Mono](https://www.google.com/fonts/specimen/Ubuntu+Mono)

Cousine is a good match for Nitti Light.

## See also

* [mattly/iterm-colors-pencil][it] - iTerm support for terminal-based use of the pencil color scheme
* [mattly/atom-colors-pencil-light][ap] - Atom verson of the pencil color scheme
* [pencil color scheme at vim.org][vo]

[ap]: https://github.com/mattly/atom-colors-pencil-light
[it]: https://github.com/mattly/iterm-colors-pencil
[vo]: http://www.vim.org/scripts/script.php?script_id=4850

If you find this colorscheme useful, you may want to check out these
plugins by [@reedes][re]:

* [vim-lexical][lx] - building on Vim’s spell-check and thesaurus/dictionary completion
* [vim-litecorrect][lc] - lightweight auto-correction for Vim
* [vim-one][vo] - make use of Vim’s _+clientserver_ capabilities 
* [vim-pencil][pn] - rethinking Vim as a tool for writers
* [vim-textobj-quote][qu] - extends Vim to support typographic (‘curly’) quotes
* [vim-textobj-sentence][ts] - improving on Vim's native sentence motion command
* [vim-thematic][th] - modify Vim’s appearance to suit your task and environment 
* [vim-wheel][wh] - screen-anchored cursor movement for Vim
* [vim-wordy][wo] - uncovering usage problems in writing 

[re]: https://github.com/reedes
[lx]: http://github.com/reedes/vim-lexical
[lc]: http://github.com/reedes/vim-litecorrect
[vo]: http://github.com/reedes/vim-one
[pn]: http://github.com/reedes/vim-pencil
[ts]: http://github.com/reedes/vim-textobj-sentence
[qu]: http://github.com/reedes/vim-textobj-quote
[th]: http://github.com/reedes/vim-thematic
[wh]: http://github.com/reedes/vim-wheel
[wo]: http://github.com/reedes/vim-wordy

The [README](https://github.com/reedes/vim-thematic) in
_thematic_ has more details on setting up emulation of iA Writer.

## Future development

If you’ve spotted a problem or have an idea on improving this color
scheme, please post it to the github project issue page.

<!-- vim: set tw=74 :-->
