ACLOCAL_AMFLAGS =-I m4 --install

SUBDIRS = src include docs m4 tests

EXTRA_DIST = bootstrap.sh AUTHORS TODO NEWS README.md ticcutils.pc.in codemeta.json

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = ticcutils.pc

ChangeLog: NEWS
	git pull; git2cl > ChangeLog
