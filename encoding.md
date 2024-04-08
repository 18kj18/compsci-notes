# Encoding 

Two common formats used for encoding strings are:
- ASCII
- Unicode

# ASCII
American National Standard Code for Information Interchange

Ascii is a 7-bit character set, with 247 unique ascii values

These numbers







# Code points
- Each character in a character set table is assigned a unique value(code point)

## Extended ASCII character sets
- because 8-bit computers allowed for 256 characters and ASCII only used 128, this was all that was requied to represent the characters and symbols of the English language.
- When other nations wanted to use computers they needed code points to assign to their own alphabets. This space was found by using the additional 8th bit. These are Extended ASCII.
- Each version of extended ascii differs from the last.

# Unicode
- Worldwide character-encoding standard
- All characters, symbols and all that

## Varaible width encoding
- Codes of differing lengths are used to encode a character set for representation, usually in a computer.
- E.g. code point of value 123 can be sent in 8 bits, and 2005 can be sent in 16 bits

# UTF - Unicode Transformation Format
- UTF-8 is the main encoding method on the internet, It uses 8 bit blocks to represent characters

---

Example:

U+20AC

1. Convert it to binary
C = 12 HEX = 1100
A = 10 HEX = 1010
0 = 0000
2 = 0010

20AC = 0010 0000 1010 1100

2. How many bits are necessary to represent the number?
First 2 are 0, so we only need 14 bits to encode it in Unicode

3. Identify the corresponding row of this table
[](https://i.stack.imgur.com/sQuKr.png)

The third row can fit 14 bits, so we use that one.
1100010 10000010 10101100 is the answer

---

Example:

11100010 10011100 10010011 to UTF-8

1. Remove the digits used to encode the row
0010 011100 010011

