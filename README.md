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
MOV R0,#50H
MOV A, @RO
MOV B, A
MUL AB
INC RO
MOV @RO, A
END








```

## OUTPUT


![WhatsApp Image 2025-09-22 at 21 36 24_47cd22f7](https://github.com/user-attachments/assets/9ff9ae83-523c-4bfa-912d-bf1aa00d3e08)

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
MOV RO,150H
MOV A, @RO
MOV B,A
MUL AB
MOV B, @RO
MUL AB
INC RO
MOV @RO, A
INC RO
MOV @RO, A
END







```


## OUTPUT

![WhatsApp Image 2025-09-22 at 21 36 24_ef2c19c9](https://github.com/user-attachments/assets/26d07caf-d0a8-456f-beff-30600aaf06d2)

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
