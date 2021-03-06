Experimental Operating System (XOS)
===================================
Version 1.0.1
--------------
This is a platform for building a simple operating system upon a simulated machine hardware. Various components have been provided in this development package. 

For instructions and detailed documentation, visit
http://xosnitc.github.com/


Components
==========
APL-Compiler
SPL-Compiler
XFS-Interface
XSM

ChangeLog
=========
* SPL Compiler Fixes
	-- Fixed incorrect string comparision
	-- Fixed incorrect format of 'store' compilation.

Compiling
=========
* Use 'make' from the base directory to compile all components

* To compile each component separately, cd into the corresponding directory
and use 'make' command.

* To recompile each component, within the corresponding directory, first use 'make clean' and then use 'make' command.

Mailing Lists
=============
* Users
xos-users@googlegroups.com

* Contributors
xos-developers@googlegroups.com

* Contributor: Rohit sukumaran
All code done in spl/spl_progs/


Compiling and Loading XOS code to Machine
=============

to compile and load all interrupts
```
cd myxos
./cals
```
to compile single program
```
./compile [apl][spl] [flags] [filename]
```

to load single program
```
./load [apl|spl] [flags] [filename]
```
to remove single program from disk
```
./rm [flags] filename
```
