NULL =

SUBDIRS = 			\
	stereo			\
	po			\
	$(NULL)

themedir = $(datadir)/sounds/$(THEME_NAME)
#theme_DATA = index.theme

#THEME_IN_FILES = index.theme.in

wildcard = %.theme: %.theme.in
	$(INTLTOOL_MERGE) $(wildcard) $(top_srcdir)/po/*.po) ; \
	$(INTLTOOL_MERGE) $(top_srcdir)/po $< $@ -d -u -c $(top_builddir)/po/.intltool-merge-cache

EXTRA_DIST = \
	README			\
	CREDITS			\
	index.theme.in		\
	$(NULL)

CLEANFILES = \
        index.theme		\
	$(NULL)

DISTCLEANFILES = \
	$(NULL)

MAINTAINERCLEANFILES =		\
	*~			\
	intltool-*.in		\
	compile			\
	configure		\
	INSTALL			\
	install-sh		\
	missing			\
	mkinstalldirs		\
	config.guess		\
	ltmain.sh		\
	config.sub		\
	depcomp			\
	Makefile.in		\
	config.h.*		\
	aclocal.m4		\
	$(NULL)
