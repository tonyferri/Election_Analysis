# Election Analysis:
Using Python to analyze election results.

## Overview of Election Audit:
The intention of this audit is to summarize election results by winning candidate and number / percentage of votes in order to officially submit them to the election commission.  Additional information was requested to summarize total vote and percentage by county, as well as county with the highest total turnout of voters.

## Election Audit Results:
* How many votes were cast in this congressional election?
    * 369,711
* Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
    * Jefferson: 10.5% (38,855)
    * Denver: 82.8% (306,055)
    * Arapahoe: 6.7% (24,801)
* Which county had the largest number of votes?
    * Denver
* Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
    * Charles Casper Stockham: 23.0% (85,213)
    * Diana DeGette: 73.8% (272,892)
    * Raymon Anthony Doane: 3.1% (11,606)
* Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
    * Diana DeGette: 73.8% (272,892)

[Election Results Summary](https://github.com/tonyferri/Election_Analysis/blob/main/Resources/election_results_txt_file.png);
[Code Example 1: For Loop](https://github.com/tonyferri/Election_Analysis/blob/main/Resources/code_forloop_county.png);
[Code Example 2: Winner](https://github.com/tonyferri/Election_Analysis/blob/main/Resources/code_winner.png);

## Election Audit Summary:
While this script worked well for this election audit, it can also be used for any potential future audits as well.  The variables "file_to_load" and "file_to_save" would need to be be modified to accomodate a new folder structure and file name.  Also, if the format of the csv file did not match the current example, script would need to modified in reference to candidate name and county.