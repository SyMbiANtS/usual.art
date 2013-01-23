
AC_PREREQ([2.60])
AC_INIT([sound-theme-mageia.guitar.4],
        [4],
        [https://forums.mageia.org/en/viewtopic.php?t=4038])

AC_CONFIG_SRCDIR([index.theme.in])

AM_INIT_AUTOMAKE([1.9 no-dist-gzip dist-bzip2])

AC_SUBST(VERSION)

IT_PROG_INTLTOOL([0.40.0])
GETTEXT_PACKAGE=sound-theme-mageia.guitar.4
AC_SUBST(GETTEXT_PACKAGE)
AC_DEFINE_UNQUOTED(GETTEXT_PACKAGE, "$GETTEXT_PACKAGE")
AM_GLIB_GNU_GETTEXT

AC_PROG_LN_S

AC_CONFIG_FILES([
Makefile
stereo/Makefile
po/Makefile.in
])

AC_OUTPUT
