
AC_PREREQ([2.60])

AC_INIT([sound-theme-echoe.synth-1],
        [1],
        [https://github.com/SyMbiANtS/usual.art])

AC_CONFIG_SRCDIR([index.theme.in])

AM_INIT_AUTOMAKE([1.9 no-dist-gzip dist-bzip2])

AC_SUBST(VERSION)

THEME_NAME=echoe.synth-1
AC_SUBST(THEME_NAME)
AC_DEFINE_UNQUOTED(THEME_NAME,"$THEME_NAME")

IT_PROG_INTLTOOL([0.40.0])
GETTEXT_PACKAGE=sound-theme-$THEME_NAME
AC_SUBST(GETTEXT_PACKAGE)
AC_DEFINE_UNQUOTED(GETTEXT_PACKAGE, "$GETTEXT_PACKAGE")
AM_GLIB_GNU_GETTEXT

AC_PROG_LN_S

AC_SUBST(ENABLE_KDE_HACK)
AC_SUBST(ENABLE_FREEDESKTOP_HACK)
AC_SUBST(ENABLE_HOOK)
AC_DEFINE_UNQUOTED(ENABLE_HOOK,"$ENABLE_HOOK")
AC_DEFINE_UNQUOTED(ENABLE_KDE_HACK,"$ENABLE_KDE_HACK")
AC_DEFINE_UNQUOTED(ENABLE_FREEDESKTOP_HACK,"$ENABLE_FREEDESKTOP_HACK")

AC_CONFIG_FILES([
Makefile
stereo/Makefile
po/Makefile.in
])

AC_OUTPUT
