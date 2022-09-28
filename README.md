# Investigating a dataset: No show appointments
## by Folami J. Balogun  

## Dataset
This [dataset](https://www.kaggle.com/datasets/joniarroba/noshowappointments) contains information from over 100,000 medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A description of each column in the dataset is detailed below;

01 - PatientId: Identification of a patient  
02 - AppointmentID: Identification of each appointment
03 - Gender: Male or Female  
04 - Sheduled Day: The day the patient set up the appointment  
05 - Appointement Day: The day of the appointment, when the patient is to see the doctor  
06 - Age: How old is the patient  
07 - Neighbourhood: Where the appointment takes place  
08 - Scholarship: indicates whether or not the patient   is enrolled in Brasilian welfare program Bolsa Família  
09 - Hipertension: indicates whether patient has hypertension or not  
10 - Diabetes: indicates whether patient has diabetes or not  
11 - Alcoholism: indicates whether patient is an alcoholic or not  
12 - Handcap: indicates whether patient is handicapped or not  
13 - SMS_received: 1 or more messages sent to the patient  
14 - No-show: indicates if patient was absent for their appointment  

## Summary of findings
In the first question where I explored how age affects showing up for appointments, the analysis showed that though the senior adults have the smallest appointment bookings amongst the four age groups, they are more likely to show up for their appointment when compared to the other age groups while the young adults, though with the most appointment bookings of the four age groups are the least likely to show up for an appointment.

I then checked the influence of when the appointment booking is made had on showing up for the appointment. This showed that while most people are likely to book for their appointment after the appointment day, people like this are the most likely to show-up. The proportion of people that show up for their appointment also decreases as the scheduled day gets farther from the appointment day.

Lastly, I checked the effect being hypertensive or not has on showing up for an appointment in the senior adult population and I saw that there is no significant difference in whether a senior_adult will show up for their appointment based on their hypertensive status, as about an equal proportion of both groups go for their appointment.
