Command | Description
--- | ---
xargs | this executes some arguments. there are lots of uses, one example `echo 1 2 3 4 5 6 7 | xargs -n 2` this will print a max of 2 arguments per line. It seems to me that it takes the ouptup of the command on the left of the pipe, and executes the commands on the right with those inputs.
sudo | super usr do. This give you superpowers (or root power) to make changes to your system
chmod | changes the permissions on a file for User, Group and Others. Each one can have read, write and/or execute permissions.
chown | changes the owner of a file, and the group ownership.
