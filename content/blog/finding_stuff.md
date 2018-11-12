---
title: "How to find files by content under *nix."
date: 2018-10-12T18:23:22
---

Схоже, що це найпотрібніша інформація. Цей пост я перепощую вже третій раз. Треба буде цю інформацію інтегрувати у попередній пост про шпаргалку команд у лінуксі. 

А поки насолджуйтеся окремим постом.

**grep** command : print lines matching a pattern. 

**find** command: search for files in a directory hierarchy.

## grep command to find files by content

Type the command as follows:

*grep 'string' \*.txt*

*grep 'main(' \*.c*

*grep '#include<example.h>' \*.c*

*grep 'getChar\*'\*.c*

*grep -i 'ultra' \*.conf*

*grep -iR 'ultra' \*.conf*

Where *-i*: Ignore case distinctions in both the PATTERN (match valid, VALID,  ValID string) and the input files (math file.c FILE.c FILE.C filename).

*-R*: Read all files under each directory, recursively

## Highlighting searched patterns


You can highlight patterns easily while searching large number of files:

*$ grep --color=auto -iR 'getChar();' \*.c*

You may also need to display filenames and numbers:

*$ grep --color=auto -iRnH 'getChar();' \*.c*

Where *-n*: Prefix each line of output with the 1-based line number within its input file.

*-H*: Print the file name for each match. This is the default when there is more than one file to search.

*$ grep --color=auto -nH 'DIR' ./**

You can also use find command: 

*$ find . -name "\*.c" -print | xargs grep "main("")"))*
