# Git Grep
+ Searches for parts of strings in a directory

`git grep 'something'`

+ Searches for parts of strings in a directory and the -n prints out the line numbers where git has found matches

`git grep -n 'something'`

+ Searches for parts of string in a context (some lines before and some after the grepped term)

`git grep -C<number of lines> 'something'`

+ Searches for parts of string and also shows lines BEFORE the grepped term

`git grep -B<number of lines> 'something'`

+ Searches for parts of string and also shows lines AFTER the grepped term

`git grep -A<number of lines> 'something'`
