#INFO

Starting in the top left corner of a 2×2 grid, and only being able to move to the right and down, 
there are exactly 6 routes to the bottom right corner.

How many such routes are there through a 20×20 grid?

-------------------------------------------------------------------------------------------------------------------------------------

I used two different methods to solve this problem.
The lattice method which uses the binomial coefficient (mn) := m!/n!(m-n)! 
Then the factorial method which returns the factorial of a given integer.

The factorial method would return values too large for int or long, so I ended up using BigInteger.
