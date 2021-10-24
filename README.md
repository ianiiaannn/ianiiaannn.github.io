# ianiiaannn.github.io

## Front-end only console style homepage, written in javascript

---

This project was written for [TCIRC homepage](https://tcirc.tw/).\
I love this so I rewirte, make she more readable and reupload here.\
Feel free to fork or start this!

---

## Commands

* Logo\
Logo command will get element id "ascii" and clone it.\
Logo shouldn't have spaces, spaces should be replaced to &nbsp\;

* Clear\
Clear everything but input line and header.\
There's a link to trigger help command for users doesn't have a keyboard.

* Ls\
Ls finds id "linkTable" and clone.\
\<th> means Folder.\
\<td> with class "exec" means executeable files(links).

* About\
A example of new simple command, just clone and insert.

* Help\
Commands are stored in a array called "CommandInstances".\
Any command are pushed into the array will be showen by the help command.

* init(function)\
Will execute Logo.run() then Help.run().

---
