# Monty Hall problem

The Monty Hall problem is a surprising probability puzzle:

* There are 3 doors—two hide goats, and one hides a car.
* You pick one door (let’s call it door 2), hoping it has the car.
* The game show host, Monty Hall, then looks at the other two doors (1 and 3) and opens one that has a goat behind it (Say 3). (If both doors have goats, he chooses one at random.)

He then says to you, "Do you want to pick door 2 or stick to door 1.

What do you decide to have better chances of winning a car?

\


![monty\_hall](https://media.geeksforgeeks.org/wp-content/uploads/20250722165253621826/monty_hall.webp)

#### &#x20;Check if you were right - full answer with solution below. <a href="#check-if-you-were-right-full-answer-with-solution-below" id="check-if-you-were-right-full-answer-with-solution-below"></a>

**Solution:** The main trick is that the host would open the door with a goat only, so the chances of the other door having a car are higher. Hence, you should always switch to improve your chances. Below is a detailed solution.

Let’s solve the Monty Hall problem step by step, assuming the gates are numbered 1, 2, and 3:

**Setup:**

* **Player’s choice:** The player initially picks **gate 2**.

The car is equally likely to be behind any of the three gates initially. Let’s evaluate the three possible arrangements:

**1. Car behind gate 1:**

* Player picks gate 2 (initial choice).
* Host must open gate 3, showing a goat (since gate 1 has the car).
* **Switching to gate 1 wins the car.**

**2. Car behind gate 2:**

* Player picks gate 2 (initial choice).
* Host opens gate 3, showing a goat.
* **Switching to gate 1 loses, as the car is behind gate 2.**

**3. Car behind gate 3:**

* Player picks gate 2 (initial choice).
* Host cannot open gate 3 because it has the car. Instead, he opens gate 1, showing a goat.
* **Switching to gate 3 wins the car.**

**Summary of outcomes:**

* In **2 out of 3 scenarios**, switching wins the car.
* In **1 out of 3 scenarios**, staying with the initial choice wins.

**As probability of winning a car by switching is higher than not switching. It is advantage to switch.**

