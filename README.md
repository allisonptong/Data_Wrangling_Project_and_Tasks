# Data_Wrangling_Project_and_Tasks

## Overview

The purpose of this repository is to collect all of my code from the course QBS 181 Data Wrangling. I have been given permission from my instructor to make this work public. 

## Description of subdirectories

There are five subdirectories - 3 projects that I completed throughout the term as well as my code from the midterm and final assignemnts. 

### The first project asked us to:

1.	 Rename all the columns for eg.,

a)	TriAge to Age

b)	GenderCode to Gender

c)	ContactID to ID

d)	Address1Stateorprovince to State

e)	TriImagineCareenrollmentemailsentdate to EmailSentdate

f)	Trienrollmentcompletedate to Completedate

g)	Calculate the time (in days) to complete enrollment and create a new column to have this data


2.	Create a new column “Enrollment Status”

a)	Insert Status=Complete :code is 167410011

b)	Insert Status=Email sent :code is 167410001

c)	Insert Status=Non responder: Code is 167410004

d)	Insert Status=Facilitated Enrollment: Code  is 167410005

e)	Insert Status= Incomplete Enrollments: Code  is 167410002

f)	Insert Status= Opted Out: Code  is 167410003

g)	Insert Status= Unprocessed: Code  is 167410000

h)	Insert Status= Second email sent : Code  is 167410006


3.	Create a new Column “Gender”

a)	Insert Gender=female if code=2

b)	Insert Gender=male if code=1

c)	Insert Gender=other if code =167410000

d)	Insert Gender=Unknown if code =’NULL’


4.	Create a new column “Age group” and create age groups with an interval of 25 yrs. for example 0-25 years as ‘0-25’, 26-50 as “26-50” and so on...


### Project 2 asked us to:

1.	Create a new column “Enrollment group” in the table Phonecall

a)	Insert EnrollmentGroup=Clinical Alert :code is 125060000

b)	Insert EnrollmentGroup =Health Coaching :code is 125060001

c)	Insert EnrollmentGroup =Technixal Question: Code is 125060002

d)	Insert EnrollmentGroup =Administrative: Code  is 125060003

e)	Insert EnrollmentGroup =Other: Code  is 125060004

f)	Insert EnrollmentGroup =Lack of engagement : Code  is 125060005


2.	Obtain the # of records for each enrollment group


3.	Merge the Phone call encounter table with Call duration table.


4.	Find out the # of records for different call outcomes and call type. Use 1-Inbound and 2-Outbound, for call types; use 1-No response,2-Left voice mail and 3 successful. Please also find the call duration for each of the enrollment groups 


5.	Merge the tables Demographics, Conditions and TextMessages. Find the # of texts/per week, by the type of sender. 


6.	Obtain the count of texts based on the chronic condition over a period of time (say per week). 


### The third project was to:

1.	Compute the rate for table2, and table4a+table4b and perform the four operation

a.	Extract the number of TB cases per country per year

b.	Extract the matching population per country per year

c.	Divide cases by population, and multiply by 10,000

d.	Store back in appropriate place.


2.	Why does this code fail?
table4a%>%gather(1999,2000,key="year",value="cases")


3.	Use the flights dataset in the nycflights13 library and answer the following

a.	How does the distribution of flights times within a day change over the course of the year

b.	Compare dep_time,sched_dep_time, and dep_delay. Are they consistent. Explain your findings

c.	Confirm my hypothesis that the early departures of flights in minutes 20-30 and 50-60 are caused by scheduled flights that leave early. Hint:create a binary variable that tells whether or not a flight was delayed.


4.	Use similar methods as accessing Twitter from an API, search the keyword “black Friday deals” on Facebook.
    Hint: use this package from R to access Facebook https://cran.r-project.org/web/packages/Rfacebook/Rfacebook.pdf

### The midterm assingment:

Visit the website https://wwwn.cdc.gov/Nchs/Nhanes/2015-2016/DIQ_I.htm#Data_Processing_and_Editing

1.	The DIQ_I.xpt(will be uploaded on canvas) file has some problems with its data (e.g., missing values, numeric columns stored as chars, etc.) and need to be cleaned before further use. 

a)	List the data-related issues you see in this data set

b)	How will you address each data-related issue?

c)	Give justification for why you chose a particular way to address each issue. For example, if you decide to address missing values by removing rows or filling empty data cells, justify your decision or if you want to create a PHI field like year of Birth


2.	Clean the data by addressing each point listed in 1.
      
Verify that whether the counts of each code or value for various variables are correct as mentioned in the website


### Final Assignment:

1)	Consider the following blood pressure dataset (IC_BP_v2.csv). Perform the following operations

a.	Convert BP alerts to BP status
b.	Define Hypo-1 & Normal as Controlled blood pressure; Hypo-2, HTN1, HTN2 & HTN3 as Uncontrolled blood pressure: Controlled & Uncontrolled blood pressure as 1 or 0 (Dichotomous Outcomes) 

c.	Merge this table with demographics (SQL table) to obtain their enrollment dates

d.	Create a 12-week interval of averaged scores of each customer 

e.	Compare the scores from baseline (first week) to follow-up scores (12 weeks)

f.	How many customers were brought from uncontrolled regime to controlled regime after 12 weeks of intervention?


2)	Merge the tables Demographics, Conditions and TextMessages. 
Obtain the final dataset such that we have 1 Row per ID by choosing on the latest date when the text was sent (if sent on multiple days)

3)	Repeat Question 2 in R. 
Hint: You might want to use tidyr/dplyr packages

4)	Set up a public GitHub repository to share your code. If you didn’t attend the Research Computing’s Git/BASH workshop, or no longer familiar with it, please use online resources (e.g. YouTube tutorials) to re-familiarize yourself with Git/GitHub.


