## Some Useful Git actions & commands

## ROLLING BACK

#### When you have __not staged__

Right after saving the file, run the `git checkout <filename>` command.

This will revert the file to the previous state before the edit was done.

#### When you have __staged__

After staging the file, run the `git checkout -- <filename>` command.

This will revert the file to the previous state before the change was done

> A command `git reset HEAD <filename>` was given but this did not work in my example.
