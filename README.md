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
Editing
-------
```
r <char>      Replace the character under the cursor with <char>
ce            CHANGE to END of word.  Deletes word from cursor and places you in insert mode
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
