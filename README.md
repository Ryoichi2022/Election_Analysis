Challenge 3
# Election_Analysis

## 1. Overview of Election Audit
The Colorado Board of Elections would like an automated election audit process for the U.S. Congressional Precinct in Colorado. The automated process, which is based on Python, will summarize the election results such as the total number of votes cast and the percentage of votes for candidates in order to generate a vote count report to certify the U.S. congressional race. It is also expected to be used in other congressional districts, senatorial districts, local elections. 

Votes were cast through mail-in ballot, punch cards, or direct recording electronic (DRE) counting machine and gathered in a csv format as final election results.

## 2. Election Audit Results
369,711 votes were cast in total in the election, consisting of the following number of votes and the percentage of total votes in each county:
Jefferson County: 38,855 / 10.5%
Denver County: 306,055 / 82.8%
Arapahoe County: 24,801 / 6.7%
The largest number of votes were cast in Denver County.
Each candidates received the number of votes and the percentage of the total votes as follows:
Charles Casper Stockham: 85,213 / 23.0%
Diana DeGette: 272,892 / 73.8%
Raymon Anthony Doane: 11,606 / 3.1%
As a result, Diana DeGette won the election with 272,892, or 73.8% of votes. The election results printed to the terminal is shown as Figure 1.

## 3. Election Audit Summary
### Application to Other Elections
In the process, the vote data is expected to be in csv format and include ballot ID, county, and candidate for each vote. As long as the csv contains these items, the automated process will work for other elections to generate the result report.

### Potential Modification
One potential modification could be made to summarize the result for each county to identify the candidate that has won the election in the county. This modification will be able to present results of the same type of election in multiple counties altogether.
Once the modification is implemented, the process would be used for different elections in each county by replacing the county with election type such as sheriff, mayor, and school board. Then, the result of multiple elections will be available at once after the election results csv data is ready for the automated process.

(Figure 1)
Election results printed to terminal
![]()
