#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ(2.59)
AC_INIT(pam_externalpass, 0.1, thomas@habets.pp.se)
AM_INIT_AUTOMAKE([pam_externalpass], [0.1])
AC_CONFIG_SRCDIR([pam_externalpass.c])
AC_CONFIG_HEADER(config.h)

# Checks for programs.
AC_PROG_CC
#AC_PROG_LIBTOOL

# Checks for libraries.

# Checks for header files.
AC_HEADER_STDC
AC_HEADER_SYS_WAIT
AC_CHECK_HEADERS([stdlib.h string.h sys/time.h syslog.h unistd.h])

# Checks for typedefs, structures, and compiler characteristics.
AC_C_CONST
AC_TYPE_PID_T
AC_TYPE_SIZE_T

# Checks for library functions.
AC_FUNC_FORK
AC_FUNC_MALLOC
AC_CHECK_FUNCS([dup2 memset strdup strerror])

AC_CONFIG_FILES([Makefile])
AC_OUTPUT