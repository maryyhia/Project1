
# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Test Analysis


### Overview

Our first module in DSI covers:
- Basic statistics and probability
- Many Python programming concepts
- Programmatically interacting with files and directories
- Visualizations
- EDA
- Working with Jupyter notebooks for development and reporting

## Problem Statement
#### With the change in format for the SAT in 2016, the participation rates across the states have changed in varying levels as well. This project is directed towards states where Ivy League schools are located in and identify if this new format has a positive effect on their participation rates. 

## Target audience
- Non-technical College Board representatives

## Data sources
### Data provided
* [SAT](https://collegereadiness.collegeboard.org/sat)
 * [`sat_2017.csv`](./data/sat_2017.csv): 2017 SAT Scores by State ([source](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/))
* [`sat_2018.csv`](./data/sat_2018.csv): 2018 SAT Scores by State ([source](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/))
* [`sat_2019.csv`](./data/sat_2019.csv): 2019 SAT Scores by State ([source](https://blog.prepscholar.com/average-sat-scores-by-state-most-recent))

### Additional sources
- [SAT new format 2016](https://sat.ivyglobal.com/new-vs-old#:~:text=The%20College%20Board%20made%20content,in%20the%20spring%20of%202016.)
- [SAT new format and why it was changed](https://blog.prepscholar.com/complete-guide-to-the-new-sat-in-2016)
- [List of Ivy League schools](https://en.wikipedia.org/wiki/Ivy_League#Members)
- [The College Board](https://en.wikipedia.org/wiki/College_Board)
- [States that require SAT](https://blog.prepscholar.com/which-states-require-the-sat)


## Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|sat2017df|data frame|SAT|Imported SAT 2017 data
|sat2018df|data frame|SAT|Imported SAT 2018 data 
|sat2019df|data frame|SAT|Imported SAT 2019 data
|combined_sat|data frame|SAT| Combined data frame of cleaned filtered data from 2017, 2018, and 2019
|ivyleague_sat|list|States|List of states with Ivy League schools
|ivyleague_part|data frame|SAT|Only containing participation rates of years 2017, 2018, and 2019, against the states
|ivyleague_prc|date frame|SAT|Only containing percentage change rates between the years against the states


## Summary of analysis
Taking in account that some of the Ivy League states requires their students to take the SAT, there is still a positive effect from the new change in format which resulted in an increase in participation rates across the years 2017, 2018, and 2019. 

## Conclusions/ Recommendations

