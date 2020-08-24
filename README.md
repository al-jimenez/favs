# favs()
favs is a Bash function - List/rate favorite alias, functions & scripts

## Use
Use this and customize it with your changes. I use this as a menu to remind my old man brain what functions, scripts and aliases I have created since I forget stuff often.

## Help menu
When you execute favs -? you will get the following:
![Help menu](https://github.com/al-jimenez/favs/blob/master/favs.png)

## Usage Examples

     favs -a 'c=clear;  Clears the screen' 3
       '♥︎ ♥︎ ♥︎ ALIAS:    c=clear;  Clears the screen'

     favs -f 'notes | .n add a date stamped note to .notes file.' 2
       '  ♥︎ ♥︎ FUNCTION: notes | .n add a date stamped note to .notes file.'

     favs -s 'cheatsheets.sh - load specific cheatsheets' 1
       '    ♥︎ SCRIPT:   cheatsheets.sh - load specific cheatsheets based
                        on language'

     favs -s 'cheatsheets.sh - load specific cheatsheets'
       '      SCRIPT:   cheatsheets.sh - load specific cheatsheets based
                        on language'

## A portion of the .fav file  
    ♥︎ ♥︎ ♥︎  FUNCTION: 'cdf()'          - a cd macro funciton to cd to location of frontmost Finder window

    ♥︎ ♥︎ ♥︎  FUNCTION: 'g()'            - list of git commands; fast, shortened git commands & help (g -?)

    ♥︎ ♥︎ ♥︎    SCRIPT: 'chknet'         - provides a suite of network tests (custom to this machine) ALIAS: (chk -?)

    ♥︎ ♥︎ ♥︎  FUNCTION: 'dev()'          - allows travels to local & remote dev projects using dev folder structure (dev -?)

    ♥︎ ♥︎ ♥︎  FUNCTION: 'which()'        - Overloading of which. Reveals aliases & functions then uses '/usr/bin/which' (which ?)

    ♥︎ ♥︎ ♥︎  FUNCTION: 'whereis()'      - Overloading of whereis. Locate programs (using native 'whereis') or a file (i.e. script, etc).




See the example .favs file for more examples
