AUTOMAKE_OPTIONS = foreign

if ENABLE_APPS
  MAYBE_APPS = cli
endif

if ENABLE_MAN
  MAYBE_MAN = man
endif

SUBDIRS = src include $(MAYBE_APPS) $(MAYBE_MAN)

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = wavpack-stream.pc

MAINTAINERCLEANFILES = \
	configure \
	Makefile.in \
	config.guess \
	config.sub \
	ltmain.sh \
	aclocal.m4 \
	depcomp \
	compile \
	missing \
	install-sh

EXTRA_DIST = doc/*.pdf doc/*.html doc/*.css
