SUBDIRS = src debian winbuild tgz2build tests scripts
ACLOCAL_AMFLAGS= -I m4

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = zorplibll.pc

EXTRA_DIST = dist.conf ${pkgconfig_DATA} makefile.msc VERSION

distclean-local:
	rm -rf scripts/config.log scripts/failure_notify5.0-0 target test-driver

