# Lab-1_202001098







                             

Software Engineering: IT 314

Parth Agarwal
202001098


Date: January 25th  2023

Lab-Group:2
Lab Assignment: 1



Identifying Functional and Non-Functional Requirements

Library Information System (LIS)-

I)Functional requirements:-

Sign Up: 
a) Users- Since the books will only be available or issued to those who are registered on the site therefore we will have a sign up feature where the new users can come and enter their details for the future login purpose.
b) Staff/Librarian- They will be logging in with a different set of credentials as they will be having access to all the information related to the system.

Login: 
a)Users- This is the option which enables the already existing  users to come and verify their username and password for the purpose of availing the features of the library. 
b) Staff/Librarian- They will be able to access the records through a different login page and this will allot them the administrative privileges and complete control over the system. This will give them access to details of all the registered users and all the other information regarding the library.

Searching: This feature will be a parameter match based tool which will facilitate the user to find the book which they are looking for in the system. A user can search for the book based on the various parameters like the -
Name of the book
Publication House
Author’s Name
Category/Genre Wise
Books with similar content

However this feature can be used by anyone regardless of the fact that he is logged into the system or not. As this gives the user to just search for the book they are looking for.

Issuing the Book: As the users will want to remotely issue the book so this feature will come in handy as users can remotely login and then use this to issue the book which they want. The feature will have following sub features associated with it:

Max Count at a time : This will restrict the user from issuing more than specified count of at a time, so as to manage the resource load.
Wait and Book: If the book is already issued than the user can use this feature of wait and book which allots him the book as and when the book is available.
Re-issue: If there is no pre booking of the book than the user can extend the deadline for the return for the book.

Updating the Records: The staff members and librarian will be able to update the records of the book and the users details, so as to monitor and regulate the issuing process. There will be following options in update:
Delete: This will allow the administrator to delete a book which is no longer available
Update: This allows the administrator to update the details regarding the existing records of any book or magazines.
Add: This option can be used to add a new record into the database.



II) Non -Functional Requirements:-

Scalability: The system should be able to handle a 10x the size of the total students and faculty of the institute as the institution may expand in the future and so the system should be able to add all the users.
Reliability: This is one of the most important features as the system should be reliable and consistent at all times. For the system to be online 24/7 it can be hosted on two servers, incase of failure in either of them. 
Regulatory: This ensures the system follows all the guidelines and regulations which are mandated by the institution.
Maintainability and Serviceability : Web App should be easy to fix and update in case any bus occurs.
Security: This is the most important aspect of any application as it prevents and unauthorized or malicious user to tamper with the records or misuse the information.
Usability: The interface should be user friendly and should have the options will designed and easy to identify so as people from any age-group or background should be able to use it.


Design Constraints and Interoperability:The  application  has  to  be  developed  as  a  web  application,  which  should  work  with Firefox 5, Internet Explorer 8, Google Chrome 12, Opera 10. The system should be developed using HTML 5.














Hearing Aid Assistant:
I)Scope:  This application can be used by all the people facing any level of hearing loss. This is a cross platform application  which can be used on any operating system, provided the system meets a minimum set of requirements. But the system is primarily optimized to work best on android devices. It can be used for a variety of daily tasks like walking on roads, inside a building, while communicating with others, etc.

II)Functional requirements:

Vibrate to Alert: On encountering any important event like car horns, baby crying it should instantly alert the user regarding occurrence of above mentioned.

Fall Detection: The system should be able to sense it as the device falls off, suggesting any mishap so as to alert the user.

Data processing: The app should be able to differentiate between different	sounds so as to create the appropriate response to the sound. The app uses an artificial intelligence to perform the required tasks.

Logging Key events: The app should be able to resord all the key events occurring during the day.

Speech to Text: This is one of the most important feature of the system as it can helps in communicating with any other person.


III)Non-Functional requirements:

Low latency: it is very important feature as the app should be able to sense the critical events.
It should be able to provide real time alerts to key sound events.
The app is designed primarily for the android smartphones but it may be used to any other platform as well.
The app is designed to be used by people with disabling hearing loss.





