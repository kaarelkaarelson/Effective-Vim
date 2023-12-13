# Vim

This is a vim guide for most essential functionalities to save you the most time. 

It assumes no need for .vimrc file and can be followed on any vanilla vim system e.g. Overleaf or Google Colab. 

Currently, the project is grouped by different usages. 

## Enter for different modes

***Visual-block mode***: `<Ctrl> + v`

## Replace

Replace all occurrences in the document
1. Replace the words using the command line `:%s/old-word/new-word/g`

Replace all occurrences in the highlighted text.

1. Select lines with *visual-block mode*
2. Replace the words using the command line `:'<,'>s/old-word/new-word/`
