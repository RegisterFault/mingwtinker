AC_INIT([mingwtinker], [1.0], [registerfault@gmail.com])
AC_CONFIG_AUX_DIR([build-aux])
AM_INIT_AUTOMAKE([-Wall -Werror foreign])
AC_PROG_CC
AC_CHECK_HEADERS([unistd.h wchar.h windows.h],,
   AC_MSG_ERROR(["You need to select --host=<mingw compiler prefix>. I do i686-w64-mingw32"]))
AC_CONFIG_HEADERS([config.h])
AC_CONFIG_FILES([
        Makefile
        src/Makefile
])
AC_OUTPUT
