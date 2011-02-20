tcom Allows Emacs as Editor for MS Outlook
==========================================

Introduction
------------

This is a github clone of 
[[tcom Allows Emacs as Editor for MS Outlook][http://wiki.tcl.tk/9198] with
some minor edits in order to make it easier for Emacs to locate the necessary
Tcl scripts.


Installation
------------

In order to use this extension you will have to install
[[http://www.activestate.com/Products/ActiveTcl/][ActiveTcl]] for Windows. You
will also need [[http://www.vex.net/~cthuang/tcom/][tcom]].

In order to avoid having to edit *outlookedit/outlookedit.el* Emacs expects to
find the Tcl scripts in *$HOME/.emacs.d/vendor/outlookedit*. Coincidentally
this is exactly how my personal
[[http://github.com/dholm/dotemacs/][Emacs setup]] is configured.

**NOTE:** I did not write outlookedit.el but simply providing this github
mirror of it to make it easier for users to add it to their Emacs
configurations.


Configured key-bindings
-----------------------
 * (C-c o e) Copy contents of currently open e-mail in Outlook to emacs
 * (C-c o s) Replace the contents of the currently open e-mail in outlook with
   the contents of your current Emacs buffer
