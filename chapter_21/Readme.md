English | code
--- | ---
What is your shell set to? | `env | grep shell` mine says SHELL=/bin/bash
What direcotry are in you (dont use `pwd` this time)? | `env` and look for PWD or `env | grep $PWD`
What is your home directory set to? | `env | grep HOME` and look for the HOME environment variable. Mine is /Users/aaronglasenapp
Can you set your environment to have DEBUG set to true? | `export DEBUG=true`

To add my newly created ~/bin direcotory to my PATH, i do PATH=~/bin:$PATH

To make this permanant, I edited my ~/.profile to include ~/bin: before $PATH
