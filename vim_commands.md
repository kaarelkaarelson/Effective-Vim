## Vim commands for VSCode

### Visual mode (Normal mode)
Enter into insert mode: `i`

Enter into normal mode: `kj`

#### Navigation
Go to the next word: `w` (left-to-right)
Go to the first line of the file: `gg`

Go to the last line of the file: `Shift + g`

Go to the begginning of the current line: `0`

Go to the end of the current line: `$`

Undo tab: `Shift+tab` (tab manually allowed in the keybindings for VSCode)

Create a new line: under `o` or before `O`
 
#### Copying (yanking)
Copy a line: `yy` -> yank

Copy the current word: `yiw`

Copy everything from the cursor to the end of the line: `y$`

Copy everything from the cursor to the start of the line `y^`


#### Delete 
Delete a line: `dd`

Delete the selected word: `diw`

Delete a word after cursor: `dw`

Delete before on a line (the **back** of the line): `db`

Delete after a line (until the **end**): `de`

Delete {digit} number of lines after the current line: `{digit} + dd`

#### Undo

Undo a change: `u` -> `Ctrl + Z`  

#### Paste

Paste a line: under `p` or before `P` (What is the difference? - lower case pastes under the line, uppercase before the line)

Highlight a line: `Shift + V`

