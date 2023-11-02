## Some Useful Git actions & commands

## ROLLING BACK

#### When you have __not staged__

Right after saving the file, run the `git checkout <filename>` command.

This will revert the file to the previous state before the edit was done.

#### When you have __staged__

After staging the file, run the `git checkout -- <filename>` command.

This will revert the file to the previous state before the change was done

> A command `git reset HEAD <filename>` was given but this did not work in my example.

#### RESOURCE
[Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)

This has a lot of helpful commands in the day-to-day activities of a dev

## Vagrant

### VAgrantfile

Added a vagrantfile to be used to set up a virtual VM in order to utilize the jenkins environment

The following commands are used:

- `vagrant init <boxname>` to initialize the box with the type of distro

- Edit the vagrant file to provision the suitable VM capacity required

- `vagrant up` to bring the machine up into operation

- `vagrant ssh` to connect into the machine via ssh

- `vagrant halt` to puth the machine into a stopped state

- `vagrant destroy` to discard the machine

> inside browser:   `http://<ip address>:8080`

