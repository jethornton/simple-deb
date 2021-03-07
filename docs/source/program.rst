Create the Howdy program
========================

In the src directory create the howdy file and add the following to it.
::

	#!/usr/bin/env python3

	print('howdy')

Now the directory structure looks like this and we have all the files
needed to build the deb.
::

	john@d10cave:~/minimal-deb$ tree
	.
	└── howdy-0.0.1
	    ├── debian
	    │   ├── changelog
	    │   ├── compat
	    │   ├── control
	    │   ├── copyright
	    │   ├── files
	    │   ├── manpages
	    │   ├── rules
	    │   └── source
	    │       └── format
	    ├── man
	    │   └── howdy.1
	    └── src
	        └── howdy

	5 directories, 10 files

