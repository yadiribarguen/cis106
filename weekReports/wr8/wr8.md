---
name: yadir ibarguen
class: cis106
semester: fall 2023
---

# week report 8

## What is VIM?
Vim is a text editor for Unix that comes with Linux, BSD, and macOS. It is known to be fast and powerful, partly because it is a small program that can run in a terminal. It is mainly used because it can be managed entirely without menus or a mouse with a keyboard.

## What is nano? 
Nano is a text editor for Unix-like computing systems or operating environments using a command line interface. It emulates the Pico text editor, part of the Pine email client, and also provides additional functionality.


## Describe in your own words how to:

* Start and quit vim
to start up vim you enter the word vim into the terminal, this will cause vim to open and to quit vim you simply type `:q!`

* What are the different vim modes:
  * insert mode: used for writing text
  * normal mode: used for manipulating text
  * command mode: used for entering vim commands
  * visual mode: used for navigating and manipulation of text selections
  * select mode: similar to visual mode
  * ex-mode: similar to the command-line mode but optimized for batch processing

* Insert text in vim
* to insert text you open vim and press the letter i this will start insert mode allowing you to insert text

* Save a file in vim
there are a few ways to save text in vim you can use:
  * :w- this will save the file
  * :w new.txt- will save the file as new.txt
  * :wq- will save the file and quit
  * :wqa!- will save the file and close all the files open in the buffer

* Search for a word inside vim
to search for words you have a few options such as:
  * /word you are searching; you type the forward slash and the word you want to search and it will search forward
  * n: will repeat the search for the next word
  * ?: will search backwards
  * (*) will search for the next occurrence of the word under the cursor
  * (#) will search backward for the previous occurrence of the word under the cursor


* Delete text in vim
commands for deleting text in vim:
  * dw- delete current word
  * u- undo
  * dd- delete line under the cursor
  * d + /word- delete until the word given
  * x- for cut

