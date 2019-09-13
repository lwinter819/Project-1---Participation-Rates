# Project 1: SAT & ACT Analysis

## Problem Statement
SAT participation rates vary from that of ACT participation rates. As a member of the College Board, my goal is to take a look at SAT and ACT data from 2017 and 2018 in order to find ways that can increase participation for the SAT in a financially responsible manner.

## Executive Summary

For this project, I examined SAT and ACT participation rates by state for 2017 and 2018 looking for trends in the data. I used several data sets which included statewide average scores for each section and composite/total scores for both exams. These data sources provided the framework for my data analysis.

After cleaning the data and making sure all data types for each category were correct, I was able to start examining the data in closer detail. I first took a look at SAT vs ACT participation rates in the form of a histogram to see the distribution of both exams. It became clear when seeing the graphs, that the SAT had many more states with lower participation rates than the ACT, while the ACT had many with 100% participation. The ACT is mandatory to take in several states.

Another area I examined was participation rates by region to see if there were any trends. The largest disparity between the two tests was in the south. The south had the lowest SAT participation rate, but had the highest ACT participation. The ACT is mandatory in many southern states. The result of this is that only the most college-driven students will also take the SAT. The students who don't care about college will only take the mandatory exam which causes the gap between the participation rates.

It's important to note, that these tests are not the same. ACT tests different skills and subjects than the SAT. For example, the ACT tests science whilke the SAT does not. This is an important item to keep in mind when thinking about ways to increase the participation rate for the SAT and is what my analysis was motivated by.



### Data Dictionary:

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|ACT/SAT|This is the state the scores for SAT/ACT correspond to.|
|participation_sat_2017|float|SAT|Participation rate for each corresponding state|
|read_write_sat_2017|int|SAT| Average score for the reading/writing section by state|
|math_sat_2017|int|SAT| Average score for the math section by state|
|total_sat_2017|int|SAT| Average total score by state|
|participation_act_2017|float|ACT|Participation rate for each corresponding state|
|english_act_2017|float|ACT|Average score for the english section by state|
|math_act_2017|float|ACT|Average score for the math section by state|
|reading_act_2017|float|ACT|Average score for the reading section by state|
|science_act_2017|float|ACT|Average score for the science section by state|
|composite_act_2017|float|ACT|Average composite score by state|


## Conclusions and Recommendations
After reviewing and analyzing all of the data, I came to the conclusion that the college board should focus their marketing on states with low SAT participation that have the ACT as mandatory. Many of the states that have low SAT participation rates have a 100% participation rate on the ACT since it is mandatory. This is causing the negative correlation between participation rates for the two exams. Many students who have no interest in going to college will only take the one exam, while the most college-driven students will take both.

One way to market the SAT to students to increase the participation rates would be to explain that the two exams are not the same. In my findings, I saw that SAT and ACT scores are negatively correlated. Meaning doing well on one exam, doesn't necessarily mean you will do well on the other and vice versa. Students may not realize that the tests are different and the SAT doesn't even test science knowledge. This is an important message to bring across because many students may be able to increase their chances of going to college by taking the SAT if they performed poorly on the ACT. The south is a region in particular that the college board can focus on due to the large disparity in participation rates.

An area of concern in my research is that overall test scores are negatively correlated with participation rates. If states are concerned with keeping their average test scores up, then increasing participation will not help their cause.

Knowing the percent of students that took both exams would have been extremely useful in my research. It would allow me to look for trends in states where neither exam is mandatory.

Sources -
https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows
https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/
https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=2&cad=rja&uact=8&ved=2ahUKEwi2vPDWgOfiAhUpU98KHb1KAJMQFjABegQIARAC&url=https%3A%2F%2Fwww2.census.gov%2Fprograms-surveys%2Fpopest%2Fgeographies%2F2015%2Fstate-geocodes-v2015.xls&usg=AOvVaw3ltt7GNQSeeGvJjxG53B9I
https://www.edweek.org/ew/articles/2018/10/31/sat-scores-rise-as-number-of-test-takers.html
