# Election Results Analysis

## Overview of Election Audit 

The purpose of the audit analysis is to certify the election results for a seat in the U.S. Congress. Using Python, I automated the generation of a report summarizing the results of the election. 

## Election Audit Results

### Total Votes 

* 369,711 votes were cast in this congressional election. 

### Votes by County 

* Jefferson: 10.5% (38,855)
* Denver: 82.8% (306,055)
* Arapahoe: 6.7% (24,801)

* Denver had the largest number of votes.

### Votes by Candidate 

* Charles Casper Stockham: 23.0% (85,213)
* Diana DeGette: 73.8% (272,892)
* Raymon Anthony Doane: 3.1% (11,606)

### Winner of the Election 

* Diana DeGette received the most votes (272,892) and won the election. She received a majority of the votes (73.8%). 

## Election Audit Summary 

This script makes certifying the results of the election significantly faster; so long as there are no errors in the script, the results will always be accurate and free of human error. The election commission can adapt and use this script for other types of elections e.g. senators and other levels of government e.g. municipal level. 



In this module, you'll be assisting a Colorado board of elections employee, Tom, in an election audit of the tabulated results for a U.S. congressional precinct in Colorado. You are tasked with reporting the total number of votes cast, the total number of votes for each candidate, the percentage of votes for each candidate, and the winner of the election based on the popular vote.

This task is usually done in Excel, but Tom's manager wants to know if there's a way to automate the process using Python. If this audit is done successfully with Python, the code you and Tom write will be used to audit not only other congressional districts, but also senatorial districts and local elections.

There are three primary voting methods that you and Tom will take into account, mail-in ballots, punch cards, and direct recording electronic, or DRE, counting machines. Mail-in ballots are typically hand counted at the central office. Punch cards are collected and then fed into a machine that tabulates vote totals and sends the results to the central office. Finally, memory cards from DRE counting machines are sent to the central office and read by a computer.

Altogether, the votes cast by these three methods will determine the final election results. After the votes are counted, your job is to generate a vote count report to certify this U.S. congressional race. Let's get started.