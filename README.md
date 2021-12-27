# Stocks Analysis
## Overview of Project
Steve in interesreted in stocks and needs help analyzing some stock data. Steve wants to find the total daily volume and yearly return for each stock. Daily volume is the total number of shares traded throughout the day; it measures how actively a stock is traded. The yearly return is the percentage difference in price from the beginning of the year to the end of the year.

### Purpose
We created a VBA program to collect stock infomration in 2017 and 2018. We refactored the program to make it more quicker and efficient than the previous program. 

## Results
[2017](VBA_Challenge_2017.png)

[2018](VBA_Challenge_2018.png)

The data shows 12 different stocks and in 2017, 11 of the 12 tickers have recieved a positive return, even some stocks got over 100% return. However, in 2018, all the companies returns dropped and 10 of the 12 companies returns were negative. There was no correlation with the volume of each ticker, becuase some on the daily volume increased and some decreased between 2017 and 2018. 

## Summary

- After refatoring the code, our program was more efficent and was put in one place. When calling the subroutines, it was nice to only call on subroutine, instead of calling individual ones. For example, before we had a subroutine to call the data to the table and another subroutine to design and format the table. Now that we have in all one subroutine, we can  The biggest advantage after refactoing was the decreased run time. Before, it took my computer about 0.4 seconds to run, but now it is only 0.007 seconds. This is great for Steve if he decided to analyze over 1000 different kinds of tickers, so he can get his analysis in seconds instead of minutes. Below, we can see in the first picture how long it took just to run the analysis from the original code. In the second picture, we can see how much faster is was with the refactored code, which not only ran the analysis, but also formated the table. 

<img width="242" alt="image" src="https://user-images.githubusercontent.com/58046234/147486736-88eb84c0-41c7-435a-b166-fa52e270f8ea.png"> <img width="244" alt="image" src="https://user-images.githubusercontent.com/58046234/147486360-865e65ca-a0d7-47a4-91f3-80f777648853.png">
- However, after refactoring our code and putting all together, it was harder to test each indivdual section. Before, we had multiple subroutines and we would check if each subroutine was running properly and it was easier to debug. However, after combining everything into one subroutine, it took a longer time to test and debug the program. 

