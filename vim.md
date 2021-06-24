** Press  (i)  to insert text.
** Press (a,A)  to append text.
** Type  (o,O)  to open a new line.
** Press  (x,X)  to delete the character.
** press (1G) go to start line , (G)  go to end line , (10G) go to line 10
** Use  (:wq)  to save a file and exit.
** Type (.) go to repeat command
** Type (/) go to search mode and press (n) next word of file search
** press (r) to replace one character
...	...	...	...
Cut 		dd
copy 		yy
paste           p,P 
...	...	...	...
1. To delete from the cursor up to the next word type:    (dw) or (3dw)
2. To delete from the cursor to the end of a line type:     (d$) or (d^) 
3. To delete a whole line type:    (dd) or (2dd)
this use command (yy , 2yy) to.
...	...	...	...
To undo , type:               u  (lowercase u)
To reundo , type:           CTRL-R
...	...	...	...
substitute	:s/old/new/gc	:1,20s/old/new/g
...	...	...	...
:! command
:!! date	
...	...	...	...
Go To VISUAL mode	>>       press	(v)
...	...	...	...
