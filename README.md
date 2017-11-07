# eunuchs
Missing manly parts of UNIX API for Python

Eunuchs is a library of Python extension that complement the standard libraries in parts where full support for the UNIX API (or the Linux API) is missing.

Most of the functions wrapped by Eunuchs are low-level, dirty, but absolutely necessary functions for real systems programming. The aim is to have the functions added to mainstream Python libraries.

Current list of functions included:

    fchdir(2)
    recvmsg(2) and sendmsg(2), including use of cmsg(3)
    socketpair(2)
