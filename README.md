# Election-Audits with Python
## Overview of Election Audit
Seth and Tom requested our assitance to put together election-audit results from a Colorado Board of Elections to share with the election commission. While they were thankful for help, the election committee asked for additional data to be added to aid in completing the audit. 

We were given a `.csv`file with the raw election data. Utilizing Python, the objective is to retrieve certain information including the total number of votes cast, the complete list of candidates with respective vote quantities, the percentage of votes each candidate won, and the winner of the elections based on popular vote.

## Election-Audit Results
### Here is an image of the summarized election results:
![Capture1](https://user-images.githubusercontent.com/92230478/140006671-b40be62f-a547-4fdf-945c-f5d92b64f37d.PNG)

### Election Outcomes
* There were a total of **369,711** casted in this congressional election
* County Votes
  * **Jefferson County** had **10.5%** of votes with **38,855** total votes
  * **Denver County** had **82.8%** of votes with **306,055** total votes
  * **Arapahoe County** had **6.7%** of votes with **24,801** total votes
* **Denver County** had the largest number of votes at **306,055**.
* Candidate Votes
  * **Charles Casper Stockham** had **23.0%** of votes with **85,213** total votes.
  * **Diana DeGette** had **73.8%** of votes with **272,892** total votes.
  * **Raymon Anthony Doan** had **3.1%** of votes with **11,606** total votes.
* **Diana DeGette** has won the election with **73.8%** of votes at **272,892** total votes.

## Election-Audit Summary
This script can be modified and used for any election to find the number of votes with different filters (other than candidates and counties). All we would need is a `.csv` file containing the information desired to compile. The data could include other characteristics including geography and demographics for which the script could be modified to account for these, making our analysis deeper. 

We can look into which cities hold the most power in determining the winner of the election. This is critical for the candidates as they will understand where they need to focus their campaigning efforts to win these significant votes.

In addition, seeing the gender, age groups, income bracket, and ethnicities of the voters would also be valuable information to the candidates. This will help them know which adgenda they need to appeal to in order to sway more voters in their favor.

As long as we have all the neccessary information, we can modify the script to compile and calculate the characteristics of any election. 
