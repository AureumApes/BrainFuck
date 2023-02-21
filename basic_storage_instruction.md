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
Memory<br>
\[0] \[50]

Copy
-
### Copy with loss
This will copy the byte freom cell\[0] too cell\[1]
```brainfuck
+++++++[>+<-]
```
Memory<br>
\[0] \[7]

### Copy withot loss
```brainfuck
+++++++[>+<>>+<<-] Copy cell0 to cell1 and cell2
>>[<<+>>-]<< Copy cell2 to to cell0 with loss
```
Memory<br>
\[7] \[7]