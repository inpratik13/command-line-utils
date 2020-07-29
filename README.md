# command-line-utils
Command line utilities to ease day-to-day work.


### code
Opens file or directory in Visual studio code app.

`code .`  
Opens current directory in Visual studio code app.

`code test.txt`  
Opens `test.txt` in Visual studio code app.


### watch
Repeats provided commands at given interval.

`watch -n 5 ls -lh`  
Executes `ls -lh` command every 5 second.

`watch ls -lh`  
Executes `ls -lh` command every 2 second. 2 sec is default time if `-n` flag is not passed.

### .zshrc
Contains useful configurations for `zsh`.

- `export PS1="%B%F{cyan}[%n@%m %1d]\$%f%b "`  
  Sets terminal prompt to `#[user_name@host_name dir_name]$` in cyan colour.

