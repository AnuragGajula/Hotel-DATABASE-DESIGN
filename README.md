# Hotel-DATABASE-DESIGN
Welcome to the Hotel Database System — a professionally designed, fully normalized relational database for managing hotel staffing operations.


>> MiHotel Database System
Welcome to the MiHotel Database System!
This project is a fully normalized, relational SQL database designed for managing hotel employee recruitment, applications, offers, and applicant details.

>> Project Description
The MiHotel database is built to efficiently store and manage:

Hotel Locations

Employee Information (HR, Managers)

Job Postings

Applicant Profiles

Applications and Offers

Education, Employment History, References

Military Service Records

Conviction Records

All tables are normalized up to 3rd Normal Form (3NF) to ensure data integrity, eliminate redundancy, and enhance query performance.

>> Entity-Relationship Diagram (ERD)
A professional ERD is created showing all entities, relationships, and keys.

Key Highlights:

One-to-Many relationships between Hotels and Employees

One-to-Many between HR and Job Postings

Many-to-One between Applicants and Applications

Applications linked with Offers


>>Database Tables

Table Name	Description
MiHotel	Stores Hotel information
Employee	Stores Manager and HR employee details
Job_Posting	Stores job posting information
Applicant	Stores applicant's personal information
Application	Links applicants to job postings
Offer	Stores job offers for applicants
Education	Applicant's educational background
Employment_History	Previous employment records
Professional_Reference	Professional references details
Military_Service	Applicant's military service records
Conviction	Criminal history information

>> Normalization Summary
1NF: Atomic data and unique records

2NF: No partial dependencies

3NF: No transitive dependencies

BCNF (optional): Further normalized structures like applicant languages

>> ER Diagram
![image](https://github.com/user-attachments/assets/80d8d4bd-1724-44ca-be16-06ab70585bb0)

