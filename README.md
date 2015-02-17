rueqn
=====

rueqn is an AWK reimplementation of the traditional Unix troff eqn preprocessor.
The traditional Russian typography is based on its own historical and cultural
foundation. The goal is to reimplement eqn preprocessor to suit well with
Russian typographical tradition in typesetting mathematical equations.

This is not a complete work yet, but I hope it will be!

You can run it through groff to see what it is able to do:

 $ ./rueqn eqntest.tr | groff -Tps -dpaper=a4 >/tmp/out.ps

For other details see the source code, it is very compact and small.
