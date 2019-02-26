#INFO

Let d(n) be defined as the sum of proper divisors of n (numbers less than n which divide evenly into n).
If d(a) = b and d(b) = a, where a ≠ b, then a and b are an amicable pair and each of a and b are called amicable numbers.

For example, the proper divisors of 220 are 1, 2, 4, 5, 10, 11, 20, 22, 44, 55 and 110; therefore d(220) = 284. 
The proper divisors of 284 are 1, 2, 4, 71 and 142; so d(284) = 220.

Evaluate the sum of all the amicable numbers under 10000.

----------------------------------------------------------------------------------------------------------------------------------------

For this project I used a method called "divisor" which would return the sum of all numbers divisble from the integer being passed.
In the main, I used a for loop to go through all numbers 1 - 10000 and two temp values to test if the values were amicable.
temp1 would give me the output of d(a), while temp2 would give me d(b).
If d(b) == a && d(a) != d(b) =>  amicable = true

