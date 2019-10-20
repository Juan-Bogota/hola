# **0x02. vi**
> ## *Foundations - 0-Day ― 0-Day*

## General
* What is vi
* Who is Bill Joy
* How to start and exit vi
* What are the command and insert modes, and how to switch from one to the other
* How to edit text
* How to cut and paste lines
* How to search forward and backward
* How to undo
* How to quit vi

## VI
![Alt](https://miro.medium.com/max/1110/1*VO98sILElESsQdiq1DLcZQ.png)

The default editor that comes with the UNIX operating system is called vi (visual editor). [Alternate editors for UNIX environments include pico and emacs, a product of GNU.]
The UNIX vi editor is a full screen editor and has two modes of operation:
    1. Command mode commands which cause action to be taken on the file, and
    2. Insert mode in which entered text is inserted into the file.

* **:wq<Return>**   quit vi, writing out modified file to file named in original invocation
* **:q!<Return>**   quit vi even though latest changes have not been saved for this vi call
* **u**	      UNDO WHATEVER YOU JUST DID; a simple toggle
* **i**	      insert text before cursor, until <Esc> hit
* **a**	      append text after cursor, until <Esc> hit
* **o**	      open and put text in a new line below current line, until <Esc> hit

You can see other commands in this [link](https://www.cs.colostate.edu/helpdocs/vi.html)
