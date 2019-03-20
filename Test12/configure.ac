#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT(hello, [1], [])
AC_CONFIG_SRCDIR([src/main.c])
AC_CONFIG_HEADERS([config.h])

AM_INIT_AUTOMAKE(-Wall -Werror foreign) 
AM_PROG_AR
# Checks for programs.
AC_PROG_CC
# Checks for libraries.
AC_SEARCH_LIBS([dlopen], [dl])
# Checks for header files.

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.

LT_INIT([static])
AC_CONFIG_FILES([Makefile
		src/Makefile])
AC_OUTPUT
