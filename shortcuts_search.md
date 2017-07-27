# Research

## Notations

    (\ar)     : Placeholder for an arrow key
    (\c)      : Placeholder for a character
    (\n)      : Placeholder for a number (usually optionnal)
    (\w)      : Placeholder for a word

## Search

    t(\c)     : Reach the next occurence of c
    f(\c)     : See t(\c)
    /(\w)     : Find the next occurence of w (press enter to validate)
    *         : Find the next occurence of the word the cursor is on
    #         : Find the previous occurence of the word the cursor is on
    n         : Repeat last search from current position

## Go to

    0   |   |
              : (zero | pipe) Go to the start of the line
    ^   |   _
              : Go to the first character of the line
    $         : Go to the end of the line

    (\n)(\ar) : Move n characters/lines (defaults to one) in the chosen direction
    (\n)g(\ar): Same as (\n)(\ar), only works with up or down
    (\n)j   |   (\n)+
              : Move n lines below (defaults to 1)
    (\n)k   |   (\n)-
              : Move n lines higher (defaults to 1)
    (\n)l     : Move n characters to the right (defaults to 1)
    (\n)h     : Move n characters to the left (defaults to 1)
    (\n)G     : Go to line n

    (\n)(     : Go to the start of the n-th previous paragraph
    (\n))     : Go to the start of the n-th next paragraph
    (\n){     : Go to the end of the n-th previous paragraph
    (\n)}     : Go to the end of the n-th next paragraph
    [[        : Go to the start of the file
    ]]        : Go to the end of the file

    (\n)e     : Go to the last character of the n-th word after the current word (defaults to 1)
    (\n)w     : Go to the start of the n-th word after the current word (defaults to 1)
    (\n)b     : Go to the start of the n-th word before the current word (defaults to 1)

## Selection

    v         : Allows a user to use the arrow keys to select an area on which the next command will apply
    y         : Copies the selected are to the clipboard

## Others

    `         : Swaps cursor position with an other previously saved


