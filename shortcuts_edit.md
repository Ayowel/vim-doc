# edit

The edit mode has two sub-modes amongst which a user can switch by pressing 'insert':

* insert mode : a character typed is inserted between those surrounding him
* replace mode : a character typed replaces the following on the line

**Caution :** Depending on your system,vim might use a dedicated clipboard or your system's clipboard. Make tests.

## Notations

    (\ar)     : Placeholder for an arrow key
    (\c)      : Placeholder for a character
    (\n)      : Placeholder for a number
    (\w)      : Placeholder for a word
    (\*)      : Generic placeholder

## Enter insert mode

    i         : Enter insert mode at the cursor's position
    a         : Enter insert mode 1 character after the cursor's position
    o         : Toggles insert mode on a new line under the current one
    s         : See Delete category
    c         : See Delete category

## Quick insert

    p         : Insert the content of the clipboard at the selected position

## Enter replace mode



## Quick replace

    (\n)r(\c) : The n (defaults to 1) following characters will be replaced by c (once)

## Delete

[Go-to commands](shortcuts_search#go-to)

    dd        : Delete the current line and copy it to the clipboard
    (\n)d(\*) : Deletes characters traveled by using a go-to command. The go-to uses n as (\n) parameter if possible.
    cc        : Delete current line's content, copy it to the clipboard and enter insert mode
    (\n)c(\*) : Same as (\n)d(\*) then enter insert mode
    (\n)D     : Deletes characters from the cursor's position to n lines after (defaults to 0)
    (\n)C     : Same as (\n)D then enters insert mode
    (\n)x     : Delete the n next characters on the current line
    (\n)s     : Removes the n following characters on the line and enter insert mode (defaults to 1)
    (\n)S     : Deletes all characters on the current line and n lines after then enters insert mode (defaults to 0)

## Others

    (\n)u     : Undo last change
    (\n)~     : Invert capitalisation on the n next characters on the line
