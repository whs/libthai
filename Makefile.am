ACLOCAL_AMFLAGS = -I m4

SUBDIRS = include src data tests doc

EXTRA_DIST = \
	build-aux/git-version-gen	\
	build-aux/test.map	\
	meson.build	\
	meson_options.txt	\
	subprojects/libdatrie.wrap	\
	$(NULL)

MAINTAINERCLEANFILES = Makefile.in

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = libthai.pc

dist-hook:
	echo $(VERSION) > $(distdir)/VERSION
