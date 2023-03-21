## Terminal Cheat Sheet
> Note: You can change font size by prefacing text with `#`. The more `#` you use, the smaller the text is.

### List of commands
#### Files
* `mkdir` - make a folder
* `touch` - make a file
* `mv` - move a file
  * > The syntax is `mv` `file name` `new location`.
* `rm` - permanently remove a file (it cannot be found in the bin)
  * `rm -r` - if you try to `rm` a directory you will get an error so use `-r` after
  * > You need a whitespace between `rm` and `-r`.
* `.` - everything
* `ls` - list 
  * `ls -a` - list everything including hidden files 
    * >It is colour-coded into blue:visible and white:hidden.
    * >The `.` preface denotes a file and no `.` denotes a folder.
  * `ls -l` - list including details such as date/time
  * `ls -la` - both `-a` and `-l` can be merged into one command
#### Navigation
* `pwd` - view your path and see where you are
* `cd` - return to home (you should see a bare `~`)
* `..` - go two steps before on the path

#### Display
* `command` and `L` - clear the terminal screen
  * >You can still scroll up and see previous commands.

#### Git Commands
* `git status` - check what stage it is on
* `git log`

##### the stages
* `git init` - initialise 
* `git add` - add onto the stage
  * e.g, `git add .` will add everything
* `git push` - 
* `git commit -m"[enter a message]"` - save the work 
  * > `git commit` requires a message 