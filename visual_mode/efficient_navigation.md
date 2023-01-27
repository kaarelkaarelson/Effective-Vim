# Efficient Navigation

## Vertical

Go to the start of next/last paragraph: `{` and `}`

Go to line {n} (relative line number): `{n} + k` or `{n} + j` 

Go to line {n} (absolute line number): `{n} + G`

Go to the first line of the file: `gg`

Go to the last line of the file: `Shift + g`

Create a new line: under `o` or before `O`


## Horizontal

Go to the next word: `w` (left-to-right)

Go back to the last word: `b` (right to left)

Go to the beginning of the current line: `0`

Go to the end of the current line: `$`

Go to the character {x} after cursor on the current line: `f + {x}`

Undo tab: `Shift+tab` (tab manually allowed in the keybindings for VSCode)



## File structure (aka teleporting)

Go to the declaration of the method: `gd` (if interface method then goes to the interface class)
 - return back from the declaration method `Ctrl + o`

Go to the implementations of the method: `Ctrl + b`
