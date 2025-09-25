# SQUARE AND CUBE OF A NUMBER
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
ORG 00H
MOV DPTR,#4500H
MOVX A,@DPTR
MOV B,A
MUL AB
INC DPTR
MOVX @DPTR,A
INC DPTR
MOV A,B
MOVX @DPTR,A
END


```

## OUTPUT
<img width="1912" height="1111" alt="Screenshot 2025-09-25 060637 1" src="https://github.com/user-attachments/assets/956f997d-8bd0-4947-87da-312dd2de9af8" />



## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```
ORG 00H
MOV R0,#50H
MOV A,@R0
MOV B,A
MUL AB
MOV B,A
MOV A,@R0
MUL AB
INC R0
MOV @R0,A
INC R0
MOV @R0,B
END

```


## OUTPUT

<img width="1904" height="1126" alt="image" src="https://github.com/user-attachments/assets/ddf3d62e-83a4-45b1-8b87-d78d78de3014" />


## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
