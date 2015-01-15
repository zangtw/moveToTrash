# moveToTrash

A simple script that can work as recycle bin on Unix/Linux.

#### Installation step

1. put this file under whatever folder in your `$PATH`.
2. create a folder named `~/.Trash`
3. add these aliases in you `~/.bashrc`:

```bash
alias rm='MoveToTrash'
alias CleanTrash='/bin/rm -rf ~/.Trash/*'
```

#### To use this program
-  use `CleanTrash` if you want to clean the recycle bin.
-  use `rm` directly in your terminal to delete the files/folders.
-  if you want to call this program in your shell script, you need to `source` your script.
