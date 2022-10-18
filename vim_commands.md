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

Create a new line under: `o`

#### Copying (yanking)
Copy a line: `yy` -> yank

Copy the current word: `yiw`

Copy everything from the cursor to the end of the line: `y$`

Copy everything from the cursor to the start of the line `y^`
#### Delete 
Delete a line: `dd`

Delete a word: `dw`

Delete before on a line (the **back** of the line): `db`

Delete after a line (until the **end**): `de`

Delete {digit} number of lines after the current line: `{digit} + dd`

#### Undo

Undo a change: `u` -> `Ctrl + Z`  

#### PPste

Paste a line: `p` or `Ctrl + P` (What is the difference?)

Highlight a line: `Shift + V`

