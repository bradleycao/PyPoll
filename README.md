# Election Analysis

## Project Overview

In this project, I helped the two clients Seth and Tom, go audit the election results. The key aspects that we looked into are:

- Total number of votes cast
- The voter turnout for each county
- The percentage of votes from each county out of the total count
- The county with the highest turnout
- A complete list of candidates who received votes
- Total number of votes each candidate received
- Percentage of votes each candidate won
- The winner of the election based on popular vote
The results were then printed in TXT file named election_analysis.txt. 


## Resources

Data Source: election_results.csv

## Election Audit Results

The analysis of the election show that:
- There were **369,711** votes cast in the election.
- The counties, along with their results, were:
    - Jefferson received **10.5%** of the vote and **38,855** number of votes.
    - Denver received **82.8%** of the vote and **306,055** number of votes.
    - Arapahoe received **6.7%** of the vote and **24,801** number of votes.
- The candidates, along with their results, were:
    - Charles Casper Stockham received **23.0%** of the vote and **85,213** number of votes.
    - Diana DeGette received **73.8%** of the vote and **272,892** number of votes.
    - Raymon Anthony Doane received **3.1%** of the vote and **11,606** number of votes.
- The Largest County Turnout was **Denver**.
- The winner of the election was:
    - **Diana DeGette** received **73.8%** of the votes and **272,892** numbers of votes.

## Election Audit Summary

For future elections, there are two things that I suggest we can modify this script:

- If you have a different file name,with similar column names inside, you can change the file name in the **file_to_load** variable:
    ```
    file_to_load = os.path.join("Resources", "new_file_to_load.csv")
    ```
- If you want to have a different file name when you export the file, you can change the name in the **file_to_save** variable:
    ```
    file_to_save = os.path.join("analysis", "new_file_to_save.txt")
    ```



