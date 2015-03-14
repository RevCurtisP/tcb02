# Introduction #

The Macro Library consists of macro _include_ files which contain _macros_ and _aliases_ for standard Basic commmands and functions.

# Details #

Each macro file imports it's related Assembly Language Library File.

**HEADER.TCB** Header information for the target machine and compiler. Also contains the RND() Function.

_INCLUDE "HEADER"_ must be the first line that is not a blank or a comment in a TCB02 program.

**CONSOLE.TCB** Commands and Functions related to the console (keyboard and screen).

**PRINT.TCB** The PRINT command. Usually requires CONSOLE.TCB.

**GRAPHICS.TCB** Pixel Graphics Commands and Functions. May be hi-resolution or character based, depending on the target machine.

**CHAR.TCB** Functions for Single Characters.

**STRING.TCB** String Functions. Requires STRING.TCB.