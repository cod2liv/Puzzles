# Puzzles

5June, 2023

1. The Two Egg Problem:
You are given two eggs and access to a 100-story building. You need to find the highest floor from which an egg can be dropped without breaking. What is the minimum number of attempts required to find the solution? Provide the strategy as well.
Solution: The optimal solution involves a binary search approach. Start by dropping an egg from the 50th floor. If it breaks, continue the search from floors 1 to 49; if it doesn't break, continue from floors 51 to 100. This approach ensures a maximum of 50 attempts.

2. The Bridge and Torch Problem:
Four people need to cross a bridge at night. They have only one torch, and it takes different times for each person to cross the bridge. Only two people can cross at a time, and someone has to bring the torch back each time to accompany the others. The challenge is to find the minimum time required for all four people to cross the bridge.
Solution: The optimal solution involves careful planning. The two fastest people initially cross with the torch. One of them returns with the torch, while the other two cross together. Finally, one of the two remaining people with the torch goes back to accompany the last person across.

6 June, 2023

3. The Prisoner Hat Riddle:
There are 100 prisoners in solitary cells. There's a room with 100 hats, 50 black and 50 white. Each prisoner can only see the other prisoners' hats but not their own. The prisoners must guess the color of their own hat simultaneously. How can they maximize the number of correct guesses?
Solution: The prisoners agree on a strategy beforehand. The first prisoner counts the number of black hats they see. If the count is even, they say "black." If it's odd, they say "white." Each subsequent prisoner counts the number of black hats they see plus the previous prisoner's guess. Following this strategy, at least 50 prisoners will guess their hat colors correctly.

4. The Poisoned Wine Problem:
You have 1,000 bottles of wine, and one of them is poisoned. You also have 10 test strips that can detect poison when applied to a bottle. However, each strip can only be used once. How can you determine which bottle is poisoned in the minimum number of tests?
Solution: Assign each bottle a unique number in binary, and label each test strip with the corresponding bit position (1, 2, 4, 8, etc.). Take one drop from each bottle and put it on the strip associated with its binary representation. By observing which test strips change color, you can determine the poisoned bottle.

7 June, 2023

5. The Three-Light Switches Problem:
You are in a room with three light switches, each corresponding to a different bulb in another room. You don't know which switch corresponds to which bulb. You can only go into the other room once. How can you determine which switch corresponds to each bulb?
Solution: Start by turning on the first switch and waiting for a few minutes. Then turn off the first switch and turn on the second switch. Immediately enter the other room. The bulb that is on corresponds to the second switch. The bulb that is off and feels warm corresponds to the first switch, and the bulb that is off and feels cool corresponds to the third switch.

6. The 25 Horses Puzzle:
You have 25 horses and can race them in groups of five. However, you can only use one stopwatch, and it can only measure time in seconds. What is the minimum number of races required to determine the three fastest horses?
Solution: Divide the 25 horses into five groups and race them. Take the top horse from each group and race them in a second race. The top horse in the second race is the fastest horse overall. Take the second and third-place horses from the second race and combine them with the second-place horse from the first race. Race them in a third race, and the top horse in this race is the second-fastest overall. The third-fastest horse can be determined by comparing the remaining horses that haven't participated in the third race.

8 June, 2023

7. The 8-Quart and 3-Quart Water Jug Puzzle:
You have two jugs, one with a capacity of 8 quarts and the other with a capacity of 3 quarts. You need to measure exactly 4 quarts of water. How can you do it?
Solution: Fill the 8-quart jug fully. Pour its contents into the 3-quart jug until it is full, leaving 5 quarts in the 8-quart jug. Empty the 3-quart jug. Pour the remaining 5 quarts from the 8-quart jug into the 3-quart jug. Refill the 8-quart jug and pour exactly 1 quart into the 3-quart jug until it is full. This leaves exactly 4 quarts in the 8-quart jug.

8. The Two Trains Puzzle:
Two trains are on the same track, heading towards each other. Train A is traveling at 100 km/h, and Train B is traveling at 120 km/h. A bird starts flying from Train B towards Train A at a speed of 150 km/h. When the bird reaches Train A, it instantly turns and flies back towards Train B. The bird continues flying back and forth until the two trains collide. How much distance did the bird travel?
Solution: The bird's speed is irrelevant. Since the bird flies back and forth until the trains collide, it means the trains will collide at the midway point between their initial positions. Therefore, the distance traveled by the bird is half the distance between the two initial positions of the trains.

9 June, 2023

