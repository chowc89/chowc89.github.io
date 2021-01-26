---
layout: project
type: project
image: images/mct.PNG
title: Money Calculator
permalink: projects/Money Calculator
# All dates must be YYYY-MM-DD format!
date: 2021-01-20
labels:
  - Java
summary: A Money Calculator that calculate the money return to customers.
---

<img class="ui image" src="../images/mc1.PNG">
  
Many people think that carrying too much change will make it inconvenient. Therefore, people hope that the store clerk can give them back the least number of coins instead of filling them with a bunch of pennies. So, like we have pennies, nickels, dines, and quarters, if the we need to give back 31 cents, how many ways can we do it? We can give back 31 pennies, gave back a quarter, a nickel, and a penny, or gave back 3 dines, and a penny. If the we give back a quarter, a nickel, and a penny which is only three coins, and it is way better than giving back 31 pennies.
You might think, isn't this a simple question? Just start with the coin’s large denomination. This is true, but what if there’s another denomination of 21? Let say we have denominations of 1, 5, 10, 21, and 25. If we need to give back 63 cents, how many ways can we do it? If we start from the largest denomination, we will need a 25, a 10, three 1s, total is 6 coins. This is not the best answer to this problem, because we have the denomination of 21 now. We can use three 21s to make up to 63. Of course, it is also because this problem has been designed to allow us to quickly find the best solution. If we change to other numbers, it may not be so easy.
In order to find the solution in the fastest way, programmers design a program that will do all the calculation, and find the best solution for the question. I was curious about how does this machine operate, so I decided to make one. During high school, my professor introduce java to me, and this money calculator naturally became one of the projects I made during that period. This money calculator will ask the users to input the price and payment, and it will calculate the number of each denominations of money that need to return to consumer. For example, if you input enter $450 for the price, and $1000 for payment, it will display one "$500" and one "$50". However, this calculator only displays New Taiwan dollar as the main currency, it can be improved by adding more currency of different countries.

