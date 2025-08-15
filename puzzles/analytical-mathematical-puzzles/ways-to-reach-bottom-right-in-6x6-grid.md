# Ways to Reach Bottom Right in 6x6 Grid

You begin in the top left corner of a 6x6 grid, and your objective is to move to the bottom right corner. There are just two directions you can move: right or down. Both diagonal and backward movements are prohibited. How many different ways are there to get from the start to the finish?

<figure><img src="https://media.geeksforgeeks.org/wp-content/uploads/20241228163555788894/puzzle-660.webp" alt="puzzle" height="330" width="660"><figcaption></figcaption></figure>

\
**Approach 1 - Using Combinatorics:**

<figure><img src="https://media.geeksforgeeks.org/wp-content/uploads/20221019142115/PUZZLE3-660x330.png" alt="Three conditions of reaching at the last end" width="660"><figcaption><p>Three conditions of reaching at the last end</p></figcaption></figure>

<figure><img src="https://media.geeksforgeeks.org/wp-content/uploads/20221019140955/PUZZLE4-660x352.png" alt="Example of some ways to reach endpoint" width="660"><figcaption><p>Example of some ways to reach endpoint</p></figcaption></figure>

We can see here that the number of paths from starting left point to the right ending is not depending on the way of the path, it depends on the number of rows and columns taken to reach the end. Whenever we face such kind of problem, where we have a choice to take or a fixed number of rows or columns to be taken in grid. We can think about mathematics in those cases. Here, we are going to use a mathematical concept, called **combinatorics.**

**Why combinatorics?**

In this case of a 6×6 grid, all the paths must consist of a total of 10 moves, 5 down and 5 right, our job is to select the 5 right moves from the collection of 10 moves. we must employ a certain number of rows and columns (5 of the total 10 blocks) to travel from the left beginning to the right end.\
if we choose 5 rows box then the answer is **10c5=252** and the same if we choose 5 column answer is **10c5=252.**

#### **Approach 2 - Using Pascal Triangle:**

<figure><img src="https://media.geeksforgeeks.org/wp-content/uploads/20221019142244/PUZZLE1-660x330.png" alt="Pascal Approach" width="660"><figcaption><p> Pascal Approach</p></figcaption></figure>

If we know the number of ways to reach the left box and an upper box of a given box, then, the number of ways to reach at the given box, we can easily visualize, it will be the sum of both because we can either reach here from the left box paths or upper box paths. As shown in the figure here, we can reach the left box in A ways and reach the upper blocks in B ways, so the total answer to reach will be A+B.&#x20;

<figure><img src="https://media.geeksforgeeks.org/wp-content/uploads/20221111112858/PUZZLE2.png" alt="" width="900"><figcaption></figcaption></figure>

Here, for the first row, they can only be taken from the left move, not from the upward move. So the answer is 1 for the first row and similarly, for the first column they can be only taken from the upward move, not from the left move. So the answer here is also 1, and for the remaining grid, it is calculated using the **Pascal Approach** which is explained before. To reach the right endpoint, we have taken the sum of (126+126), which are moves at its top and left.&#x20;
