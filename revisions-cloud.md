**Git** is a *distributed version control system* that allows for multiple users to edit code, make and track changes, and review previous versions. 

Git organizes **repositories** where project files are stored and organized. Repositories can be accessed locally or remotely. These can be *cloned* from the remote repository onto a local system.

The local repository is comprised of:
* Working directory (where files live)
* Index (used for staging
* Head (Points to the most recent commit)

When changes are made in Git, they are *flagged* to indicate they came after the previous commit. The modified file is staged, and then committed -- which provides a snapshot.

The three step process can be seen as:
* Add
* Commit
* Push

Changes that have been committed locally still need to be *pushed* to the remote repository so that they are up-to-date.

This can be done with the 'git push origin master' command.