# vim-doc
Personal guide to vim

Navigation
----------
```
H   (HIGH)    move cursor to top of screen
M   (MIDDLE)  middle of screen
L   (LOW)     bottom of screen

zz  scroll cursor line to middle of screen
zt                        top of screen
zb                        bottom of screen

CTRL-y        Cursor remains; move viewport up
CTRL-e        Cursor remains; move viewport down

CTRL-u        Move viewport UP half screen
CTRL-d        Move viewport DOWN half screen
```
Searching
---------
```
/ <term>      Find occurances of term (searching forward)
? <term>      Find occurances of term (searching back)
n             Find NEXT occurance
N             Find previous occurance
CTRL-O        Go back to where you came from (can repeat multiple times)
CTRL-I        Go forward (from above)
%             Go to matching parenthesis ( "(", "[", "{" )
```
Replace
-------
```
:s/<search>/<replace>     Replace first instance of <search> with <replace> on current line
:s/<search>/<replace>/g   Replace all instances of <search> with <replace> on current line
:%s/<search>/<replace>/g  Reaplce all instances of <search> with <replace> in the whole file
:%s/<search>/<replace>/gc Reaplce all instances of <search> with <replace> in the whole file, with prompt
```
Editing
-------
```
r <char>      Replace the character under the cursor with <char>
ce            CHANGE to END of word.  Deletes word from cursor and places you in insert mode
c$            CHANGE to the end of the line
```
Deletion
--------
```
dw    delete word
d$    delete from cusror to end of line ($)
D     == d$
```
Tabs
----
```
                Open <file> in new tab    :tabe[dit] <file>
gt              Next tab                  :tabn[ext]
gT              Previous tab              :tabp[revious]
                Close tab                 :tabc[close]
                List tabs                 :tabs
```
Window Splits
-------------
```
                Split window horiz        :sp
                Split window vertically   :vsp
                Close window              :q
                
CTRL-w k        Move UP to window
CTRL-w j        Move DOWN to window
CTRL-w h        Move LEFT to window
CTRL-w l        Move RIGHT to window
```
Running command line commands
-----------------------------
```
:!<command>
```
Visual Selection
----------------
Enter visual selection mode with v
```
Press v
Move up/down to highlight a number of lines
:w <filename>       Will write the highlighted selection to the file <filename>
```
