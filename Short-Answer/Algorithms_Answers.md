#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n) , grows at n^3 while a is growing at n^2. Runtime grows as n grows


b) O(n^2) 2 loops are multiplied to get O(n^2) runtime


c) O(n) recursive function. could also be O(n-1) since it's subtracted by 1 each time the call is made

## Exercise II


Binary search would be best used here. O(log n). n = num_floors
Split the floors into 2 equal parts. Start in the middle and drop an egg
If it breaks, loop process with lower half of floors until the egg no longer breaks (n-1)
If it doesn't break, loop process with upper half of floors until the egg breaks (n+1)
Stop when only one floor is left and return it as f 