---
layout: post
title: "emacs-notes"
---

While I am going to starting working on bitstarter, I will take notes on emacs commands I use while working for I can find them again later.

To work with multiple files:
* to open a file in new buffer `C-x C-f`
* to switch between buffers: `C-x b` then `enter` 

Copy and Pasting:

* To cut the text, press `C-w` 

* To copy the text, press `M-w` 

* To paste the text, press `C-y`

Spell Checker:

On a blank AWS ubuntu machine there is apparently no spell checker. So you need to install one with

* `sudo apt-get install aspell`:

Then you need to put it into emacs with:

* `(setq-default ispell-program-name "aspell")`

Then make sure to exit and come back.

Find and Replace:

* Press `M-x`
* Then type `replace-string`
* Then `your_search_string`
* Then `your_replace_string` 
