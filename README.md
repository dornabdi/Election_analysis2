# Election_analysis

## Overview of Election Audit
A member of the Colorado Board of Elections gave me a series of tasks to complete an audit of the most recent congressional election to ensure election integrity. The tasks are as follows <br/>
1. Total number of votes cast <br/>
2. A complete list of candidates who received votes <br/>
3. Total number of votes and percentage each candidate won <br/>
4. Total number of votes and percentage each county won <br/>
5. The winner of the election based on popular vote <br/>
6. The county with the highest voter turnout <br/>

## Election Audit Results: 
- There were 369, 711 total votes cast in the election.
- Jefferson County had 10.5% of the votes with 38,855 votes cast. Denver County had 82.8% of the votes with 306,055 votes cast. Arapahoe County had 6.7% of the votes with 24,801 votes cast. 
- Denver county had the largest number of votes.
- Stockham received 23% of the vote and 85,213 votes. Degette Received 73.8% of the vote and 272,892 votes. Doane received 3.1% of the vote and 11,606 votes
- The winner of the election was Diana DeGette who received 73.8% of the total vote and 272,892 votes out of 369, 711 total votes. 


## Resources Used
- Software: Python 3.9.0, Visual Studio Code 1.52.1
- Data Source: election_results.csv from supervisor.

## Audit Summary
The script I wrote for this election audit can be easily edited and used for any other election. I propose that you save and modify this script for future elections to avoid errors and increase audit efficiency. 

<br/> This script pulls data from the election_data.csv file that was provided to me to perform this analysis. I imported the os and csv modules to locate and read the files I needed. The process I used to extract this data can be used for any other csv file. Be sure to adjust the filename accordingly. Otherwise, you can easily set your file_to_load and file_to_save variables to the relative path that is set on your computer!
<br/> ![election](election.png)

You can reuse and modify a lot of the beginning script pictured below. For example, you can view your csv file and adjust the row function to match your dataset. You can keep the same for-loop scripting for reading the data and modify the last two lines of code for more relevant parameters for each row/column. See image of script below:
<br/> ![election1](election1.png)

Additionally, looking further into the code. It is evident how the script structure can be modified for your needs. Firstly, the step by step directions in the script comments can make it very easy to adjust code. Secondly, the variables scripted can be adjusted to meet your project's needs. This is true whether you need to add variables or more conditions to your statements. See image of the script below:
<br/> ![election2](election2.png)







