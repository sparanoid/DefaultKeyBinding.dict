# DefaultKeyBinding.dict

Default keybindings fix for Mac OS X

## Features

* Adds multiple sign shortkey:
	* `control - shift - 8`  = `×`
* Adds deographic space shortkey:
	* `control - shift - space`  = `　`
* Modifies curly quotes shortkeys:
	* `control - [` = `“`
	* `control - ]` = `”`
	* `control - {` = `‘`
	* `control - }` = `’`
* Adds Chinese quotation marks shortkeys:
	* `option - [` = `「`
	* `option - ]` = `」`
	* `option - {` = `『`
	* `option - }` = `』`

## Installation

Don’t symlink this file to `Keybindings` folder, it [doens’t work](http://apple.stackexchange.com/questions/53066/textedit-key-bindings-in-lion).

### Method #1

```bash
$ git clone git://github.com/sparanoid/DefaultKeyBinding.dict.git ~/my-git-repos/DefaultKeyBinding.dict
$ cp ~/my-git-repos/DefaultKeyBinding.dict/DefaultKeyBinding.dict ~/Library/Keybindings/DefaultKeyBinding.dict
```

### Method #2
Download it and put DefaultKeyBinding file in:

	~/Library/KeyBindings/

## Syntax

`"[keycombination]" = ("insertText:", "&#092;[unicodenumber or actual character]");`

	Prefix   Meaning
	~        ⌥ option key
	$        ⇧ shift key
	^        ^ control key
	@        ⌘ command key
	#        Keys on number pad

More information about keybinding syntax:
http://xahlee.info/kbd/osx_keybinding_key_syntax.html


Not familiar with coding or need more complex keybinding modifications? Try this:
http://scripts.sil.org/ukelele

## Known Issues

* Ideographic space fix doens’t work when Google Chrome is running. (Tested on Mac OS X 10.8.3)

## Author

**Tunghsiao Liu**

+ http://twitter.com/tunghsiao
+ http://github.com/sparanoid
