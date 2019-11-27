# InnovaccerProject
This is an application which can capture the Name, email address, phone no. of the visitor and same information for the host on the front end.
At the backend once the user enter the information in the form and enters the checkin time, all the information is stored on the firebase database with time stamp of the entry.
It triggers an email and a sms to the host when the vistor submits the form, host gets all the details such as
Visitor Name, email, phone no., checkin time.
When the visitor checksout an email and sms are sent to the visitor stating all the details:
Visitor Name, phone no.,checkin time, checkout time, Host name.
Email is sent programmatically through the application itself using JavaMail API and JSSEProvider class functionality.
SMS is sent programmatically through the application itself.
All the data is updated on the database itself.
GMail Account used for managing the database and sending emails:
username: internprojectinnovaccer@gmail.com
password: internadmin
PROJECT MADE BY SHASHANK MAHAJAN (Email: shashankmahajan99@gmail.com)
