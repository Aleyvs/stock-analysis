# Analysis of all Green Stocks

## Overview of Project
During this analysis we will be helping Steve refactor the previous code we had prepared for him. This new code will loop through all the data in a more efficient manner so that Steve can do a more in-depth analysis of all the dataset. We will provide a comparison of the time the original code takes to run vs the new refactored code. Also, comment on the advantages and disadvantages of refactoring code.

## Results

### Stock Performance Comparison (2017 vs 2018)

The initial purpose of this project was to help Steve analyze the dataset that includes all stocks on green companies so that his parents can take an informed decision on where it's best to invest. Taking a look at the results from 12 different companies through the years of 2017 and 2018 the best option for investments would be to divide their investments between ENPH and RUN. Both this companies show growth during both years and in an important amount.

 ![2017_Results](Resources/2017_results.png)    ![2018_Results](Resources/2018_results.png)     

Steve's parents can now divide their investments between more than one company and not have all their eggs in one basket. Also, Steve can keep using the code in upcoming years to keep an eye on how every company is doing and make an informed decision every year.

### Original vs Refactored Script

Another purpose of this project was to help Steve create a better version of the code that will do the analysis in a more efficient way. With the original script the code goes over all the data 12 times, and brings the information out for one company at a time until it finishes. On the other hand, the refactored code goes into the data only once and uses the stock TickerIndex to travel through the data.
The original script runs the data for 2017 in a little over half a second vs 0.09 seconds for the refactored script. In a similar manner 2018 data for the original script runs in 0.55 seconds and the refactored only takes 0.1 seconds.

#### 2017 Original vs 2017 Refactored
 ![2017_Original_Script_Results](Resources/All_stocks_2017.png)    ![2017_Refacotred_script_Results](Resources/VBA_Challenge_2017.png)              

#### 2018 Original vs 2018 Refactored
![2018_Original_Script_Results](Resources/All_stocks_2018.png)     ![2018_Refactored_Scrpt_Results](Resources/VBA_Challenge_2018.png)  

Maybe with a dataset of this size the time difference is not very significant. But if Steve's parents ever want to broaden their options and see a report of more companies the refactored code only takes 20% of the time the original code takes to run. 

## Summary

 ### Advantages and disadvantages of refactoring code
The main advantage of refactoring code will always be making the code more efficient. This gives the opportunity of running a script in less time, or getting information faster. Also, refactoring to make a code more comprehensible and easier to maintain when different coders work on the same code is a huge advantage. A big disadvantage could be that it could introduce errors or bugs into the code or make it less efficient, and refactoring code is very time consuming, we have to be aware that the change made will be valuable in comparison with the man hours spent refactoring it.

### Pros and cons applied to refactoring the original VBA script

Applying the above points to our refactor work I would say that it is not beneficial in the time vs benefit comparison. If Steve were paying someone to refactor the code it would not be an insignificant cost for the benefit of a fraction of a second. Maybe in this situation keeping the original code could work just as well.
