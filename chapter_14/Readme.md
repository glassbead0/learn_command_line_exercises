English | code
--- | ---
Can you remove blah.txt? | `rm blah.txt`
Lets get rid of our development log file. | `rm log`
Can you remove everything in the slash temp slash foo directory? | `rm -rf /tmp/foo`

the `rm -rf` command recursively removes all contents from a directory. If you do this from your home directory, that would be very bad. the -f option forces the removal, without giving you a warning or an option to stop. 
