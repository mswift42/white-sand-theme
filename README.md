# white-sand-theme
Emacs 24 theme with a light background.


Created with [Emacs Theme Creator](http://emacs-theme-creator.appspot.com).

Screenshots:
------------

Code samples of Elisp and Python:

![Screenshot](https://github.com/mswift42/white-sand-theme/raw/master/white-sand-elispandpython.png)

Javascript and Org-mode sample:

![Screenshot](https://github.com/mswift42/white-sand-theme/raw/master/white-sand-jsandorg.png)

Go and Java sample:

![Screenshot](https://github.com/mswift42/white-sand-theme/raw/master/white-sand-goandjava.png)


The font used in the screenshots is [Ubuntu Mono](http://font.ubuntu.com/).

Weather data can be displayed in an agenda buffer using [weather-metno.el](https://github.com/ruediger/weather-metno-el).

* * * 

Available on Melpa.

Installation Instructions
-------------------------

add the following lines to your init.el (only if you have not done so already):

    (setq package-archives '(("gnu" . "http://elpa.gnu.org/packages/")
                             ("melpa" . "http://melpa.org/packages/")))
    (package-initialize)



This will add the gnu and melpa repos to your emacs setup.

To install the theme:

**M-x package-install** white-sand-theme


To use the white-sand theme when starting emacs, add this to your init.el:

    (load-theme 'white-sand)
