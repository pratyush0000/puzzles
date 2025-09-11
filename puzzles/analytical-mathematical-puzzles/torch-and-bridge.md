# Torch and Bridge

There are 4 people (A, B, C, and D) who want to cross a bridge at night.

* A, B, C and D take 1, 2, 5 and 8 minutes respectively to cross the bridge.
* There is only one torch with them, and the bridge cannot be crossed without the torch.
* There cannot be more than two people on the bridge at any time, and when two people cross the bridge together, they must move at the slower person's pace.

Can they all cross the bridge in 15 minutes?

<figure><img src="https://media.geeksforgeeks.org/wp-content/uploads/20250515160437692532/bride_and_torch.webp" alt="Torch and Bridge" height="400" width="800"><figcaption><p>Puzzle- Torch and Bridge</p></figcaption></figure>

#### Check if you were right - full answer with solution below. <a href="#check-if-you-were-right-full-answer-with-solution-below" id="check-if-you-were-right-full-answer-with-solution-below"></a>

**Solution:** They must cross the bridge in the following way:

**Step 1:** A and B cross the bridge. A comes back. Time taken is **3 minutes**. Now B is on the other side.\
\


<figure><img src="https://media.geeksforgeeks.org/wp-content/uploads/20191212132039/Torch-and-Bridge-solution2-768x472.png" alt="Torch-and-Bridge-solution2" height="472" width="768"><figcaption><p>Step- 1</p></figcaption></figure>

\


\
**Step 2:** C and D cross the bridge. B comes back. Time taken **8 + 2 = 10 minutes**. Now C and D are on the other side.\
\


<figure><img src="https://media.geeksforgeeks.org/wp-content/uploads/20191212131222/Torch-and-Bridge-solution-1-768x472.png" alt="Torch-and-Bridge-solution-1" height="472" width="768"><figcaption><p>Step- 2</p></figcaption></figure>

\


\
**Step 3:** A and B cross the bridge. Time taken is **2 minutes**. All are on the other side.\
\


<figure><img src="https://media.geeksforgeeks.org/wp-content/uploads/20191212131449/Torch-and-Bridge-solution-2-768x472.png" alt="Torch-and-Bridge-solution-2" height="472" width="768"><figcaption><p>Step- 3</p></figcaption></figure>

\


\
**Total time spent:** 3 + 10 + 2 = 15 minutes.

**To minimize the time:**

> The trick here is that the persons with the fastest speeds only should come back (and that too only if there is a need to come back, as here we need to bring back the torch). A comes back in step-1 and B comes back in step-2. And, finally reduce the number of traveling back, like C, D does not come back.
