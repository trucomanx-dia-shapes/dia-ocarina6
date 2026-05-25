# Dia-Shapes for 6-hole ocarina tabs

![logo](screenshot.png)


## Install/uninstall shapes in the Dia directory 
Manual installation of the package in Dia. Installation is done in the `~/.dia` directory.

    make shapes
	make install

On the contrary, to uninstall we use:

    make uninstall

Uninstallation is done in the `~/.dia` directory.

Finally, if desire, deletes *.shape and *.png files.

	makeup clean

## Create a release

### Compressed file
Creates a file at `dist/dia-*-VERSION.tar.gz` where `VERSION` is the current version of the project.

	make dist

### DEB file
Creates a file in `deb/dia-*-VERSION_all.deb` where `VERSION` is the current version of the project.

	make deb