9. The Fox, Chicken, and Grain Puzzle:
You have a fox, a chicken, and a bag of grain. You need to cross a river in a small boat, but you can only take one item at a time. The problem is that the fox will eat the chicken if left alone with it, and the chicken will eat the grain if left alone with it. How can you transport all three across the river without any of them being eaten?
Solution: Follow these steps:

Take the chicken across the river and leave it on the other side.

Return alone to the initial side.

Take the fox across the river and leave it on the other side.

Take the chicken back to the initial side.

Leave the chicken on the initial side and take the grain across the river.

Leave the grain with the fox on the other side.

Return alone to the initial side.

Finally, take the chicken across the river one last time.

10. The 100 Prisoners and Light Bulbs Problem:
There are 100 prisoners in solitary cells, each with a switch that controls a light bulb in the central room. The prisoners don't know the initial state of their switches or the bulbs. They are taken to the central room one at a time and can flip any number of switches. The room is initially dark, and the goal is for each prisoner to determine when their switch controls their own bulb. Once a prisoner makes a guess, they cannot communicate with the others. How can they achieve a 100% success rate?
Solution: The first prisoner who enters the room turns on all the switches. The second prisoner who enters the room checks the status of the light bulb. If it is on, they know it's their switch that controls it. If it's off, they know it's either their own switch or the previous prisoner's. The second prisoner then turns off all the switches except their own. Each subsequent prisoner follows the same strategy. Eventually, the 100th prisoner will find their switch controls their own bulb, and all prisoners have determined the correct state of their switches.

11 June, 2023

11. The Water Jug Puzzle (Variant):
You have two jugs, one with a capacity of 5 quarts and the other with a capacity of 3 quarts. You need to measure exactly 4 quarts of water. How can you do it?
Solution: Fill the 5-quart jug fully. Pour its contents into the 3-quart jug until it is full, leaving 2 quarts in the 5-quart jug. Empty the 3-quart jug. Pour the remaining 2 quarts from the 5-quart jug into the 3-quart jug. Fill the 5-quart jug again, and pour 1 quart into the 3-quart jug until it is full. This leaves exactly 4 quarts in the 5-quart jug.

12. The Triangle Within a Circle Puzzle:
Given a circle, draw a straight line that intersects the circle at exactly three points.
Solution: Draw any chord (a straight line segment within the circle that connects two points on the circle). The chord will intersect the circle at exactly two points, and the line extended from the chord will intersect the circle at a third point, resulting in a total of three points of intersection.

12 June, 2023

13. The Prisoner Hat Riddle (Variant):
There are 100 prisoners in solitary cells, each with a hat that is either black or white. They can't see their own hat but can see the hats of the prisoners in front of them. Starting from the last prisoner, each prisoner guesses the color of their own hat or passes. If a prisoner guesses incorrectly, they are executed. The prisoners can discuss a strategy beforehand. What strategy can they use to maximize the number of prisoners who survive?
Solution: The prisoners agree on a strategy. They choose a "leader" among them who will count the number of black hats they see in front. The leader will guess the color of their own hat based on the parity (even or odd) of the count. The other prisoners will guess "pass" if their count matches the leader's guess or guess the opposite color if it doesn't. This way, at least 50 prisoners will survive.

14. The Weighing Balance Puzzle:
You have 12 identical-looking coins, and one of them is counterfeit, either lighter or heavier than the rest. You also have a weighing balance. What is the minimum number of weighings required to determine the counterfeit coin and whether it's lighter or heavier?
Solution: Divide the 12 coins into three groups of four. Weigh two of the groups against each other. If they balance, the counterfeit coin is in the third group. If they don't balance, take the group that is lighter (assuming the scale tipped to that side) and select any two coins from that group. Weigh these two coins against each other. If they balance, the third coin is the counterfeit and lighter. If they don't balance, the lighter coin is the counterfeit and lighter. This solution requires a maximum of two weighings.

13 June, 2023

15. The Two Guards and Two Doors Puzzle:
You are in a room with two doors. One door leads to certain death, while the other door leads to freedom. There are two guards, one in front of each door. One guard always tells the truth, and the other always lies. You don't know which guard is which, nor which door leads to freedom. You can ask one guard one question to determine the correct door. What question should you ask?
Solution: Ask either guard, "If I were to ask the other guard which door leads to freedom, what would they say?" Then choose the opposite door that the guard indicates. Since one guard always tells the truth and the other always lies, regardless of which guard you ask, they will both point to the same door, which is the door to certain death. Therefore, you should choose the opposite door.

16. The Square Within a Circle Puzzle:
Given a square, draw a circle that intersects the square at exactly four points.
Solution: Draw the circle such that its center coincides with the center of the square. The circle will intersect the square at the four corners of the square.

