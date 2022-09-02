# Random useful

* find or fd - recursively finding file/folder with regex

* touch - create file as dir/file.ext

* locate - look for filepaths with given string

* cut - only use specific parts of file/output

* sort - sort list of data

* uniq - will remove duplicated data of sorted list

* paste - print out data, can set delimiter

* xargs - pass lines of data into arguments for the next command

* bc - calculator

* wc - count how many lines/words/etc

* alias - create shorthand for certain commands
    * `alias gs="git status"`
    * likely want to add to .bashrc or will be reset on terminal close

* ln - create symbolic link

* cron/crontab - create job that runs every so often
* httpie/http - easier version of curl

* `cd -` - will cd to previous directory
* `pushd` - cd into new directory but save current location
* `popd` - will go to previous location in stack

* `sudo !!` - rerun previous command with sudo
* `<c-r>` - will search through command history
* `!102` - re-run #102 in command history
* `<c-u>` - will clear current line instead of holding <bs>
* `command | column -t` - make output into columns/table

* `cmatrix` - cool looking sort of screen saver

# Text search/manipulation

* grep - look for regex in lines of file(s)

* awk - more in depth/better grep

* sed - search and replace + grep like in vim substitute

# Job running / parallelizing

* jobs - show running jobs

* kill - sends signal to job, by defaul kill signal
    * `kill %1` will kill job 1
    * `kill -STOP %1` - will stop/pause job 1

* `echo "hello" &` - run echo command in background
* bg/fg - will run job in background/foreground
    * `bg %1` - continue job in background
    * `fg %1` - continue job in foreground

* <c-z> stop/pause job

* nohup - run job and ignore hangup commands, will save output to file
    * `nohup echo "hello" &` - run in background and ignore hangup commands
    * useful when running in remote session, allow to run even when disconnected
