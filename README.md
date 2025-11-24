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
MOV A,P0 
MOV R0,A 
MOV B,R0 
MUL AB 
MOV P2,A 
END
```
## OUTPUT
![WhatsApp Image 2025-11-07 at 21 49 00_67426f1e](https://github.com/user-attachments/assets/5e70b902-9d8d-491f-8fb8-2bc40408acae)
![WhatsApp Image 2025-11-07 at 22 47 10_894b8073](https://github.com/user-attachments/assets/b73edd88-d335-49d6-b0b1-f6b978b0b640)

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
MOV A, P0
MOV B, A
MUL AB
MOV R0, A
MOV A, R0
MOV B, P0
MUL AB
MOV P2, A
END
```

## OUTPUT
![WhatsApp Image 2025-11-07 at 22 43 29_19932908](https://github.com/user-attachments/assets/1c4d64c0-7411-4cd4-9274-76a3fce5f61a)
![WhatsApp Image 2025-11-07 at 22 47 10_275342f8](https://github.com/user-attachments/assets/142b7779-8664-4ceb-b98e-5bf3975c56c7)


## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
