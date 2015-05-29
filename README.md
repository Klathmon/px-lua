# px-lua

This allows you to run LUA from within providex.

Currently there are 2 ways to run code:
* RUN_FILE\[$\]()
* RUN_STRING\[$\]()

If the file/string ends in a `return` statement, then it will return that value to providex and the functions will return the value to you.

Make sure to use the correct function (string vs numeric) depending on what you are expecting, if you get it wrong i'm not sure what will happen...

#TODO:
* allow translation from pxplus memory files to LUA tables
* allow LUA scripts to call pxplus subroutines
