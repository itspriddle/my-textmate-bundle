# Josh's TextMate Bundle

This bundle includes a few TextMate snippets/commands I've collected.


## Snippets

* `head` (JavaScript or PHP) expands into a comment header for JS/PHP files.

* `--` (JavaScript or PHP) expands into:
  `// --------------------------------------------------------------------`

* `gradient` (CSS) expands into an Internet Explorer, Safari, and Firefox
   friendly CSS-Gradient syntax (and falls back gracefully, from
   [kneath's bundle](http://github.com/kneath/textmate-snippets/))

* `reset` (CSS) expands into a CSS reset I use frequently.

* `clear` (CSS) expands into a set of CSS rules I use for clearing elements.

* `footer` (Javascript or PHP) expands into a comment footer for JS/PHP files.

## Commands

* **&#8984;+S** Strips whitespace and saves document. Doesn't seem to work
  with bundles that include their own **&#8984;+S** command. If you know how
  to fix that and send me a pull request, you'll be my hero.


## Installation

    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone http://github.com/itspriddle/my-textmate-bundle.git Josh\'s\ Bundle.tmbundle

