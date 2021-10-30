# ianiiaannn.github.io

## Front-end only console-style homepage, written in javascript

This project was written for [TCIRC homepage](https://tcirc.tw/).\
I rewrite, make it more readable, and upload it here.\
Feel free to fork or start this!

## Commands

* Logo\
Logo command will get element id "ASCII" and clone it.\
The logo shouldn't have spaces, spaces should be replaced to &nbsp\;

* Clear\
Clear everything but input line and header.\
There's a link to trigger help command for users who don't have a keyboard.

* Ls\
Ls finds id "linkTable" and clone.\
\<th> means Folder.\
\<td> with class "exec" means executeable files(links).

* About\
An example of a new simple command, just clones and insert.

* Help\
Commands are stored in an array called "CommandInstances".\
Any commands are pushed into the array will be shown by the help command.

* init(function)\
Will execute Logo.run() then Help.run().

---
