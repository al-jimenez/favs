# favs()
favs is a Bash function - List/rate favorite alias, functions & scripts

## Use
Use this and customize it with your changes.   
I use this as a menu to remind my old man brain what I functions, scripts and aliases I have created since I forget stuff often.

## Help menu
When you execute favs -? without parameters you will get the following:
![Help menu]()

## Special Options

### Update Option
This option performs the following operations:
  1) git add .
  2) git commit -m "<commit message>"
  3) git push (if remote repo defined)

 The commit message can be specified on the command line i.e.:  g u "<commit message>"
 This message will be appended with the stagged filenames, i.e.:  "[a-macbook]:README.md; Updated README.md file"
 Optionaly I have include bash commits with the same code to prepend date and machine name as well.

### Ignore Option
 This option adds a file to the .gitignore file using the following syntax:
  g ignore <filename>

### Git Log Options
 Here are some 'git log' options that I commonly use:

 g log | g l      -     which git log --name-status
