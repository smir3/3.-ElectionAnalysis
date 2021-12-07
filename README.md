# ElectionAnalysisAssignment

Overview of Election Audit

Purpose:
Tom is a Colorado Board of Election Employee. His manager, Seth, wants to know if there is a way to automate the election results analysis process using Python. I am tasked with assisting Tom in creating a vote count report to certify this U.S congretional race. This report will be used for congretional or senatorial districts, and local elections. 

Task deliverables:
There are 3 primary voting methods that Tom will take into account; mail-in ballots (hand counted), punch cards (machine counted), and direct recording electronic (computer counted). These will determine the total election results. The task is to use Python to determine the total number of votes cast, the total number of votes for each candidate, the percentage of votes for each candidate, the winner of the election, the voter turnout for each county, the percentage of votes from each county, and the county with the highest turnout.  

Election-Audit Results

- There were 369, 711 votes cast in this congressional election
- County breakdown with respective votes: Jefferson 10.5% (38, 855), Denver 82.8% (306, 055), Arapahoe 6.7% (24,801)
- Denver was the county with the largest turnover
- Candidate votes breakdown: Charles Casper Stockham: 23.0% (85,213), Diana DeGette: 73.8% (272,892), Raymon Anthony Doane: 3.1% (11,606)
- The winning candidate was: Diana DeGette: 73.8% (272,892)

Election-Audit Summary:

Summary: 
This election-audit summary is designed to be used for the election audit by the Colorado Board of Election. With a few minor changes, this script can easily be used for other congretional districts or senatorial districts, and local elections. 

For local elections script:
1) Make sure you are referencing the right row in the excel document for the candidate_name and county_name. Edit line 32 in the code for the candidate_name, and line 34 in the code for the county_name. Please keep in mind that the first row is referred to as row 0.
2) The python documents and text file are contained within a folder titled "analysis", and the excel document is contained within a folder titled "resources". If the Python, text file, or excel document are within different folders, please make sure lines 4 and 6 of the code are updated to reflect this.
3) Since this is a local election; the variable, lists, and dictionary names do not need to be updated (ex. can still refer to counties etc.)

For congretional or senatorial districts:
1) Ensure that steps 1 and 2 from the "local elections script" instructions above are addressed
2) Since congretional and senatorial district elections are on the state level, the variable, lists, and dictionary names should be updated to mention "state" instead of "county"(ex. line 13, 14, 20, 21, 34, 46, 48, 50, 52, 61, 65, 67, 69, 71, 72, 73, 75, 77, 78, 79, 81, 83, 85, 87)

## File Directory
  - The PyPoll_Challenge.py file
  - The analysis folder 
    - election_results.txt 
  - The Resources folder with the 
    - election_results.csv 
