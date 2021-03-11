Building the deb
================

In the howdy-0.0.1 directory of the program in this case it's a 
subdirectory of minimal-deb open a terminal and build the deb with the
following command.
::

	dpkg-buildpackage -us -uc

To check the deb file open a terminal in the minimal-deb directory and
use lintian to verify.
::

	john@d10cave:~/minimal-deb$ ls
	howdy-0.0.1                  howdy_0.0.1_amd64.changes  howdy_0.0.1.dsc
	howdy_0.0.1_amd64.buildinfo  howdy_0.0.1_amd64.deb      howdy_0.0.1.tar.xz
	john@d10cave:~/minimal-deb$ lintian howdy_0.0.1_amd64.deb
	john@d10cave:~/minimal-deb$ 

If there are no errors then nothing is displayed.

Right click on the deb and open with Gdebi.

.. image:: images/gdebi-01.png
    :align: center

You can see what files will be installed where on the `Included files`
tab.

.. image:: images/gdebi-02.png
    :align: center

You can install the deb then open a terminal and type on howdy to see
the program is installed.

.. image:: images/program-01.png
    :align: center

You can also type in man howdy to see the man page.

.. image:: images/man-01.png
    :align: center

