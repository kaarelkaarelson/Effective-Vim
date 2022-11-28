# Search and Replace in Vim

**To use those commands you need to enter the command mode -> `:`**

## Commands

Change each 'foo' to 'bar' in the current line. `:s/foo/bar/g`	

Change each 'foo' to 'bar' in all the lines. `:%s/foo/bar/g`

Change each 'foo' to 'bar' for all lines from line 5 to line 12 (inclusive). `:5,12s/foo/bar/g`

Change each 'foo' to 'bar', but ask for confirmation first. `:%s/foo/bar/gc`

Change each 'foo' to 'bar' for all lines within a visual selection. `:'<,'>s/foo/bar/g` *Vim automatically appends the visual selection range ('<,'>)*. 

Resource: https://vim.fandom.com/wiki/Search_and_replace
