Directory Structure
===================

Building a deb of a Python program so you can share it.

The example Python program is called `howdy`. Setup the directory structure for
the program.

I created a directory called minimum-deb and placed the other directories in
there.
::

	john@d10cave:~/minimal-deb$ mkdir -p howdy-0.0.1/debian/source howdy-0.0.1/man howdy-0.0.1/src
	john@d10cave:~/minimal-deb$ tree
	.
	└── howdy-0.0.1
	    ├── debian
	    │   └── source
	    ├── man
	    └── src

	5 directories, 0 files

The program directory also has the revision as part of the name.

You can create the directories with a file manager or in a terminal with the
following command.
::

  mkdir -p howdy-0.0.1/debian/source howdy-0.0.1/man howdy-0.0.1/src
