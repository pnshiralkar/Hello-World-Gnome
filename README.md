To build and install this program, run these commands from a terminal:

./autogen.sh --prefix=/home/$USER/.local
make install

-------------
When running the first command $USER will be replaced by your username.

Running the first command above creates the following files:

aclocal.m4
autom4te.cache
config.log
config.status
configure
hello-world.desktop
install-sh
missing
Makefile.in
Makefile

Running "make install", installs the application in /home/your_username/.local/bin
and installs the hello-world.desktop file in /home/your_username/.local/share/applications

You can now run the application by typing "Hello World" in the Overview.

----------------
To uninstall, type:

make uninstall

----------------
To create a tarball type:

make distcheck

This will create hello-world-1.0.tar.xz

