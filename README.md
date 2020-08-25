# Lexical-Compiler-Simple
## Requirement
- JavaCC
- JDK8
- Initial System Variable for Java Environment and JavaCC 6.0.1

## How to run via commandline line by line
- For Lexical calculator
```
javacc CalculatorResult.jj
javac Calc2.java
java Calc2
```
And then type any literal number or operator

- For Lexical Tree view
Type in commandline
```
jjtree CalculatorTree.jjt
javacc CalculatorTree.jj
javac Calc4.java
java Calc4
```
And then type any literal number or operator

- For Custom Programming Language Parser
Type in commandline
```
javacc SimpleProgram.jj
javac SimpleProgram.java
java SimpleProgram program.ht
```
The program.ht file contains our custom code. Edit program.ht file for 
