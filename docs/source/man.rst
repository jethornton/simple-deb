Create the man file
===================

A simple man file is needed to make lintian happy. In the man directory
create `howdy.1` and add the following to it.
::

	.TH HOWDY 1 "MARCH 2021" Linux "Just a Test"
	.SH NAME
	howdy \- howdy testing
	.SH SYNOPSIS
	.B howdy [-test]
	.SH DESCRIPTION
	.B howdy
	just a simple man page test

Now the directory structure looks like this.
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

	5 directories, 10 files
