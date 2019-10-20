# **0x01. Emacs**
> ## *Foundations - 0-Day ― 0-Day*

## General
* What is Emacs
* Who is Richard Stallman
* How to open and save files
* What is a buffer and how to switch from one to the other
* How to use the mark and the point to set the region
* How to cut and paste lines and regions
* How to search forward and backward
* How to invoke commands by name
* How to undo
* How to cancel half-entered commands
* How to quit Emacs

## EMACS
![Alt](https://www.gnu.org/software/emacs/tour/images/splash.png)

Emacs or EMACS is a family of text editors that are characterized by their extensibility. The manual for the most widely used variant, GNU Emacs, describes it as "the extensible, customizable, self-documenting, real-time display editor"

### Install emacs
In your terminal:

> * $ sudo apt-get update
> * $ sudo apt-get upgrade
> * $ sudo apt-get install emacs

* **C-e**   End of line
* **C-a**   Beginning of line
* **C-s**   Incremental search forward
* **C-r**   Incremental search backward
* **C-x h** Make region contain the entire buffer ("Select all")
* **C-k**   Kill line (cut)
* **C-w**   Kill region ("cut")
* **C-y**   Yanks last killed text
* **C-7**   Undo
* **C-x o** Change Buffer
* **C-x-4 C-f**   Open a file in other buffer
* **M-w**   Copy

*Tools for compiling, running, and testing programs. Emacs integrates with GDB to provide an IDE **M-x gdb; M-x gdb-many-windows**
* Emacs can compare two files and highlight their differences **M-x ediff**
* Emacs is a file manager **M-x dired**
* Starts a shell in the buffer named *shell*, switching to it if it already exists. Use C-u M-x shell to use a buffer with a different name. **M-x shell**
* Displays man pages. **M-x man**
