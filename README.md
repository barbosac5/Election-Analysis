# Election-Analysis

## Project and Challenge Overview
  For this analysis Tom (a member of the Colorado Board of Elections) and I retrieved data from an election audit for the United States Congressional precinct in Colorado. The first objective of this Module was:
1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received. 
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

  After retrieving the necessary data, I was then tasked with using a set of Python starter code to find out more information about the congressional election. The requested additional information is as follows:
1. The voter turnout for each county
2. The percentage of votes from each county out of the total count
3. The county with the highest turnout 

## Results
Accodring to the data: 
There were 369,711 total votes cast across the three counties (Arapahoe, Denver, and Jefferson). 
##  The Votes
Out of the 369,711 votes: 
1. Jefferson county had 10.5% of the votes with 38,855 number of votes.
2. Denver county had  82.8% of the votes with 306,055 number of votes.
3. Arapahoe county had 6.7% of the votes with 24,801 number of votes. 
4. The county with the largest amount of votes was the city of Denver with 82.8% of votes with 306,055 number of votes.

In this election, there were three candidates running. These candidates were:
  - Charles Casper Stockham 
  - Diana DeGette
  - Raymon Anthony Doane
The results are as follows:
  - Chalres Casper Stockham received 23% of the votes with 85,213 number of votes.
  - Diana DeGette received 73.8% of the votes with 272,892 number of votes 
  - Raymon Anthony Doane received 3.1% of the votes with 11,606 number of votes
The winner of the election was:
  - Diana DeGette with the winning vote count of 272,892 votes  with a 73.8% of the vote.

![Election_Results](./Election-Analysis/Analysis/election_results.txt)
  

## Challenge Summary 
  Even though this code shows the results the committee was asking for, I do believe it can be improved upon even more. An example of improvement can be in gathering specific data regarding information we did not retrieve, such as finding out how many people voted for a specific candidate per county. This can be done via an if statement where we can state if a candidate got a vote in a specific county, then add 1 to the candidate's name. With this modification, we can see if a candidate had a much larger influence in a particular county. With that extra information, and we can speculate reasons for why a certain candidate did well in a certain county (for example, the certain county can be the candidate's home town).
  With more modifications, we can use Python and more specifically this code, to gather data that can be used in any election from the local level to even a presidential election. One way this can be used in something like the presidential election is to first retrieve a new CSV file that can contain the election data for a presidential election. This can first be done by gathering the top three candidates for the election and findin out the amount of votes cast for each candidate. The new data would have to be in a new CSV file similar to the file we used for this module.  With a new CSV file and new data, we can upload it and change some variables around as well as rename the other variables containing county information to "state" variable such as "state_votes" or "largest_state_turnout". 
  
![Code](./Election-Analysis/Analysis/Python_Code_(1).pdf)
![Code](./Election-Analysis/Analysis/Python_Code_(2).pdf)
![Code](./Election-Analysis/Analysis/Python_Code_(3).pdf)

## Resources 
-Data Source: election_results.csv
-Software: Python 3.7.6, Visual Studio Code, 1.66.2
