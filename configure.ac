AC_INIT(tcpkali, 0.1, lwalkin@machinezone.com)

AC_CONFIG_SRCDIR([tcpkali.c])
AC_CONFIG_AUX_DIR(config)
AM_INIT_AUTOMAKE(foreign)
AC_CONFIG_MACRO_DIR(m4)

AC_CONFIG_HEADER([config.h])

AM_MAINTAINER_MODE
AM_PROG_LIBTOOL

AC_PROG_CC
AC_PROG_CPP
AC_PROG_INSTALL

AX_CHECK_COMPILE_FLAG([-W], [CFLAGS="$CFLAGS -W"])
AX_CHECK_COMPILE_FLAG([-Wall], [CFLAGS="$CFLAGS -Wall"])

m4_include([libev/libev.m4])

AC_CONFIG_FILES([Makefile libev/Makefile])
AC_OUTPUT