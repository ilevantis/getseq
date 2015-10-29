getseq
======

Prints the entries from a multiFASTA file which contain a string.

Usage:
------
``Usage: getseq FILE1 [STRING [OPTIONS [FILE2]]]``

FILE1              A multifasta file.

STRING             The string used to search the FASTA entries in FILE1.

Options:
--------
-d              Searches the description line of each fasta entry for the 
                inputted string(s) and prints these entries. This is the 
                default mode if no option is given.

-s              Searches the sequence of each fasta entry for the 
                inputted string(s) and prints these entries.

-f file         Takes a file (FILE2) as an option argument. Each line of
                FILE2 will be used as a search string.

-h              Prints a help message.

If no STRING is given or if -f is not used, stdin is read to provide the search strings.