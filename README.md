# ior-check

This allows you to easily check certain material's ior values on your linux shell.


To use the script:

-Download both files and save them in a folder of your choice. Mine are both saved under ~/Documents/scripts.

-Open the .sh file and make sure the cd command is taking you to the folder where your .csv file was saved.

-Create an alias that sources the .sh file and save. For example:

alias ior 'source ~/Documents/scripts/ior.sh'

-Now, when you open your shell, you can type:

ior mtl

replace the word 'mtl' for the material you're looking for. For example:

ior gold
