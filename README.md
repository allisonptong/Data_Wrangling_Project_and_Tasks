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


