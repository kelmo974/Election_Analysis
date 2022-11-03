# Election_Analysis
Aggregations and analysis of election data for Colorado counties.


## Purpose

This analysis was conducted in an effort tangential to standard proceedings of democracy. Vote counts in three Colorado counties were aggregated and compared to one another to determine totals by county, percentages of overall vote, and the election winner.


## Methodolgy

Election data was sourced from a .csv files and imported into a VS Code python interpretor by relying on base modules csv and os. Once the data was read, a series of lists and dictionaries was created so that variables could be assigned before carrying out aggregations. Results of the aggreations were written to a .txt file that is found along this README and the PyPoll_Challenge file. 

## Results

Not surpsingly, Denver county recorded the greatest number of votes cast. This heavily influenced the election outcome. Denver votes accounted for 82.8% of the total votes, while Jefferson and Arapahoe provided 10.5% and 6.7%, respectively. Diana DeGette won the election in a landslide by receiving 73.8% of the votes.

## Summary
This approach was an exciting way to learn about the capabilities of the channeling python libraries through VS Code as the capabilities of the python shell wouldn't have enabled for saving of the script as readily nor catered to beginnger skills with color-coding and indention alerts. Overall, this analysis captured the end results of the election, but would require a deeper dive to produce more refined insights such as voter sentiment and/or extrapolting for other counties and future elections.
