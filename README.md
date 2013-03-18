# DefaultKeyBinding.dict

Default keybindings fix for Mac OS X

## Features

* Adds multiple sign shortcut: ×
	* `option - [`  = ×
* Modifies curly quotes shortcuts:
	* `control - [` = `“`
	* `control - ]` = `”`
*	`control - {` = `‘`
	* `control - }` = `’`
* Adds Chinese quote marks shortcuts
	* `option - [` = `「`
	* `option - ]` = `」`
	* `option - {` = `『`
	* `option - }` = `』`

## Installaion

### Method #1

```bash
user$ git clone git://github.com/sparanoid/DefaultKeyBinding.dict.git ~/Library/Keybindings/
````

### Method #3

```bash
user$ git clone git://github.com/sparanoid/DefaultKeyBinding.dict.git ~/my-git-repos/DefaultKeyBinding.dict
user$ ln -s ~/my-git-repos/DefaultKeyBinding.dict/DefaultKeyBinding.dict ~/Library/Keybindings/DefaultKeyBinding.dict
```

### Method #2
Download it and put DefaultKeyBinding file in:

	`~/Library/KeyBindings/`

## Usage

`"[keycombination]" = ("insertText:", "&#092;[unicodenumber or actual character]");`

	Prefix   Meaning
	~        ⌥ option key
	$        ⇧ shift key
	^        ^ control key
	@        ⌘ command key
	#        Keys on number pad

More information about keybinding syntax:
http://xahlee.info/kbd/osx_keybinding_key_syntax.html


Not familiar with codeing or need more complex keybinding modifications? Try this:
http://scripts.sil.org/ukelele

## Author

**Tunghsiao Liu**

+ http://twitter.com/tunghsiao
+ http://github.com/sparanoid
