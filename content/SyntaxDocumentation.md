## Syntax

Syntax of custom programming language accepted:

1. Declaration variables.
2. Assign variables 
3. Program Body
4. Statement

### Assign variables

```
<DATA_TYPE> <VARIABLE_NAME> := <VALUE>
```
<DATA_TYPE> may be one of the following: INTEGER, FLOAT, STRING, BOOLEAN
You can declare a variable everywhere inside the program

### Program Body
```
PROGRAM
// Writes main code here
ENDPROGRAM
```

### Print statement

```
PRINT <VARIABLE_NAME> | <INTEGER> | <FLOAT> | <STRING>
```


### Statement
* If..else condition
```
IF <CONDITIONAL> THEN
	// Do somethings
ELSE
	// Do somethings else
ENDIF
```
* Switch case
```
SWITCH <VARIABLE_NAME>
	CASE <FIRST_VALUE>: 
		// Do somethings in case
	ENDCASE
	CASE <SECOND_VALUE>: 
		// Do somethings in case
	ENDCASE
	DEFAULT:
		// Do somethings in case
	ENDCASE
ENDSWITCH
```
* While loop
```
WHILE <CONDITIONAL> DO
	// Do somethings in loop
ENDWHILE
```