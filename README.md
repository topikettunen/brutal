## About

Brutal theme for Emacs for all your minimalistic needs.

![Brutal](https://raw.githubusercontent.com/topikettunen/brutal-emacs/master/img/brutal.png)

- Note: I'm using bold in my font face, which is not on by default in the theme.

## Installation

At the time of writing this theme is not available in Melpa yet. So at the
moment best way to install this theme is to copy it to your `.emacs.d`. I use
`themes` directory for holding this so I can load it with:

``` elisp
(add-to-list 'custom-theme-load-path "~/.emacs.d/themes")
(load-theme 'brutal t)
```
