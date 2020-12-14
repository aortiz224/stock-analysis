# Stock Analysis

## Overview of Project
Steve has asked us to expand the stock analysis to include the entire stock market over the last few years. In order to do this, we will need to refactor our existing code to make our code more efficient and to be able to run faster.

## Results :chart_with_upwards_trend:
Let's deep dive on the Stock Analysis we performed. Overall, for the stocks we evaluated, 2017 had a better performance than 2018. Specifically, tickers **ENPH** and **RUN** both had positive returns year over year. **DQ** on the other hand, even though the trading volume increased by approximately 300% from 2017, it had a negative return of 62.6% in 2018. Steve is better off evaluating and recommending stocks other than **DQ** for his parents.

In my block of code, by initializing a ticker index as shown below, I was able to refactor my code so that the respective arrays read from the ticker index. Therefore, making the code run faster and efficient .
```
    tickerIndex = 0
 
    Dim tickerVolumes(12) As Long
    Dim tickerStartingPrices(12) As Single
    Dim tickerEndingPrices(12) As Single 
 ```

The images below show the amount of time it took the code to run for each year. For comparison, the originl code took about 0.49 seconds.

![VBA_Challenge_2017](https://user-images.githubusercontent.com/74662680/102029809-f412a100-3d7d-11eb-8f84-51d6692f06f9.png)

![VBA_Challenge_2018](https://user-images.githubusercontent.com/74662680/102029854-2ae8b700-3d7e-11eb-97bd-a0555e2baa95.png)

## Summary 

Refactoring code comes with its advantages and disadvantages. A refactored code:
1. is more readable to a coder who may not be familiar with the code, 
2. reduces repetitiveness by defining more variables, and 
3. runs faster by making the code more efficient at the task it is assigned to do. 

On the other hand, refactoring code is time consuming. We're trying to achieve what we already have with a more efficient code but the time savings may not outweight the cost. It begs the phrase, "If it ain't broke, don't fix it." In the end, we are coders and trying to figure out easier and better ways to achieve a particular result is the name of the game.

When taking into account the original and refactored VBA script, yes the code ran faster (advantage) but only by small fractions of a second as mentioned in the *Results* section above. The time spent to refactor the code took significantly longer than the time savings the refactored code generated (disadvantage). 
