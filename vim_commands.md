# Vim Commands 

-

## Visual mode (Normal mode)
Enter into insert mode: `i`

Enter into normal mode: `jj`

### Navigation
Go to the next word: `w` (left-to-right)

Go back to the last word: `b` (right to left)

Go to the begginning of the current line: `0`

Go to the end of the current line: `$`

Go to the character {x} after cursor on the current line: `f + {x}`

Go to the first line of the file: `gg`

Go to the last line of the file: `Shift + g`

Undo tab: `Shift+tab` (tab manually allowed in the keybindings for VSCode)

Create a new line: under `o` or before `O`

Go to the declaration of the method: `gd` (if interface method then goes to the interface class)
 - return back from the declaration method `Ctrl + o`

Go to the implementations of the method: `Ctrl + b`

Go to line {n} (relative line number): `{n} + k` or `{n} + j`

## Highlighting text

start highlighting text: `v` (after that you can move with `hjkl` keys)

highlight current line: `ctrl + v`
 
### Copying (yanking)
Copy a line: `yy` -> yank

Copy the current word: `yiw`

Copy everything from the cursor to the end of the line: `y$`

Copy everything from the cursor to the start of the line `y^`




### Delete 
Delete a line: `dd`

Delete the character: `x`

Delete the selected word: `diw`

Delete a word after cursor: `dw`

Delet upto symbol horizontally {x}: `dt + {x}`

Delete before on a line (the **back** of the line): `db`

Delete after a line (until the **end**): `de`

Delete {n} lines down: `{n} + dd`

Delete {n} lines up: `{n} + dk`

### Refactoring
Change the number inside a variable: `Ctrl + a` -> turns `int start1` to `int start2` (might be intellij feature)
 
### Joining and separatiing code lines
Join current line and line below together: `Shift + j`
Put empty line between current line and line below: `Shift + k`
Join x lines together (meaning delete '\n' symbols from each of these lines): `{digit} + J`

![image](https://user-images.githubusercontent.com/90053205/196723942-0c99e27e-290f-4692-96c4-778b510dbe36.png)

![image](https://user-images.githubusercontent.com/90053205/196724539-0368b64a-d929-4ae1-841b-fbf97bb2bd0f.png)

(*Here command `5+j` was used*)




### Undo

Undo a change: `u` -> `Ctrl + z`  

### Paste

Paste a line: under `p` or before `P` (What is the difference? - lower case pastes under the line, uppercase before the line)

Highlight a line: `Shift + V`

-

## Visual Block Mode

### Editing multiple lines

Edit vertically aligned text: `V` -> then select desired lines with `hjkl` -> go into insert mode `I` (good for inserting spaces and tabs for identation)

Add text to vertically aligned code: Enter Visual Block Mode and select desired lines -> go into insert mode `I` -> type the text that you want to insert on the initial line -> `press <Esc>` (... and boom, all your lines are edited).

Replace vertically aligned text:  Enter Visual Block Mode and select desired lines and text -> press `c` -> type the text that you want to insert on the initial line -> `press <Esc>` (all the selected lines will update as well).

## Command line
Change all occurances: Type to command line -> `:%s/foo/bar/g` wherer foo is the word you want to change, and bar is the replaced word.
