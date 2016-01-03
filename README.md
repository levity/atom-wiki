# wiki

A personal wiki package for Atom. Forked from [Awiki](https://github.com/Dessyreqt/awiki), but makes some significantly different design choices.

## Features

### Index page

It supports only one wiki, which can be specified in the settings page. Pressing `alt-w` will open your wiki's index location. This can also be accessed from the main menu under "Packages/Wiki/Open Wiki Index"

### Links

Links are created by surrounding a word with square brackets like so:
```
[Link to another wiki page]
```
This can be done automatically by pressing `alt-enter` on a word or a selection.

You can follow this link by putting the cursor on the link and hitting `alt-enter`. You can also follow it by right-clicking on it and selecting "Open/Create Wiki Link".

You can navigate back to the previous page by pressing `shift-alt-backspace`.

### Markdown

The grammar of wiki pages is a superset of [Github Flavored Markdown](https://github.com/atom/language-gfm).
