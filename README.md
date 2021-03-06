# VBA_Challenge
 repository for VBA challenge.
 
## Overview of Project

The purpose of this challenge is to use VBA code to facilitate the analysis of a series of stocks by the end user. Using VBA we hope to create a summary table, easy to read and visualize. To ensure optimal performance and scalability of the *VBA Code*, we will challenge ourselves to refactor the script to make it more efficient. (eg. Having the VBA script successfully run faster, using less memory and making it easier to read)


## Results

As a result of the refactoring process the vba scripts run time has been improved around *84% ~ 83%*, as shown in Image 1.1 the original script took 0.89 seconds to run, while the new refactored code ran in 0.14 (Image 1.2). A similar improvement in the scripts run time can be seen for the analysis for 2018, where the run time decreased  from about 0.92 (Image 2.1) to 0.15 seconds(Image 2.2).

### 2017 Analysis Screenshoots

**Image 1.1: Original Script Run Time for 2017 Analysis.**
![Original 2017](https://github.com/calvogeorge/VBA_Challenge/blob/baac2fb730b274d978f609b323ba7d2c3b60c878/Resources/VBA_Challange_2017_Original.png)

**Image 1.2: Refactored Script Run Time for 2017 Analysis.**
![Refactored 2017](https://github.com/calvogeorge/VBA_Challenge/blob/baac2fb730b274d978f609b323ba7d2c3b60c878/Resources/VBA_Challenge_2017_RF.png)

### 2018 Analysis Screenshoots

**Image 2.1: Original Script Run Time for 2018 Analysis.**
![Original 2018](https://github.com/calvogeorge/VBA_Challenge/blob/560737f42743ac1f5cfc7e1fd34ce4564af09e9c/Resources/VBA_Challange_2018_Original.png)

**Image 2.2: Refactored Script Run Time for 2018 Analysis.**
![Refactored 2018](https://github.com/calvogeorge/VBA_Challenge/blob/560737f42743ac1f5cfc7e1fd34ce4564af09e9c/Resources/VBA_Challenge_2018_RF.png)


## Summary

### Advantages and Disadvantages of Refactoring Code.

Advantages of Refactoring code is that it allows you to improve a script by eliminating redundancies, improving the readability, understanding of the code, and potentially making it easier to maintain. A disadvantage is that the process can be time consuming while not offering guarantees that you will be able to achieve a more efficient code.


### Advantages and Disadvantages of the Original Code and the Refactored Code.

The original script has is faster to code, as you are only following the logical steps you need your code to follow, without little consideration on redundancies that might arise from later in the code. Being an obvious disadvantage, the fact the code could contain redundancies, slowing it down and reducing efficiency. In this project our original code contained an extra **for loop**, that while it help us obtain the desired results it slowed down the execution of the script. Eliminating this extra loop is an advantage in the refactored code.

