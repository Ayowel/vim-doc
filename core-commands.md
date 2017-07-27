# Core commands

Those commands are the least one should know to use vim. Lack one, and you'll probably end-up stuck at some point.

## Save and exit

    :w      : Write your changes to the disk.
    :w!     : In case :w throws an error, can force through some restrictions

    :q      : Exit. If changes have been made, this will throw an error
    :q!     : Exit no matter what has been done before

    :wq     : Save and exit, equivalent to ':w' then ':q'
    :wq!    : Save and exit, equivalent to ':w!' then ':q'

## Undo

    u       : Revert your last modification


