# Election_Analysis
Python module on election results

## Overview
This was a Python module on election results dealing with three counties in Colorado, featuring three candidates. The task was to identify the total votes, votes per county, county with largest voter turnout, number and percentage of votes per candidate, and results for the winning candidate. 

## Results
- Total votes are measured by the total overall votes.
- Votes per county are measured by the county name, percentage of votes cast, and number of total votes cast.
- County with largest voter turnout was measured by assessing which county had the largest number of votes cast.
- Number and percentage of votes cast per candidate were based on dividing votes per candatidate against the total.
- Results for the winning candidate were absed on assessing total number of votes won, along with percentage of total.

## Summary
- This script only assesses the three counties and three candidates in one election in the state of Colorado. It was affected by the significantly larger population size of Denver county, and thus its expected larger numbers for turnout. Much of Colorado outside Denver county is rural, thus the measure of all counties in Colorado, not just this sample, but for any given year would likely show Denver county to be even more the outlier. 
- The analysis shows results for an election in a statewide race in Colorado, which is distinct for having three major candidates while many US states have only one or two viable candidates for statewide office. 
- - This script is versatile enough to be applied to much more local races, especially since there is no allowance for national party, which is less salient locally. Party affiliation, if given in the data, could also be easily added. 
- - This script could also be applied to the hyperlocal (e.g., grade-school elections), or international level. If the patterning in the script is followed, it could be applied to any jurisdiction, with the designation of "counties" replaced with others like "province," "township," or whatever is used locally.
