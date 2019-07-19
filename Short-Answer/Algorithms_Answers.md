### I gave 2 answers along with why.


## a) 
   1. 0(n^3) - because of the n * n * n in while loop 
   
   2.  0(n) -  the loop is only running linear based on n. if n == 1 it while run 1 time n == 2 twice etc..


## b)
   1. 0(n^4) - 4 nested for loops. O(n) _ O(n) _ O(n) * O(n) = O(n^4)
   2. 0(n^3) - all will run linear except for the last which will always run 10 times. 
## c)
   1. 0(n) This is a recursive function that is just running like a loop. Its going to start at whatever value bunnies is until its -1 so its linear 0(n)


  ## Exercise II

  ![Egg Tower](https://code.oursky.com/wp-content/uploads/2016/07/egg-dropping-puzzle.jpeg "Egg drop tower of terror!!")



 <!-- eggs = e, f = floors -->
  
  <!-- def eggDrop(e,f):
    #if no floors skip if 1 floor then koo
    if (f == 1 or f == 0):
        return f -->

Use a binary search:
 https://www.geeksforgeeks.org/binary-search/


Start at the middle floor and drop egg
* Find it by dividing length of building by 2 = middle floor
* if it is f we are doneskis! if f is lower than the middle floor we can rule out the top half of floors.
* same as if its higher than the middle index.
* repeat steps on lopp until f is middle element then we can figure out howe many are below it.


Recursively:
    if the egg breaks go halfway down and repeat,
    if the egg doesnt break, go halfway up and repeat


 DO this until highest floor is found where it doesn't break.



Bada bing bada boom!
https://hackernoon.com/what-does-the-time-complexity-o-log-n-actually-mean-45f94bb5bfbf

O(log n)


