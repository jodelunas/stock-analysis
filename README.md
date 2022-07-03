# Refactoring VBA

## Overview of Project

The purpose of this project was to refactor the previous solution code, to see if refactoring shortened the length of time for the code to run. The original code works well for the 12 stocks, but might not be efficient for a larger amount of stocks in the future.

## Results

Both codes produced the same results, showing 2017 was a much better year. By refactoring, and creating a ticker index, with the code Dim tickerIndex, it ran much faster. This allowed for all tickers to be run simutaneously. The differences in time are shown in the images below.

![image](https://user-images.githubusercontent.com/106006911/173867278-797aedc1-f222-45b9-920b-627b0b9ed0f9.png)      
![image](https://user-images.githubusercontent.com/106006911/173867758-c77e4a53-b935-47f7-b4ce-c87e02d68749.png)
![image](https://user-images.githubusercontent.com/106006911/173867999-e6edd4f0-f016-4924-bbad-a3c34226a705.png)
![image](https://user-images.githubusercontent.com/106006911/173868165-5dc1b482-5393-42e1-88ba-11e6bc5a1f55.png)




## Summary

The advantage of refactoring code, is to make it run more efficiently and faster. The disadvantage, is that you are more likely to run into errors. This also will take  more time to write.

The advantage for this challenge, was that it did run much faster. The results were the same. The disadvantage, was the time and difficulty it took to refactor it. The small data set that is being used, does not make this an affective use of time. For a larger data set, this would be a better use of time. 
