# mission 5 - numbers and data

## 1. task / objective
convert numbers between decimal binary and hexadecimal by hand, verify using python, write number_converter.py, and explain text encoding

## 2. work completed
solved all manual conversions with working steps, verified results in python terminal, wrote and tested number_converter.py with three test values, and answered text encoding questions

## 3. commands / tools used
python3, bin(), hex(), int(), ord()

## 4. my understanding

### task 5.1 - convert numbers by hand

1 convert decimal 13 to binary
13 / 2 = 6 rem 1
6 / 2 = 3 rem 0
3 / 2 = 1 rem 1
1 / 2 = 0 rem 1
read remainders from bottom to top
answer: 1101

2 convert decimal 25 to binary
25 / 2 = 12 rem 1
12 / 2 = 6 rem 0
6 / 2 = 3 rem 0
3 / 2 = 1 rem 1
1 / 2 = 0 rem 1
read remainders from bottom to top
answer: 11001

3 convert binary 1010 to decimal
(1 * 2^3) + (0 * 2^2) + (1 * 2^1) + (0 * 2^0) = 8 + 0 + 2 + 0 = 10
answer: 10

4 convert binary 1101 to decimal
(1 * 2^3) + (1 * 2^2) + (0 * 2^1) + (1 * 2^0) = 8 + 4 + 0 + 1 = 13
answer: 13

5 convert hexadecimal a to decimal
a in hex is 10
10 * 16^0 = 10
answer: 10

6 convert hexadecimal 1f to decimal
(1 * 16^1) + (15 * 16^0) = 16 + 15 = 31
answer: 31

7 convert binary 1111 to hexadecimal
group of 4 bits 1111 = 8 + 4 + 2 + 1 = 15
15 in hex is f
answer: f

### task 5.2 - verify using python
tested expressions in python:
- bin(13) gave '0b1101' (matches)
- bin(25) gave '0b11001' (matches)
- int('1010', 2) gave 10 (matches)
- int('1101', 2) gave 13 (matches)
- int('a', 16) gave 10 (matches)
- int('1f', 16) gave 31 (matches)
- hex(0b1111) gave '0xf' (matches)

### task 5.3 - build a small number converter
created number_converter.py and tested with 3 positive numbers:

| test number | binary output | hexadecimal output |
| :--- | :--- | :--- |
| 13 | 0b1101 | 0xd |
| 25 | 0b11001 | 0x19 |
| 42 | 0b101010 | 0x2a |

explanation of functions:
bin() converts integer number into binary string starting with 0b
hex() converts integer number into hexadecimal string starting with 0x

### task 5.4 - how is text stored?
- ascii code for uppercase letter a is 65 and lowercase letter a is 97
- computers only store binary bits so an encoding standard maps each letter to a unique number so text can be stored and shown correctly
- one character that is not part of basic ascii is euro symbol € or rupee symbol ₹ or emoji 😊

## 5. difficulties faced
no major difficulties

## 6. how i resolved them
not applicable

## 7. evidence / files
number_converter.py in this folder

## 8. commit details
commit message: build number converter and practise data representation
