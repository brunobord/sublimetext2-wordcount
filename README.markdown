# SublimeText2 Word Count Plugin

## What is it?

This is probably the simplest and dumbiest plugin for Sublimetext2. It simply
counts words and characters out of the current document.

## Install and Use

Simply grab the `word_count.py` file and copy it in your Plugins/User directory.

From the ST2 console (Ctrl+`), simply type:

    view.run_command('word_count')

You may want to be able to run this with a keyboard shortcut, so you can add
this to your "Key Binding - User" file:

    { "keys": ["alt+c"], "command": "word_count"}
