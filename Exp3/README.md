# EXPERIMENT 03 – GDB DEBUGGER

## AIM
To debug C programs using GNU Debugger (GDB).

## THEORY

Debugging is the process of identifying and correcting errors in a program.

### Types of Errors

- **Syntax Errors** – Occur during compilation  
- **Runtime Errors** – Occur during execution  
- **Logical Errors** – Incorrect output  

### GNU Debugger (GDB)

GDB is a debugging tool used to:

- Execute programs step-by-step  
- Set breakpoints  
- Inspect variable values  
- Analyze program flow  

### Importance

- Helps locate errors efficiently  
- Allows real-time monitoring of execution  

## PROCEDURE

1. Compile the program with debugging option:


gcc -g program.c


2. Start GDB:


gdb a.out


3. Use commands:

- `break main`
- `run`
- `next`
- `print variable`
- `continue`

## RESULT

Program debugging was successfully performed using GDB.

---
