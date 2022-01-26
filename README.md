# Election_Analysis

## Project Overview
In this project, we are assisting a Colorado Board of Elections employee (Tom) in the election audit of the tabulated results for the US congressional precinct in Colorado. We are tasked with reporting: 
1. The total number of votes cast 
2. Total number of votes for each candiddate 
3. Percentage of votes for each candidate
4. The winner of the election based on the popular vote.

Using Python we generate a vote count report to certify this US Congressional race.

## Resources
Data Source: election_results.csv

Software: Python 3.7.6, Visual Studio Code 1.6.3

## Election Audit Results

The Total Votes count of 369,711 in this congressional election is split between three counties; Jefferson, Denver, and Arapahoe.

<img width="425" alt="Screen Shot 2022-01-15 at 1 53 30 PM" src="https://user-images.githubusercontent.com/95504135/149634875-e87ba367-db33-4b08-a61e-72d6c68a50de.png">

* Arapahoe had a total of 24,801 votes - accounting for 6.7% of the total votes cast.
  
* Jefferson had a total of 38,855 votes - accounting for 10.5% of the total votes cast.
  
* Denver had a total of 306,055 votes - accounting for 82.8% of the total votes cast.
 
***Denver had the largest number of votes cast (306,055 votes)***
  
There were three candidates in this congressional race; Charles Casper Stockham, Diana DeGette, and Raymon Anthony Doane.

<img width="543" alt="Screen Shot 2022-01-15 at 1 54 14 PM" src="https://user-images.githubusercontent.com/95504135/149634911-bd30c3cd-479a-46cf-ab65-03b643604401.png">


* Raymon Anthony Doane received 11,606 votes accounting for 3.1% of the total votes.

* Charles Casper Stockham received 85,213 votes accounting for 23% of the total votes.

* Diana DeGette received received 272,892 votes accounting for 73.8% of the total votes.


***Diana DeGette recieved the majority of votes finalizing her vicotry in this congressional race of Colorado.***
<img width="298" alt="Election_Results" src="https://user-images.githubusercontent.com/95504135/149633395-a449ca45-8408-4ac1-8099-151949b35608.png">
  
## Election Audit Summary
Though the use of the vote count reporting that was created in Python, we successfully audited the results of this election. 
Admittedly, this election was relatively small compared to states and counties with larger populations and limited to three counties, but throught he process of reafactoring/modification, this code could be potentially used for larger-scale voting audits. 

The original code only output the districts, candidates, and their total votes and total percentages - this data is limited, but to gain further insight on an election, we could add party affiliation of each candidate. Through the addition of code which would mark each candidate with their affiliation as Republican, Democrat, or Independent. With this additional data, we can further analyze the correlation between counties and party affiliation. Though, it needn't be limited to just counties. Another example in which we could refactor the code is to modify it to house and display data for elections at a national level. Through the analysis of elections at a local level and the expansion of our code to a national level along with the use of our previously mentioned party affiliation code - we can gain further pertinent data on the political spectrum of various degrees.
