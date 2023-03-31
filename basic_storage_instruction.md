Basic Storage Instructions
=

This file will teach you the basics of managing your cells

for(i)
-
```brainfuck
++++[Fill this with Code-]
```
### Multiply with for(i)
This will set cell\[1] to 50
```brainfuck
++++++++[>++++<-]
```
Memory Before<br>
\[10] \[0]<br>
Memory After<br>
\[0] \[50]

Copy
-
### Move a Value
This will move the value from cell\[0] too cell\[1]
```brainfuck
+++++++[>+<-]
```
Memory Before<br>
\[7] \[0]<br>
Memory After<br>
\[0] \[7]

### Copy a value
```brainfuck
+++++++[>+<>>+<<-] Move cell0 to cell1 and cell2
>>[<<+>>-]<< Move cell2 to to cell0
```
Memory Before<br>
\[7] \[0]<br>
Memory<br>
\[7] \[7]
