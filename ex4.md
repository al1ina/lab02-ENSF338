1. Describe the algorithm you will use to find the room. Assume all the information you have is the one given by the sign; you have no knowledge of the floor plan [0.5 pts]

I’ll look at the sign which says rooms EY100 to EY130 start to the left and then I’d check the rooms on both the left and right of the sign and I’d conclude that the hallway is a loop. 

Then I’d go to the right side because it is room EY138 which is closer to EY128, then I’d check 2 rooms and conclude that the room numbers are evenly distributed and then use interpolation search to find which room EY128. 

2. How many ”steps” will it take to find room EY128? And what is a “step” in this case? [0.25 pts]

A step is an observation/action that provides new information

Checking both the left and right rooms – step 1

Going to 2 next rooms on the right, sequentially up – steps 2 & 3

Calculating the logical next room using interpolation search – step 4

Therefore it’d take 4 steps

3. Is this a best-case scenario, worst-case scenario, or neither? [0.25 pts]

Best-case scenario 

4. With this particular sign and floor layout, explain what a worst-case or best-case scenario would look like [0.5 pts]

Best-case scenario

The room on the right would be EY128 and we would find the room right away

Worst-case scenario

The room numbers are unevenly distributed or missing, making the interpolation estimate inaccurate forcing us to check the rooms sequentially

5. Suppose after a few weeks in the term you memorize the layout of the floor. How would you improve the algorithm to make it more efficient? [0.5 pts]
Since I would have the floor layout memorized I’d be able to navigate to the room I want right away making it very efficient → O(1) 
