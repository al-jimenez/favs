# favs()
favs is a Bash function - List/rate favorite alias, functions & scripts

## Use
Use this and customize it with your changes. I use this as a menu to remind my old man brain what I functions, scripts and aliases I have created since I forget stuff often.

## Help menu
When you execute favs -? you will get the following:
![Help menu](https://github.com/al-jimenez/favs/blob/master/favs.png)

## Special Options
 -                Show all favs
 -a | alias       Add  aliaslist/rate favorite alias, functions & scripts
 -f | function    Add favs function
 -s | script      Add favs script
 -l | list        Show favs list
 -e | edit        Edit favs file
 -? | -h | help   This help

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

See the example .favs file
