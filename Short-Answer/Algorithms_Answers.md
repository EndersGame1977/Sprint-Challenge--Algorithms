#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a)
a = 0  
 while (a < n _ n _ n): -> Fastest growing term
a = a + n \* n

        This term is: quadratic.
        The Big O Notation is: O(n^2)

b)
sum = 0
for i in range(n):
j = 1
while j < n:
j \*= 2 -> Fastest growing term
sum += 1
  
 This term is: quadratic
The Big O Notation is: O(n^2)

c)
def bunnyEars(bunnies):
if bunnies == 0:
return 0
return 2 + bunnyEars(bunnies-1) -> Fastest growing term

        This term is: linear
        The Big O Notation is: O(n)

## Exercise II

        f = floor
        e = egg
        building is f tall
        if e is thrown off building at f <= 2 the e is fine
        if e is thrown off building at f > 2 the e breaks

        This is linear, O(n), because, only one egg is being dropped at a time and the highest time complexty is number of eggs.
