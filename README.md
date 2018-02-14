# GREBA - Git Repository Backup

Creates automated backups of Git repositories,
fetching changes from a central repository
(origin) and backing them up in compressed
tarballs.

Official Public Repository: https://gitlab.com/jwaghetti/greba.

### Setup

Clone git repositories to be backup up on a
directory. Give each repository directory the
`git` suffix.

To create backups, just run the greba on that
directory containing the git repositories.

### Command Line Options

* **--delete-older-than** *date*:
deletes compressed backups older than given date
(in format YYYYmmdd).

* **--help**:
displays setup and options for Greba.

* **--no-backup**:
does not create compressed backups.

* **--no-update**:
does not fetch changes from origin.

* **--version**:
displays version, copyright and licensing info.

**Copyright 2014 Jean Waghetti**

This work is free. You can redistribute it and/or modify it under the
terms of the Do What The Fuck You Want To Public License, Version 2,
as published by Sam Hocevar. See http://www.wtfpl.net/ for more details.
