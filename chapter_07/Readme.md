English | command
--- | ---
Can you remove the tmp directory? | `rmdir tmp`
Lets clear out your log directory. | `cd log` enter, `ls` then, `rm <filename>` or `rmdir <directory_name>` until everything is removed. use `rm -r` for a directory that is not empty, but be careful, this removed everything inside that directory. Alternatively, we could just `rm -r log` from the directory that contains log to remove it entirely. 

Do More

Bullet Point | command
--- | ---
Make 20 directories and remove them all | `mkdir directory_name` do this 20 times. then `rmdir directory_name` 20 times, or `mkdir directory1 directory2 ...` and then `rmdir directory1 directory2 ...`
make a single path of directories that is 10 deep and remove them all one at a time. | `mkdir -p here/is/a/path/of/directories/ten/levels/deep/dude` then `cd here/is/a/path/of/directories/that/is/ten/levels/deep` then `rmdir dude` `cd ..` `rmdir deep` `cd ..` `rmdir levels` ...etc until you have removed them all. 
If you try to remove a directory with contents, you get an error | you can fix this by `rmdir -r directory_name` but you have to be careful with the -r option. it removes things recursively, so it removes all subdirectories and files. 
