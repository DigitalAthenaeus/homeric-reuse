# Git Instructions

## Overview

- Git software on your computer.
- Files on your computer, they are a "Git Repository". 
- **Before you edit(!!!)** you will *pull* any changes from GitHub.
- You will edit your files on your computer. You will save as you go along.
- You will *check in changes* to your Git Repository. 
- You can, from time to time, *push* your changes "up" to GitHub.

## Short Sequence

1. Pull.
1. Edit.
1. Commit.
1. Push.

## Specifics

1. Navigate to your Digital Athenaeus folder, via the Terminal:

    $ cd ~/Documents/DigitalAthenaeus [return]

1. Pull any changes

    $ git pull
	
1. Edit your document(s).

1. Commit your changes:

    $ git commit -m "Your message here." -a
	
1. Push your changes:

	$ git push

## If you forget the `-m` part of a `git commit`

- You will be dropped into `nano`, a CLI text-editor.
- Type your commit message.
- Type `control-O` (control-key, letter 'O'), to "write out" (i.e. "save").
- Hit return to confirm that you want to save that file.
- Type `control-X` to quit.	
	  
