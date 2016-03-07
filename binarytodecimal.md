## To Convert Decimal to Binary

To convert decimal to binary is also very simple, you simply divide the decimal value by 2 and then write down the remainder. Repeat this process until you cannot divide by 2 anymore, for example let's take the decimal value 157: 

157 ÷ 2 = 78
78 ÷ 2 = 39
39 ÷ 2 = 19
19 ÷ 2 = 9
9 ÷ 2 = 4
4 ÷ 2 = 2
2 ÷ 2 = 1
1 ÷ 2 = 0	with a remainder of 1
with a remainder of 0
with a remainder of 1
with a remainder of 1
with a remainder of 1
with a remainder of 0
with a remainder of 0
with a remainder of 1	<--- to convert write this remainder first.

Next, write down the value of the remainders from bottom to top (in other words write down the bottom remainder first and work your way up the list) which gives: 

10011101 = 157

## To Convert Binary to Decimal

For a 16 bit value you would use the decimal values 1, 2, 4, 8, 16, 32, 64, 128, 256, 512, 1024, 2048, 4096, 8192, 16384, 32768 (powers of two) for the conversion. As you can see, we have placed the numbers 1, 2, 4, 8, 16, 32, 64, 128 (powers of two) in reverse numerical order, and then written the binary value below. 

----

 All you need to be able to do is double numbers and occasionally add one.

Start at the first ‘1’ on the left, and start with the mental number one
Move one digit right. If that digit is a zero, multiply your mental number by two. If it is a one, multiply your mental number by two and add one.
Repeat step 2 for every digit of the binary number
Here’s an example. We’ll use the binary number 1101010 1011010:

1011010 – We start at the first one. Our mental total: 1
1011010 – Next digit is a zero; we double our mental number: 1 x 2 = 2.
1011010 – Next digit is a one; we double our mental number and add one: 2 x 2 + 1 = 5
1011010 – Another one; double and add one: 5 x 2 + 1 = 11
1011010 – Zero; double: 11 x 2 = 22
1011010 – One; double and add one: 22 x 2 + 1 = 45
1011010 – And finally a zero; double: 45 x 2 = 90

------

This trick can be used in reverse for converting decimal to binary, but it’s harder to do mentally as the binary numbers tend to overflow your mental registers. If you try it, it’s best to use a piece of paper and write the binary number down as you go. You’ll be writing down the digits from right (least significant) to left (most significant).

So, the procedure looks something like:

1. Start with the decimal number in your head
2. Is the current decimal number divisible by 2?
a. If so, then write down 0
b. If not, then write down 1 and subtract 1 from the mental number.
3. Divide your mental number by 2 and go back to step 2. Repeat until your mental number is 0.

It’s easy to lose track of where you are in the conversion process, so jotting notes is helpful.

Directly applying this process to hexadecimal is even harder, as it relies on the ease of dividing by two. One possible approach would be to first convert your decimal number to binary as described above and then converting each set of four binary digits to hex, starting from the right…easy enough, just memorize your single-hex-digit-to-binary conversion table.
http://www.zenoli.net/2007/03/quickly-convert-binary-to-decimal-in-your-head/


