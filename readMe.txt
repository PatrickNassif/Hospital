As we can all agree our health is very important, that is why we are developing an application that we be in favor for the 
hospitals as well as for the patients.
The patients and doctors will be able to login to our application using their phone number or id and a password that will be encrypted than saved to our database. The patients can make an appointment by selecting their medical case then choosing the doctor and finally choosing the time of the free appointment that the previously selected doctor have. The patients can also view their appointment hour if they have one, their doctor , their operation name and the operation hour.
The doctors will be able to view the materials and medicines in the stock, their expiry date, quantity left. Furthermore they can 
see their patients information (name, last name, blood type, appointment hour, operation hour etc..).
The doctor table is formed of the following columns: id , name, family name, profession , hours in hospital, password and the 
hashed password using “sha 256”.
The patient table is formed of the following columns: id , name, family name, blood type, appointment hour, operation hour, 
operation name , the room they will be staying in after the operation phone nb, their doctor name, password and the hashed password 
using “sha 256”.
The stock table is formed of the following columns: product name, expiry date and quantity left.
The weeklyFreeCalendar table is formed of the following columns: the doctors names and the hours per day that the doctors are free.
This app is written using java where the user can create an account , login with a verification on the id/phone nb and password. 
Specified information and actions can be done based on the status of the user(doctor or patient). Queries are written to get the 
necessary information from the database and display them in the gui that we created. Many classes are created based on OO concept 
using inheritance , overridden methods…