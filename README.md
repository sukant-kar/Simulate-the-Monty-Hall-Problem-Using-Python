# Simulate-the-Monty-Hall-Problem-Using-Python
Let us think about the game show (Let’s Make a Deal) from the shows point of view, the show and the shows host (Monty) knows where there is a goat and where there isn’t a goat and therefore knows which door the prize is behind. So, we are given three doors (Door #1, Door #2, and Door#3). Behind the first door is a goat, behind the second door is a car (our prize) and behind the third door is another goat.
Suppose the contestant chooses Door #1, then the host reveals Door #3 (the goat), since the host knows Door #2 contains the prize car. In this case it is good for the contestant to switch. If the contestant/player switches then the contestant would win the prize. If the contestant/player did NOT switch then the contestant would lose the prize.
Suppose the contestant chooses Door #2, then the host reveals either Door #1 or Door #3. In this case it is bad to switch for the contestant. If the contestant/player switches then the contestant would lose the prize. If the contestant/player did NOT switch then the contestant would win the prize.
Suppose the contestant chooses Door #3, then the host reveals Door #1. In this case it is good for the contestant to switch. If the contestant/player switches then the contestant would win the prize. If the contestant/player did NOT switch then the contestant would lose the prize.
In the above scenario, we can easily see that if the contestant had switched , then the contestant would’ve won 2/3 or about 66.66% of the time and lost only 1/3 or about 33.33% of the time. If the contestant chose not switch, then the contestant would’ve won 1/3 or about 33.33% of the time and lost 2/3 or about 66.66% of the time
Let’s look at the probability of NEVER switching. There are three doors and 1 of the three doors contains the car, your desired prize, while 2 of the three doors contains the undesired prize (the goat). If the contestant chooses to stick with their gut feeling and choose to never switch then the probability of winning is 1/3 and their probability of losing is 2/3.
After staying with your original choice: Probability( Winning) = P(W) = 1/3
After staying with your original choice: Probability (Losing) = P(L) = 2/3
Now let’s take a look at the probability of ALWAYS switching. Let’s think about how you would win if you always switched. Fig. 1 shows three doors containing the goat, car, and goat in that order. If you picked door #1 the host will show you door #3 and you should switch, and if you picked door #3 the host will show you door #1 and you should switch. So if you picked a wrong door (a door containing a goat) and switch you always win, and if you chose the door that contained the prize and then switched, you would lose.
Let’s look at a scenario. Assume the prize is behind door #2 and goats are behind doors #1 and #3.
Scenario #1 for always switching:
1. You choose door #1
2.The host opens door #3 , because the prize is behind door #2, and asks if you want to switch.
3.You decide to switch to door #2
4.YOU WIN!
Scenario #2 for always switching
1.You choose door #2
2.The host opens door #3 or door #1 , because the prize is behind door # 2, and asks if you want to switch.
3.You decide to switch to door #1 or door #3
4.YOU LOSE.
Scenario #3 for always switching
1. You choose door #3
2. The host opens door #1 , because the prize is behind door #2, and asks if you want to switch.
3. You decide to switch to door #2
4. YOU WIN!
From the possible scenarios above where the prize was behind door #2 and you opted to always switch, you would’ve won 2/3 times from switching and lost 1/3 times for switching or vice versa you would’ve won 1/3 of the time by sticking with your choice and lost 2/3 of the time for sticking with your choice.
After switching original choice: Probability ( Winning) = P(W) = 2/3
Probability (Losing) = P(L) = 1/3
By switching doors in this case, your probability of winning is 2/3 and your probability of losing is 1/3 . Another way of thinking about it is, if you choose to switch you double your chances of winning or increase your chances of winning by 1/3 or about 33.33%.
Another More Intuitive Perspective of the Monty Hall Problem:
You may not be convinced yet that switching is better (meaning it gives the player an extra 33.33% chance of winning by switching their original choice to another door for the 3 door scenario) after the host reveals a door that doesn’t have the prize.
So let’s look at a fictional scenario where there are 100 doors, and only one of them contains the prize you want and the rest contains a goat. Let’s say you choose one of the doors randomly (like the last door or Door #100). Your chance of choosing the door with the prize is 1 / 100 which is 1%. The host then reveals to you 98 other doors that contain a goat leaving just your first choice and one other unopened door, so we know one of them contains the prize and the other contains the goat.
Do you still think, given this scenario that you have only a 50% chance of winning by switching or not switching since there are two unrevealed doors left ? Do you think it would be better for you to switch or stay with your original choice ?
By switching your choice you are given an extra 98% chance of getting the prize (meaning by switching you will have a 99% chance of getting the prize) , and your first choice still has only a 1% chance of being right.
If you would like to read more about this remarkable story I suggest you read the book “The Monty Hall Problem: The Remarkable Story of Math’s Most Contentious Brain Teaser”. In this book, the author Jason Rosenhouse explores the history of the Monty Hall puzzle. He shows how the problem has fascinated philosophers, psychologists, and many others, and examines the many variations that have appeared over the years using minimum mathematics.
