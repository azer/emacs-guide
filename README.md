This is an Emacs guide written for JavaScript coders. It'll cover installation, basic text editing to taking advantage 
of powerful extensions made for NodeJS and JavaScript.

### Setup

This guide will be based on `emacs.js`, a ready-to-use setup for JavaScript coders. Go to your home directory and follow these commands;

```
$ cd ~
$ git clone https://github.com/azer/emacs.js
$ cd emacs.js
$ make
```

Once you're done, you can start emacs by running:

```bash
$ emacs
```

### First Steps

Once you have Emacs open, press `C-x C-f` (Control-x Control-f) buttons to find a file to find a file to open. 
To create a new file, press `C-x C-f` again, type a filename and `enter`.

You should see an editing screen like following;

![](https://dl.dropboxusercontent.com/s/eb9xxqzwydl59fv/emacs-1.png)

### Movement

`emacs.js` comes with some new keybindings in addition to basic Emacs keybindings. For example, if you would like to jump to
a relative line number that you can see on the left of the frame, press UP or DOWN arrow buttons.

To jump to next line, press `C-n` (Control-n) and `C-p` keybindings. To jump to an absolute line number, press `M-g g` (Option/Alt-g g).
You can also press `C-v` and `M-v` to scroll up/down.

To move the cursor to next character, press `C-f`, to previous character `C-b`.

To go to end of a line, press `C-e`. To beginning of a line, `C-a`. 

### Editing

Type something new into your new document and press LEFT and RIGHT arrows. As you notice, LEFT button is binded to `undo`,
right button is binded to `redo` commands. You can also see the complete undo tree with undo-tree command by running `M-x undo-tree` (Option/Alt-x).

To delete the word next to the cursor, run `M-d` (Option/Alt-d), and `C-d` for deleting only one character.

To save your document, press `C-x C-s` (Control-x Control-s) buttons. 

### Creating Projects

`M-n n` (Option-n n)

### Creating Modules
### Creating HTML Files
### Debugging
### See Also
