###stringlist-regexp###
converts a list of strings to a nested regexp.

function( strings, [ matchStart: true , matchEnd: true ])

example:
`stringListRegExp(['foo','bar','baz']); //yields (^foo$|b(ar$|az$))
stringListRegExp(['foo','foobar','bar','baz'], true, false); //yields (^(foo(bar)?|b(ar|az)))

[![Build Status](https://travis-ci.org/w0ps/stringlist-regexp.svg?branch=master)](https://travis-ci.org/w0ps/stringlist-regexp)