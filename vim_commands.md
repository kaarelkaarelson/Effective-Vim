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

### Highlighting text

start highlighting text: `v` (after that you can move with `hjkl` keys)
highlight current line: `ctrl + v`
 
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

#### Refactoring
Change the number inside a variable: `Ctrl + a` -> turns `int start1` to `int start2` (might be intellij feature)
 
#### Joining
Join x lines together (meaning delete '\n' symbols from each of these lines): `{digit} + J`

![image](https://user-images.githubusercontent.com/90053205/196723942-0c99e27e-290f-4692-96c4-778b510dbe36.png)

![image](https://user-images.githubusercontent.com/90053205/196724539-0368b64a-d929-4ae1-841b-fbf97bb2bd0f.png)

(*Here command `5+j` was used*)





#### Undo

Undo a change: `u` -> `Ctrl + z`  

#### Paste

Paste a line: under `p` or before `P` (What is the difference? - lower case pastes under the line, uppercase before the line)

Highlight a line: `Shift + V`

