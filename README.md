# Election_Analysis
This was a Python module on election results dealing with three counties in Colorado, featuring three candidates. 

## Overview
The task was to identify the total votes, votes per county, county with largest voter turnout, number and percentage of votes per candidate, and results for the winning candidate. 
### Total vote count:
369,711. 

County breakdown:
* Denver county had the highest number of votes. 
- - Denver county had 306,055 votes for 82.8%
- - Jefferson county had 38,855 votes for 10.5%
- - Arapahow county had 24,801% for 6.7%
### Winner: 
  Dianna DeGette won the election, with 272,892 votes, 73.8% of the total votes.


## Results
- Total votes are measured by the total overall votes.
- Votes per county are measured by the county name, percentage of votes cast, and number of total votes cast.
- County with largest voter turnout was measured by assessing which county had the largest number of votes cast.
- Number and percentage of votes cast per candidate were based on dividing votes per candatidate against the total.
- Results for the winning candidate were absed on assessing total number of votes won, along with percentage of total.

## Summary
- This script only assesses the three counties and three candidates in one election in the state of Colorado. It was affected by the significantly larger population size of Denver county, and thus its expected larger numbers for turnout. Much of Colorado outside Denver county is rural so the the measure of all counties in Colorado for any given year would likely show Denver county to be even more the outlier. 
- The analysis shows results for an election in a statewide race in Colorado, which is distinct for having three major candidates while many US states have only one or two viable candidates for statewide office. 
- - This script is versatile enough to be applied to much more local races, especially since there is no allowance for national party, which is less salient locally. Party affiliation, if given in the data, could also be easily added. 
- - This script could also be applied to the hyperlocal (e.g., grade-school elections), or international level. If the patterning in the script is followed, it could be applied to any jurisdiction, with the designation of "counties" replaced with others like "province," "township," or whatever is used in the given jurisdiction.
