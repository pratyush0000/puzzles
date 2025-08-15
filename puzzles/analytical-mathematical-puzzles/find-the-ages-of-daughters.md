# Find the ages of daughters

**lok** has three daughters. His friend **Shyam** wants to know the ages of his daughters. Alok gives him a first hint.&#x20;

**1.** The product of their age is 72. \
**Shyam** says this is not enough information. **Alok** gives him a second hint. \
\
**2.** The sum of their ages is equal to my house number. \
**Shyam** goes out and looks at the house number and says, “I still do not have enough information to determine the ages”. **Alok** admits that **Shyam** can not guess and gives him the third hint. \
\
**3.** The oldest girl likes strawberry ice cream. \
**Shyam** can guess after the third hint. Can you guess what are the ages of the three daughters?&#x20;

<figure><img src="https://media.geeksforgeeks.org/wp-content/uploads/20230616085654/file.png" alt="" width="1000"><figcaption></figcaption></figure>

\


**Solution:**

> The main thing to note is, when we take all combinations of 3 numbers whose product is 72 and try summing them, we get same sum for two set of triplets ((2, 6, 6) and (3, 3, 8)). Since the question says, that the second hint was also not enough, we must consider these triplets. In these triplets, the second triplet has a single largest numbers. Hence our answer is 3, 3, 8.

Below is a detailed explanation.

**From Hint 1: The Product of the ages is 72**

Below are all 12 possibilities to get 72 from the product of three different ages:

1. 1 \* 1 \* 72 = 72
2. 1 \* 2 \* 36 = 72
3. 1 \* 3 \* 24 = 72
4. 1 \* 4 \* 18 = 72
5. 1 \* 6 \* 12 = 72
6. 1 \* 8 \* 9 = 72
7. 2 \* 2 \* 18 = 72
8. 2 \* 3 \* 12 = 72
9. 2 \* 4 \* 9 = 72
10. 2 \* 6 \* 6 = 72
11. 3 \* 3 \* 8 = 72
12. 3 \* 4 \* 6 = 72

```
Shyam was not able to guess the ages of daughter so, he asked for 2nd hint.
```

**From Hint 2: The Sum of the Ages Equals the House Number**

The second hint tells us that the sum of the ages equals the house number. Sum of the ages is given as:

1. 1 + 1 + 72 = 74
2. 1 + 2 + 36 = 39
3. 1 + 3 + 24 = 28
4. 1 + 4 + 18 = 23
5. 1 + 6 + 12 = 19
6. 1 + 8 + 9 = 18
7. 2 + 2 + 18 = 22
8. 2 + 3 + 12 = 17
9. 2 + 4 + 9 = 15
10. 2 + 6 + 6 = 14
11. 3 + 3 + 8 = 14
12. 3 + 4 + 6 = 13

From this, we can see that the **two sets** of daughters have the same sum of 14:

1. 2 + 6 + 6 = 14
2. 3 + 3 + 8 = 14

```
At this point, Shyam is still unsure about the daughters’ ages, so we move to the final hint.
```

**From Hint 3: The oldest girl likes strawberry ice cream.**&#x20;

This hint is important because it tells Shyam there is a **single eldest** daughter. If there were two daughters who were the oldest, Shyam wouldn’t be able to figure out the ages, as there would be ambiguity.

* In the combination **(2, 6, 6)**, there are two daughters who are the oldest (6 years old), so this cannot be the correct answer.
* In the combination **(3, 3, 8)**, there is a single eldest daughter who is 8 years old.

<pre><code><strong>Therefore, the only valid solution is that the daughters’ ages are 3, 3, and 8.
</strong></code></pre>



ans: 3,3,8

