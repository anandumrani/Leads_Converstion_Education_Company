# Leads_Converstion_Education_Company
Build a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads.

## Background of X Education Company
- An education company named X Education sells online courses to industry professionals. 

## Problem Statement
- X Education gets a lot of leads, its lead conversion rate is very poor at around 30%
- X Education wants to make lead conversion process more efficient by identifying the most potential leads, also known as Hot Leads
- Their sales team want to know these potential set of leads, which they will be focusing more on communicating rather than making calls to everyone.

## Objective of the Study:
- To help  X Education select the most promising leads, i.e., the leads that are most likely to convert into paying customers. 
- The company requires us to build a model wherein we need to assign a lead score to each of the leads such that the customers with a higher lead score have a higher conversion chance and the customers with a lower lead score have a lower conversion chance. 
- The CEO has given a ballpark of the target lead conversion rate to be around 80%.

## Approach
![Approach](https://github.com/anandumrani/Leads_Converstion_Education_Company/assets/105964876/a583d795-8d5c-4202-b787-f60e8f67bfec)

## Recommendation based on Final Model
- As per the regression model the most significant factors that impact lead conversion are:
	- Lead Source_Welingak Website
	- Lead Source_Reference
	- Current_occupation_Working Professional
	- Last Activity_SMS Sent
	- Last Activity_Others
	- Total Time Spent on Website
	- Last Activity_Email Opened
	- Lead Source_Olark Chat
- These features should be given priority in marketing and sales efforts to increase lead conversion.
- The features with negative coefficients that may indicate potential areas for improvement. These include:
	- Specialization in Hospitality Management
	- Specialization in Others
	- Lead Origin of Landing Page Submission
