# Introduction #

The Header Macro File imports the appropriate HDR file which contains directives and constants specific to the target machine and compiler.

# Usage #
`IMPORT "HEADER"`

**Note: This must be the first executable line of code in a program**

# Commands #

**EXIT** gracefully exits the program, returning control to the operating system.

Example: `EXIT`

**RANDOM** seeds the random number generator. This command should be executed before the first RND() function

Example: `RANDOM X`

# Functions #

**RND()** returns a random number between 0 and 255. Any arguments are ignored.

Example: `LET X = RND()`