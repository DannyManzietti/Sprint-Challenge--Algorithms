#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) Runtime 0(n):
the loop runs until a hits n^3, a is increasing by n^2. the loop tuns n times

b) Runtime 0(nlog(n)):
the loop runs n time and the inner loop runs log(n) times. this is because j increases exponentially until n for each value between 0 and n. the sum is the number of times j is doubled which is the function of a linearithmic.

c) runtime 0(n): recursion?
as 'bunnies' grows the number of times bunnyEars grows at the same rate since 'bunnies' only decreases by 1 the base case is 0

## Exercise II

the start floor is 1
the end floor is n
find middle floor between the two if total is even middle is low

if more than one floor, drop and egg from middle floor.
if two floors left(END-START == 1)
if egg breaks, current middle floor is floor f.
if egg doesnt break the end floor is f.
stop dropping those eggs
if egg breaks, current floor becomes new ending floor
find middle floor using new end floor. continue dropping eggs
if it doesnt break the floor above the the middle floor bcomes new start floor.
find middle floor using new start floor. continue dropping eggs

if 1 floor (end -start == 0) the floor is auto f
runtime 0(log(n)):
