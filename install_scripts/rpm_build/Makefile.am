NULL =

SUBDIRS = 			\
	stereo			\
	po			\
	$(NULL)

themedir = $(DESTDIR)
theme_DATA = index.theme

THEME_IN_FILES = index.theme.in

%.theme: %.theme.in $(INTLTOOL_MERGE) $(wildcard $(top_srcdir)/po/*.po) ; \
$(INTLTOOL_MERGE) -d -u -c $(top_builddir)/po/.intltool-merge-cache  $(top_srcdir)/po $< $@ ; \
sed -i 's/_theme_name_/$(GETTEXT_PACKAGE)/' index.theme ;

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
