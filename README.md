otree
=====

Replacement for tree command with better functionalites.

I frequently use tree command and half of the time it is followed by 'mvim'. When giving second command to open files in a complex directory structure(well, it is Java always), I again go through the output of tree command and try to decode the path of the file, relative to the cwd,  I want to open. To simply this workflow, otree assigns a number to each file and user will be prompted to enter the number assigned to file he wants to open.

# Future work:
    1. Support flags to list the methods, classes, tags(in case of html, xml) inside the source files. 
    2. Add colors to output
    3. Support flags to list files properties such as size, permission, owner, last modified, etc,.



# Usage:
    1. Clone the repository. 
    2. Unzip the contents. 
    3. Copy the otree file into /usr/bin/ or any other directory on the path.
