AC_INIT(myconfig, version-0.1)

AC_PROG_CC

AC_ARG_WITH(
    [my-argument],
    [AS_HELP_STRING(
        [--with-my-argument],
        [My argument is used to change some behaviour of course]
    )],
    [with_my_argument=yes],
    [with_my_argument=no]
)

if test "$with_my_argument" == yes
then
    AC_MSG_NOTICE(["with my_argument"])
else
    AC_MSG_NOTICE(["without my_argument"])
fi

AC_OUTPUT
