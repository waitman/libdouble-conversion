AC_PREREQ(2.59)

AC_INIT([libdouble-conversion], [1.1.1], [waitman@waitman.net])
AC_CONFIG_SRCDIR(src/double-conversion.cc)
AC_CONFIG_AUX_DIR(config)
AC_CONFIG_HEADERS(config/config.h)
AM_INIT_AUTOMAKE
AC_PROG_CC
dnl next 4 lines are a hack to avoid libtool's
dnl needless checks for C++ and Fortran compilers
m4_undefine([AC_PROG_CXX])
m4_defun([AC_PROG_CXX],[])
m4_undefine([AC_PROG_F77])
m4_defun([AC_PROG_F77],[])
LT_INIT

AC_CONFIG_FILES(src/Makefile Makefile)
AC_OUTPUT

