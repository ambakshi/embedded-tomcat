AC_INIT([embedtomcat], [0.1])
AC_MSG_NOTICE([Sample tomcat embedded app.])

AC_ARG_VAR(PKGNAME, [ PKGNAME=, Use given package name])
if test -z "$PKGNAME"; then
    PKGNAME="embeddedTomcatSample"
fi
AC_SUBST([PKGNAME])

AC_ARG_VAR(VERSION, [ VERSION=, Use given package version])
if test -z "$VERSION"; then
    VERSION="1.0"
fi
AC_SUBST([VERSION])
AC_OUTPUT(Makefile pom.xml)