14 June, 2023

17. The Escape Room Puzzle:
You are trapped in a room with two doors. One door leads to freedom, while the other door leads to certain death. Each door is guarded by a single guard. One guard always tells the truth, and the other always lies. You don't know which guard is which, nor which door leads to freedom. You can ask only one guard one question to determine the correct door. What question should you ask?
Solution: Ask either guard, "If I were to ask the other guard which door leads to freedom, what would they say?" Then choose the opposite door that the guard indicates. Since one guard always tells the truth and the other always lies, regardless of which guard you ask, they will both point to the same door, which is the door to certain death. Therefore, you should choose the opposite door.

18. The Chessboard and Dominos Puzzle:
You have a standard 8x8 chessboard with two opposite corners removed. Is it possible to cover the remaining 62 squares of the chessboard with 31 dominos (each dominos covers exactly two adjacent squares) without overlapping or extending beyond the board's boundaries?
Solution: No, it is not possible. Each domino always covers one black square and one white square. However, the chessboard has an equal number of black and white squares, but with two opposite corners removed, it will have 30 squares of one color and 32 squares of the other. Therefore, it is not possible to cover all 62 remaining squares with dominos.

15 June, 2023

19. The Three Ants Puzzle:
Three ants are randomly placed on the vertices of an equilateral triangle. Each ant randomly picks a direction and starts walking along the edge of the triangle. What is the probability that none of the ants collide (i.e., they don't end up on the same vertex)?
Solution: There are two possibilities for each ant: they move in a clockwise direction or in a counterclockwise direction. Since each ant has two choices, the total number of possible outcomes is 2^3 = 8. Out of these 8 outcomes, there is only one outcome where none of the ants collide (when they all move in the same direction, either clockwise or counterclockwise). Therefore, the probability that none of the ants collide is 1/8.

20. The Four Digit Number Puzzle:
Find a four-digit number that, when multiplied by 4, yields the same four digits in a different order.
Solution: The four-digit number is 2178. When multiplied by 4, it results in 8712, which contains the same four digits as the original number but in a different order.

16 June, 2023

21. The Blue-Eyed Island Puzzle:
On an island, there are 100 people, each with either blue or green eyes. They live in isolation and have no communication with the outside world. They are all perfect logicians and can see each other's eye colors but not their own. The island has a rule: If anyone can determine their own eye color, they must leave the island the following morning at dawn. No one is allowed to communicate their eye color to others. Given that everyone knows the rule and everyone can see the eye colors of others, how many days will it take for all the blue-eyed people to leave the island?
Solution: If there is only one person with blue eyes, they will leave on the first day. If there are two people with blue eyes, they will both leave on the second day, as each person can deduce that if the other blue-eyed person saw no one else with blue eyes, they must be the one with blue eyes. Similarly, for three blue-eyed people, they will all leave on the third day, and so on. Therefore, if there are n blue-eyed people, it will take n days for all of them to leave the island.

22. The Monty Hall Problem:
You are a contestant on a game show, and there are three doors. Behind one door is a car, and behind the other two doors are goats. You pick a door (let's say Door 1), and then the host, who knows what's behind each door, opens another door (let's say Door 3) to reveal a goat. The host then asks if you want to switch your choice to the remaining unopened door (Door 2) or stick with your initial choice (Door 1). What should you do to maximize your chances of winning the car?
Solution: The optimal strategy is to switch your choice to the remaining unopened door (Door 2). By switching, your chances of winning the car increase from 1/3 to 2/3. This can be counterintuitive but can be proven through probability calculations.

17 June, 2023

23. The Five Pirates Puzzle:
Five pirates find a chest of gold coins containing 100 pieces. They have to decide how to divide the coins among themselves. The pirates have a strict order of seniority, and the most senior pirate proposes a distribution plan. All the pirates, including the proposer, vote on the plan, and if a majority (more than half) accepts it, the coins are divided accordingly. If the majority rejects the plan, the proposer is thrown overboard, and the next senior pirate becomes the proposer. The process repeats until a plan is accepted. What distribution plan should the most senior pirate propose to maximize their own share while keeping the others alive?
Solution: The most senior pirate proposes that they keep 98 coins for themselves and give one coin each to the second and third senior pirates. If they proposed anything less than this, they would get voted out. If the most senior pirate is the only one left, they will keep all 100 coins for themselves.

24. The Crossing the River with a Wolf, Goat, and Cabbage Puzzle:
You need to transport a wolf, a goat, and a cabbage across a river using a boat. However, the boat can only hold you and one of the three items at a time. If you leave the wolf alone with the goat, the wolf will eat the goat. If you leave the goat alone with the cabbage, the goat will eat the cabbage. How can you transport all three items across the river without any of them being eaten?
Solution: Follow these steps:

Take the goat across the river and leave it on the other side.

Return alone to the initial side.

Take the wolf across the river and leave it on the other side.

Take the goat back to the initial side.

Leave the goat on the initial side and take the cabbage across the river.

Leave the cabbage with the wolf on the other side.

Return alone to the initial side.

Finally, take the goat across the river one last time.

18 June, 2023

25. The Broken Bar of Chocolate Puzzle:
You have a rectangular bar of chocolate that is divided into small squares. One of the squares is poisoned. You can break the bar of chocolate along the lines between the squares. However, you can only break it in one straight line. How can you guarantee that you can identify the poisoned square with the fewest number of breaks?
Solution: Break the chocolate bar along the middle row, horizontally. This way, you will have two halves of the bar. If the poisoned square is in the top half, repeat the process with that half. If the poisoned square is in the bottom half, repeat the process with that half. By continuously breaking the half that contains the poisoned square, you will eventually be left with only one square, which is the poisoned one.

26. The Three Bulbs and Three Switches Puzzle:
You have three light bulbs and three switches outside a closed room. Each switch corresponds to one light bulb inside the room. You can toggle the switches as many times as you want but can only enter the room once. How can you determine which switch corresponds to which light bulb?
Solution: Turn on the first switch and leave it on for a few minutes. Then turn it off and turn on the second switch. Enter the room. The bulb that is on corresponds to the second switch. The bulb that is off but warm corresponds to the first switch, and the bulb that is off and cool corresponds to the third switch.

19 June, 2023

27. The Nine Coins Puzzle:
You have nine seemingly identical coins, but one of them is counterfeit and weighs either more or less than the others. You have a balance scale to use, but you can only use it twice. How can you identify the counterfeit coin and determine whether it's heavier or lighter in just two weighings?
Solution: Divide the coins into three groups of three. Weigh two of the groups against each other. If they balance, the counterfeit coin is in the third group. If one group is heavier, it contains the counterfeit coin. Take two coins from that group and weigh them against each other. If one is heavier, it's the counterfeit coin. If they balance, the remaining coin is the counterfeit one.

28. The 100 Prisoners, 100 Boxes, and Random Shuffling Puzzle:
There are 100 prisoners and 100 boxes. Each prisoner is assigned a unique number from 1 to 100. The boxes are also numbered from 1 to 100. Initially, all the boxes are closed. The prisoners are taken one by one into a room with the boxes. Each prisoner can open and inspect up to 50 boxes of their choice (once a box is opened, it cannot be closed again). If any prisoner finds their assigned number in one of the boxes they open, they are freed. However, if all prisoners have finished inspecting their 50 boxes and none of them have found their assigned number, they are all executed. The prisoners can agree on a strategy beforehand, but once inside the room, they cannot communicate. What strategy should they use to maximize their chances of survival?
Solution: Beforehand, the prisoners agree that the first prisoner will open every box. The second prisoner will open every second box (2, 4, 6, ...), the third prisoner will open every third box (3, 6, 9, ...), and so on. This way, each prisoner will inspect the boxes that are multiples of their assigned number. This strategy guarantees that every number from 1 to 100 is inspected at least once, maximizing their chances of finding their assigned number and surviving.

20 June, 2023

29. The Four Weights and a Balance Scale Puzzle:
You have four weights of 1kg, 2kg, 3kg, and 4kg, but they are not labeled. You also have a balance scale. How can you determine the weight of each individual weight using the balance scale only twice?
Solution: First, place the 1kg and 2kg weights on one side of the scale and the 3kg weight on the other side. If they balance, the 4kg weight is the remaining one. If they don't balance, the heavier side contains the 4kg weight. In the second weighing, take the remaining two weights and place one on each side of the scale. If they balance, the remaining weight is the 3kg one. If they don't balance, the heavier side contains the 3kg weight.

30. The Two Missing Numbers Puzzle:
You are given an array of numbers from 1 to n, with two numbers missing. How can you find the missing numbers in O(n) time and O(1) space complexity?
Solution: Let the given array be A, and let n be the length of the array A + 2. Calculate the sum of numbers from 1 to n using the formula: sum_of_numbers = n * (n + 1) / 2. Calculate the sum of all elements in array A as sum_of_array_elements. Subtract sum_of_array_elements from sum_of_numbers to get the total of the two missing numbers. Now, you have the sum of the two missing numbers and their product. You can set up a quadratic equation using these values and solve for the two missing numbers.




















