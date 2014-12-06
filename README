gtw - git-taskwarrior wrapper
=============================

Keeps taskwarrior tasks in a separate branch of a git repository.

All commands are passed as-is to taskwarrior. Any modifications by taskwarrior
are then automatically committed and pushed to the main repository's branch.

Configuration
-------------

gtw uses two optional config variables from the main git repository:

    git config gtw.repository /path/to/taskwarrior-repository
    git config gtw.branch tasks

If gtw.repository is unset, the taskwarrior repository will be created in .git/task.

If gtw.branch is unset, tasks branch will be used by default.

Usage
-----

    cd your-project-repository/
    gtw <taskwarrior command>
    gtw add demonstrate usage # calls "task add demonstrate usage"
    git log tasks # taskwarrior changes are pushed into this branch

License
-------

Licensed under GPLv3, see http://www.gnu.org/licenses/gpl-3.0.html
