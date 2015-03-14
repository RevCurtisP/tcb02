# Introduction #

CONSOLE.TCB includes Commands and Functions for Console access.

# Usage #

`INCLUDE "CONSOLE"`

# Commands #

**CLS** Clears the Screen.

Example: `CLS`

**GET** Returns a character from the keyboard without waiting. If no key is pressed, returns 0.

Example: `GET C`

**GET** Waits for a key to be pressed, then returns the respective character.

Example: `READ C`

**HEX** prints a byte or word as hexadecimal.

Example: `HEX B`
Example: `HEX W!`

**LOCATE** moves the cursor to the desired location.

Example: `LOCATE COL, ROW`

**NEWLINE** outputs a new line, moving the cursor to the first column of the next row.

Example: `NEWLINE`

**PUT** prints a character on at the current cursor position and advances the cursor.

Example: `PUT C`

# Functions #

**COL()** returns the column of the current cursor position. The left most column is 0. Any arguments are ignored.

Example: `LET X = COL()`

**COLS()** returns the screen width in columns. This will be one greater than the maximum column position. Any arguments are ignored.

Example: `LET WIDTH = COLS()`

**ROW()** returns the row of the current cursor position. The top most row is 0. Any arguments are ignored.

Example: `LET Y = ROW()`

**ROWS()** returns the screen width in rows. This will be one greater than the maximum row position. Any arguments are ignored.

Example: `LET HEIGHT = ROWS()`