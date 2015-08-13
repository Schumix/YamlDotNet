dnl Warning: This is an automatically generated file, do not edit!
dnl Process this file with autoconf to produce a configure script.
AC_PREREQ([2.54])
AC_INIT([YamlDotNet], [0.1])
AM_INIT_AUTOMAKE([foreign])
AM_MAINTAINER_MODE

dnl pkg-config
AC_PATH_PROG(PKG_CONFIG, pkg-config, no)
if test "x$PKG_CONFIG" = "xno"; then
        AC_MSG_ERROR([You need to install pkg-config])
fi

SHAMROCK_EXPAND_LIBDIR
SHAMROCK_EXPAND_BINDIR
SHAMROCK_EXPAND_DATADIR

AC_PROG_INSTALL

AC_PATH_PROG(DMCS, dmcs, no)
if test "x$DMCS" = "xno"; then
        AC_MSG_ERROR([dmcs Not found])
fi


AC_ARG_ENABLE(debug,
	AC_HELP_STRING([--enable-debug],
		[Use 'DEBUG' Configuration [default=NO]]),
		enable_debug=yes, enable_debug=no)
AM_CONDITIONAL(ENABLE_DEBUG, test x$enable_debug = xyes)
if test "x$enable_debug" = "xyes" ; then
	CONFIG_REQUESTED="yes"
fi
AC_ARG_ENABLE(debug_unitysubset_v35,
	AC_HELP_STRING([--enable-debug_unitysubset_v35],
		[Use 'DEBUG_UNITYSUBSET_V35' Configuration [default=NO]]),
		enable_debug_unitysubset_v35=yes, enable_debug_unitysubset_v35=no)
AM_CONDITIONAL(ENABLE_DEBUG_UNITYSUBSET_V35, test x$enable_debug_unitysubset_v35 = xyes)
if test "x$enable_debug_unitysubset_v35" = "xyes" ; then
	CONFIG_REQUESTED="yes"
fi
AC_ARG_ENABLE(performancetests,
	AC_HELP_STRING([--enable-performancetests],
		[Use 'PERFORMANCETESTS' Configuration [default=NO]]),
		enable_performancetests=yes, enable_performancetests=no)
AM_CONDITIONAL(ENABLE_PERFORMANCETESTS, test x$enable_performancetests = xyes)
if test "x$enable_performancetests" = "xyes" ; then
	CONFIG_REQUESTED="yes"
fi
AC_ARG_ENABLE(release_portable_signed,
	AC_HELP_STRING([--enable-release_portable_signed],
		[Use 'RELEASE_PORTABLE_SIGNED' Configuration [default=NO]]),
		enable_release_portable_signed=yes, enable_release_portable_signed=no)
AM_CONDITIONAL(ENABLE_RELEASE_PORTABLE_SIGNED, test x$enable_release_portable_signed = xyes)
if test "x$enable_release_portable_signed" = "xyes" ; then
	CONFIG_REQUESTED="yes"
fi
AC_ARG_ENABLE(release_portable_unsigned,
	AC_HELP_STRING([--enable-release_portable_unsigned],
		[Use 'RELEASE_PORTABLE_UNSIGNED' Configuration [default=NO]]),
		enable_release_portable_unsigned=yes, enable_release_portable_unsigned=no)
AM_CONDITIONAL(ENABLE_RELEASE_PORTABLE_UNSIGNED, test x$enable_release_portable_unsigned = xyes)
if test "x$enable_release_portable_unsigned" = "xyes" ; then
	CONFIG_REQUESTED="yes"
fi
AC_ARG_ENABLE(release_signed,
	AC_HELP_STRING([--enable-release_signed],
		[Use 'RELEASE_SIGNED' Configuration [default=NO]]),
		enable_release_signed=yes, enable_release_signed=no)
AM_CONDITIONAL(ENABLE_RELEASE_SIGNED, test x$enable_release_signed = xyes)
if test "x$enable_release_signed" = "xyes" ; then
	CONFIG_REQUESTED="yes"
fi
AC_ARG_ENABLE(release_unitysubset_v35,
	AC_HELP_STRING([--enable-release_unitysubset_v35],
		[Use 'RELEASE_UNITYSUBSET_V35' Configuration [default=NO]]),
		enable_release_unitysubset_v35=yes, enable_release_unitysubset_v35=no)
AM_CONDITIONAL(ENABLE_RELEASE_UNITYSUBSET_V35, test x$enable_release_unitysubset_v35 = xyes)
if test "x$enable_release_unitysubset_v35" = "xyes" ; then
	CONFIG_REQUESTED="yes"
fi
AC_ARG_ENABLE(release_unsigned,
	AC_HELP_STRING([--enable-release_unsigned],
		[Use 'RELEASE_UNSIGNED' Configuration [default=NO]]),
		enable_release_unsigned=yes, enable_release_unsigned=no)
AM_CONDITIONAL(ENABLE_RELEASE_UNSIGNED, test x$enable_release_unsigned = xyes)
if test "x$enable_release_unsigned" = "xyes" ; then
	CONFIG_REQUESTED="yes"
fi
AC_ARG_ENABLE(release,
	AC_HELP_STRING([--enable-release],
		[Use 'RELEASE' Configuration [default=YES]]),
		enable_release=yes, enable_release=no)
AM_CONDITIONAL(ENABLE_RELEASE, test x$enable_release = xyes)
if test "x$enable_release" = "xyes" ; then
	CONFIG_REQUESTED="yes"
fi
if test -z "$CONFIG_REQUESTED" ; then
	AM_CONDITIONAL(ENABLE_RELEASE, true)
	enable_release=yes
fi


dnl package checks, common for all configs

dnl package checks, per config


AC_CONFIG_FILES([
YamlDotNet/yamldotnet.pc
YamlDotNet/Makefile
Makefile

])

AC_OUTPUT
