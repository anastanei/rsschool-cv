# Anastasiia Nikonova
## Contacts
* discord: anastasiya#5684
* [email@gmail.com](mailto:email@gmail.com)
* [+8-800-555-35-35](tel:+8-800-555-35-35)
## Code example
[Bit counting](https://www.codewars.com/kata/526571aae218b8ee490006f4)

The function countBits takes a non-negative integer n as input and returns the number of 1 bits in its binary representation. For example, for the input 1234, which is represented as 10011010010 in binary, the function returns 5 because there are five 1 bits.
```javascript
const countBits = (n) => n.toString(2).split('0').join('').length;
```