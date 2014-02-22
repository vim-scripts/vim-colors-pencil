# vim-colors-pencil

> A light (and dark) color scheme for Vim inspired by iA Writer

![markdown-example](screenshots/markdown-example.png)

## Features

iA Writer is an elegant word processor, marred only by its lack of Vim. It
does have a nice colorscheme, however.

* Accurate colors
* Subtle indicators of changes in the gutter for Signify, git-gutter, etc.
* Use for both code and prose, though it’s definitely geared towards the
  latter
* Light and dark variants

## Requirements

Currently requires vim >= 7.0

## Installation

Install using Pathogen, Vundle, Neobundle, or your favorite Vim package
manager.

Or simply copy the colorscheme file to your `~/.vim/colors` directory.

## Usage

Just like any other colorscheme:

```vim
:colorscheme pencil
```

There is a work-in-progress dark version, just set your background:

```vim
:set background=dark
```

## Differences

Most notably, the ‘#’ heading text is shaded blue. This compensates for
the lack of a visual cue found in iA Writer where the heading indicators
are inside the left margin. Here we use color instead.

## Font choices

iA Writer uses a typeface called ‘Nitti Light’ by Blue Monday. ($)

Free alternatives with bold and italic support include:

* [Anonymous Pro](https://www.google.com/fonts/specimen/Anonymous+Pro) (serif)
* [Courier Prime](http://quoteunquoteapps.com/courierprime/) (serif)
* [Cousine](http://www.google.com/fonts/specimen/Cousine)
* [DejaVu Sans Mono](http://dejavu-fonts.org/wiki/Download)
* [Liberation](https://fedorahosted.org/liberation-fonts/)
* [Luxi Mono Regular](http://www.fontsquirrel.com/fonts/Luxi-Mono) (serif)
* [Ubuntu Mono](https://www.google.com/fonts/specimen/Ubuntu+Mono)

Cousine is a good match for Nitti Light.

## See also

* [iterm-colors-pencil][ip] - [@mattly][mt] has created an iTerm color scheme for pencil

[mt]: https://github.com/mattly
[ip]: https://github.com/mattly/iterm-colors-pencil

If you find this plugin useful, you may want to check out these others by
[@reedes][re]:

* [vim-lexical][lx] - building on Vim’s spell-check and thesaurus/dictionary completion
* [vim-litecorrect][lc] - lightweight auto-correction for Vim
* [vim-pencil][pn] - rethinking Vim as a tool for writers
* [vim-quotable][qu] - extends Vim to support typographic (‘curly’) quotes
* [vim-textobj-sentence][ts] - improving on Vim's native sentence motion command
* [vim-thematic][th] — modify Vim’s appearance to suit your task and environment 
* [vim-wheel][wh] - screen-anchored cursor movement for Vim
* [vim-wordy][wo] - uncovering usage problems in writing 

[re]: https://github.com/reedes
[lx]: http://github.com/reedes/vim-lexical
[lc]: http://github.com/reedes/vim-litecorrect
[pn]: http://github.com/reedes/vim-pencil
[qu]: http://github.com/reedes/vim-quotable
[ts]: http://github.com/reedes/vim-textobj-sentence
[th]: http://github.com/reedes/vim-thematic
[wh]: http://github.com/reedes/vim-wheel
[wo]: http://github.com/reedes/vim-wordy

The [README](https://github.com/reedes/vim-thematic) in
_thematic_ has more details on setting up emulation of iA Writer.

## Future development

If you’ve spotted a problem or have an idea on improving this color
scheme, please post it to the github project issue page.

<!-- vim: set tw=74 :-->
