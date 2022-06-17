## File Commands 
* `ls` 
    * directory listing 
* `ls -al `
    * formatted directory listing with **hidden** files 
* `cd dir` 
    * change directory to dir  
* `cd`
    * change to home directory 
* `pwd`
    * show present working directory 
* `mkdir dir `
    * create a directory dir 
* `rm file`
    * remove file
* `rm -r dir` 
    * delete directory dir 
* `rm -f file `
    * force remove file 
* `rm -rf dir `
    * force remove directory dir
* `cp file1 file2 `
    * copy file1 to file2
* `cp -r dir1 dir2 `
    * copy dir1 to dir2; creates dir2 if dir2 *doesn't exists*
* `mv file1 file2 `
    * rename or move file1 to file2; if file2 is in an existing directory, move file1 to directory file2 
* `ln -s `
    * create symbolic link to file 
* `touch file` 
    * create or update file 
* `cat > file` 
    * places standard input into file 
* `more file `
    * output the contents of the file 
* `head file` 
    * output the first 10 lines of the file
* `tail` 
    * output the last 10 lines of the file 
* `tail -f file `
    * output the contents of file as it grows, starting with the last 10 lines 

## Visual Editor for files 
* `vi file `
    * launches VI Editor on specific file 
### VI editing commands 
* i (goes into insert mode)
    * insert at cursor 
* a (goes into insert mode)
    * write after cursor 
* A (goes into insert mode)
    * wrote at the end of the line 
* ESC 
    * terminate insert mode 
* u 
    * undo last change 
* U 
    * undo *all* changes to the entire line
* o (goes into insert mode)
    * open a new line 
* dd 
    * delete line 
* 3dd 
    * delete 3 lines 
* D 
    * delete contents of line after the cursor 
* C 
    * delete contents of a line after the cursor and insert new text; press ESC to end insertion 
* dw 
    * delete word 
* 4dw 
    * delete 4 words 
* cw 
    * change word
* x 
    * delete character at cursor 
* r
    * replace character 
* R 
    * overwrite characters from cursor onward 
* s 
    * substitute one character uner cursor to continue to insert 
* S 
    * substitute entire line and begin to insert at the beginning of the line 
* ~
    * change case of individual character 
### Navigating within the file 
* k 
    * move cursor **up** 
* j 
    * move cursor **down** 
* h 
    * move cursor **left** 
* l 
    * move cursor **right** 
### Saving and closing the file
* shift + zz 
    * save the file and quit 
* :w 
    * save the file but keep it open 
* :q
    * quit without saving
* :wq 
    * save the file and quit 

