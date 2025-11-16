# Monty-Hall-Simulator

Inspired by AP Statistics, Conditional Probability & Probability misconception,
this code is a simulation of famously known, a counter-intuitive puzzle, The Monty Hall Problem: to prove that switching increases our chances of winning.

Monty Hall Problem: (What is it about?)
1. There are Three Doors: Behind them are two goats and one sports car.
2. Make Your Choice for a door: You pick a door (1,2,3).
3. Host Opens a Door
4. The host shows a goat behind one of the remaining doors.
5. After he reveals the goat, you make a Final Decision:

Main Question: Should you stick with your door or switch? Or does it matter?


People may assume that chances are 50-50, but it turns out switching would increase more chance!
You'll win 2/3 after switch!

Origin: 
Initially introduced in 1975 in a letter by Steve Selvin to the American Statistician Journal.
This puzzle became even more popular after Monty Halperin, host of Let's Make a Deal, introduced this in this TV show.

Reasoning:
Switching increases our chance of winning because in the first pick, there are 
2/3: Choose goat as a first pick
1/3: Choose car as a first pick

There are higher chances of picking goat as a first pick. 
Then, after host reveals the other door, which showed that it contained a goat, he basically revealed to you that the only was to win is by switching since you chose goat as a first pick. 

Since you pick goat as a first pick are more likely, and the only way to win in this case is by switching, you win more after switch!

Mathematical Reasoning: 
This can be demonstrated in a probability tree diagram, which shows all possible outcomes to win based on your first pick and what Monty does next.

This can be also expressed in the following conditional probability equation called Bayes Theorem. 
e.g.) What's the probability the car is behind Door 1, given Monty opened Door 2?
Probability of car being in door 1 & Monty open Door 2 over total probability of monty opening door 2 is equal to ⅓, which we found earlier. 

Conclusion:
1. Switching increases chances after he reveales one door.
2. The Monty Hall problem reminds us that human intuition can be misleading, and that humans can be easily fooled, but math doesn’t.

Real-World Applications:
1. Quiz shows or test-taking: Spotting and switching from wrong answers.
2. Machine learning: Updating predictions with new evidence.
3. Video games: Risk-reward decisions based on limited info.

New question?: 
What happens when:
1. There are more than 3 doors (e.g., 4 or 100)?
2. You’re allowed to switch multiple times?



