**This category of questions will ask the students to understand the behaviour of an algorithm that solves a given problem**

Relevance: 

Analysis is a discipline within computer science that allows developers to decide between two algorithms, and to get a handle on how an algorithm will perform as the amount of data increases. This is important, despite the speed of modern computers. An inefficient algorithm could take literally thousands of years with quite small amounts of data on very fast computers. (‘Try all routes’ in the Travelling Salesperson problem is one such example.) And an algorithm that is adequate for relatively small amounts of data may be far too slow when the amount of data increases. (Each Google query involves searching terabytes of data, but still gives results in a few seconds.) Analysis of the running time of an algorithm is done by counting ‘operations’, without being concerned with how long the operation takes. A typical operation is ‘compare two numbers’, used in searching and sorting algorithms.

Another objective in analysis is to explore how the complexity of the problem increases as the problem size increases. An inefficient but simple algorithm may be preferred to an efficient but complex one if the complexity of the problem does not increase much as the size of the data increases.


Example: 

Alan, Beth, Con, Dan and Eve have each programmed their pet robots to play a guessing game. The robots have to find a number between 10 and 99, by being told whether its guesses were too high, too low or correct. Each of the robots found the number 17 in 8 guesses:

```
Alan’s robot  10  11  12  13  14  15  16  17 
Beth’s robot  90  70  50  30  10  20  19  17 
Con’s robot   10  99  50  30  20  15  16  17 
Dan’s robot   50  20  10  25  15  19  18  17 
Eve’s robot   90  10  50  20  11  13  16  17
```

Clearly their strategy was not always very good. But only one of the robots made a logic error.
Whose robot was it?

(A) Alan’s    (B) Beth’s   (C) Con’s    (D) Dan’s   (E) Eve’s

2 zabs were born in the year 2000 and 9 zabs were born in 2001. What is the first year after 2000 when just 1 zab will be born?

(A) 2009  (B) 2011  (C) 2013  (D) 2015  (E) 2017

*Solution:* 

If the logic is correct, a ‘too high’ response will give a new high limit, a ‘too low’ response will give a new low limit, and each guess will be between the upper and lower limits of guesses so far. We do not know the responses, but if the logic is correct, we can deduce whether a guess was too high or too low from the next guess.

If the logic in Dan’s robot is correct, its second and third guesses should imply that the target is less than 20. But its fourth guess is 25. So Dan’s robot has made a logic error. Hence (D).
