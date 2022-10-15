# No-show Data Exploration

## Dataset

The No-show appointment dataset which is original sourced on Kaggle contains information 
from over 100,000 medical appointments in Brazil and is focused on the question of whether
or not patients show up for their appointment. The dataset consists of 110527 rows and 14 
columns which include PatientId, Gender, Age, Neighbourhood, Scholarship, Diabetes, Alcoholism,
SMS_received, and No-show.

## Summary of Findings

In the exploration, I found that diseases and Age influenced patients availability while 
Scholarship, SMS_received, and Gender did not. 
I derived a new column "Age_group" from age to analyze the effect of age on patients 
availabilty for appointment and it showed that age influences the availability of patients 
for appointments as 'Senior adults'(60 years and above) patients showed the highest availability
for appointments while teenagers (13 - 19 years) had the least. Diseases influences patients 
availability for appointment as patients who had either hypertension or diabetes showed up more
than those without any disease. 

Gender showed that is not a good feature to determine availability for appointment as the 
difference in gender with respect to No-show is extremely small while Scholarships and SMS_received 
did not influence the patients availability for appointment as patients who did not receive messages 
nor scholarship showed up more than those who recieved.