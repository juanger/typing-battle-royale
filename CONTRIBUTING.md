# Send Pull Request

## Create a feature branch
To create a feature branch, run the following command from your terminal:

    $ git checkout -b feature/name_of_branch

Add your changes from VSCode `+` button in "Source Control"  or with:

    $ git add PATH/TO/FILE

Commit your changes from VSCode with `✔︎` button in "Source Control" or with:

    $ git commit -m "Commit message explaining changes"

Push changes to `origin` remote

    $ git push origin feature/name_of_branch

Create a Pull Request from your github.com fork

Switch back to your master branch:

    $ git checkout master

# Helpful terminal commands

## Shell

* `ls` - Lists the files in the current directory
* `mkdir DIRNAME` - Creates a new directory with the given name
* `pwd` - Prints the current directory path
* `cat FILENAME` - Prints the contents of the file with the given name
* `man COMMAND` - Prints the manual for the given command (exit by typing `Q`)


## Git

Create a commit

    $ git commit -m "This is my commit message"

Push your commit to a feature branch

    $ git push origin feature/name_of_branch

Switch to the master branch

    $ git checkout master

Pull latest changes from parent repository

    $ git pull parent master

See the list of commits in the current branch

    $ git log