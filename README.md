Project Euler #10: Sum of Primes
===========================

I made this method off the idea off of Project Euler's #10 of finding the sum of all primes up to two million, and made the method compatible with any limit you enter in the parameters. I started out doing the obvious thing and going through each number and finding if it was divisible by anything other than itself and 1, but ran into a StackOverflowError. Also, I really wanted to go with recursion while using the method, but that didn't work without unneeded parameters for the method and also gave me a StackOverflowError. Doing more research I found that making an array of boolean values would take up less memory and also give me the ability not to go through every single number up to the limit. After taking it to a whiteboard and explaining it to a few people, everything clicked and fixed a few issues I was having with.

Project Euler #11: Grid Product
===========================
What is the greatest product of four adjacent numbers in the same direction (up, down, left, right, or diagonally) in the 20x20 grid? 

I made the program so any grid X by X (must be equal dimensions) could be used. I originally thought of using normal arrays, but it would just require more code, and someone could make a method that combines all the normal arrays into 2d arrays. This project requires knowledge of using loops and exit statements in order to be able to control going through every combination of numbers and also not going out of bounds in the array.

Project Euler #12: Triangle Number
===========================

What is the value of the first triangle number to have over five hundred divisors?

I felt that this problem was easier than the last two, but I got stuck on line 29 and had to look up online for help. I want to come back to this problem and make it smoother. It is about 1.1 seconds, but it should be able to run at like 50ms with the right refinements.

