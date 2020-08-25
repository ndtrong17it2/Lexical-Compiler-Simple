## Syntax

Syntax of custom programming language accepted:

1. Declaration variables.
2. Assign variables 
3. Program Body
4. Statement

### Declaration

```
DECLARATION
Assign variables here
``` 

### Assign variables

```
BOOLEAN a:= TRUE
INTEGER b:= 20
STRING s:= "text sample"
```

### Program Body
```
PROGRAM
// Writes main code here
ENDPROGRAM
```

### Statement
* If..else condition
```
IF b = 10 THEN
	// Do somethings
ELSE
	// Do somethings else
ENDIF
```
* Switch case
```
SWITCH b
	CASE 10: 
		// Do somethings in case
	ENDCASE
	CASE 50: 
		// Do somethings in case
	ENDCASE
	DEFAULT:
		// Do somethings in case
	ENDCASE
ENDSWITCH
```
* While loop
```
WHILE b < 10 DO
	// Do somethings in loop
ENDWHILE
```