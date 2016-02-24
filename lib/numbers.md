---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

The different kinds of numbers in Ruby are integers (Fixnum) and decimals (Float)

# What are some common operations and comparisons you would perform on numbers?

Common operations are addition (+), subtraction (-), multiplication (*), division (/), modulus(%), exponentiation(**)
5 + 2 = 7 addition
5 - 2 = 3 subtraction
5 / 2 = 2 division (integer values)
5/ 2.0 = 2.5 division (float values)
5 * 2 = 10 multiplication
5 % 2 = 1  modulus
5 ** 2 = 25 exp

If all numbers in computation are integer values than the output will be an integer value.
If one of the numbers in the computation is a float than the output will be a float value.
The difference between the 2 following statements show this.

5*4+2-3+6%2 = 19
5*4+2-3.0+6%2 = 19.0

Commmon comparisons are greater than (>), less than (<) equal (==), greater than equal (>=), less than equal (<=)

# What is the difference between the `+` operation on a number versus on a String?

The '+' on a number adds, on  a string it concatenates.
1 + 1 = 2
"Steve is " + "very tall" = "Steve is very tall"

# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

It will fail generally. It is similar to trying to perform a mathematical opertion on the word "twenty".  To make this work convert the string to an integer. In this case use "20".to_i 
The one case it will work is a string * value.  This will cause the string to repeat itself value times

"abc" * 3 is "abcabcabc"

# What is the purpose of the `times` operation? Is that the same as `*`?

The 'times' operator repeats something a set number of times.  It is not the same as '*'.
3.times {puts "Hello"}  outputs 
Hello
Hello
Hello

whereas 3*8 = 24

