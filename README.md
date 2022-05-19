# exam_system
Examination system Project using Python

# TABLE OF CONTENTS
- INTRODUCTION TO PYTHON.
- INTRODUCTION TO THE PROJECT.
- ACKNOWLEDGEMENT.
- SYSTEM REQUIREMENTS.
- BACKEND DETAILS.
- FRONTEND DETAILS.
- MOTIVE.
- SCREEN SHOTS OF EXECUTION.
- BIBLIOGRAPHY.
- LIMITATIONS.
- CERTIFICATE.

# INTRODUCTION TO PYTHON

Python is an interpreted, object-oriented, high-
level programming language with dynamic 
semantics. Its high-level built in data structures, 
combined with dynamic typing and dynamic 
binding, make it very attractive for Rapid 
Application Development, as well as for use as a 
scripting or glue language to connect existing 
components together. Python's simple, easy to 
learn syntax emphasizes readability and 
therefore reduces the cost of program 
maintenance. Python supports modules and 
packages, which encourages program modularity 
and code reuse. The Python interpreter and the 
extensive standard library are available in source 
or binary form without charge for all major 
platforms, and can be freely distributed.

# History of Python:
Python is a widely used general-purpose, high-level 
programming language. It was initially designed by 
Guido van Rossum in 1991 and developed by Python 
Software Foundation. It was mainly developed for 
emphasis on code readability, and its syntax allows 
programmers to express concepts in fewer lines of 
code.

# INTRODUCTION TO THE PROJECT
The Examination Module System software is an 
ERP software used in government and private 
educational institutions in the senior secondary 
level. This software stores details of students
and their marks details in different subjects. We 
can check the report card of the student and 
perform marks analysis by graphical method. 
This software helps us to create profile for 
students, update marks and attendance details
as per the requirement.

# SYSTEM REQUIREMENTS
## HARDWARE REQUIREMENT:
- ➢Printer- to print the required documents of the 
project.
- ➢Compact Drive
- ➢Proccesor: Pentium III and above
- ➢RAM: 256 MB(minimum)
- ➢Hard-Disk : 20 GB(minimum)
## SOFTWARE REQUIREMENT: 
- ➢ Windows 7 or higher
- ➢ My-SQL server 5.5 or higher (as backend) 
- ➢ Python idle 3.6 or higher or spyder (as 
frontend).
- ➢ Microsoft Word 2010 or higher for 
documentation.

# BACKEND DETAILS
## Database Name: EXAM
### Code:

```sql

Create Database Exam;
Use Exam;
Table Name: STUDENT
Attributes:
adm_no int(6) Primary Key
name varchar(40)
class int(2)
section char(1) 

```
### Code:
```sql
CREATE TABLE STUDENT (
 adm_no INT(6) PRIMARY KEY,
 Name VARCHAR(40),
 class int(2),
 section char(1));
 ```
 
### Table Name: RESULT
#### Attributes:
``` sql 
Adm_no int(6) 
exam_name varchar(30)
sub1 int(3)
sub2 int(3)
sub3 int(3)
sub4 int(3)
sub5 int(3)
total int(3)
percentage int(5)
attendance int(5)
grade char(1)
remarks varchar(50) 
```

### Code:
``` sql
CREATE TABLE RESULT (
Adm_no int(6) PRIMARY KEY,
exam_name varchar(30),
sub1 int(3),
sub2 int(3),
sub3 int(3),
sub4 int(3),
sub5 int(3),
total int(3),
percentage int(5),
attendance int(5),
grade char(1),
remarks varchar(50));
```

## MOTIVE
❖ To maintain the student profile, marks and 
attendance details of the students of class-XI 
and XII.

❖ To generate report card displaying the marks 
of a student in different subjects in a particular 
exam and represent the same by graphical 
analysis.

❖ Globalized usage.

## LIMITATIONS
❖ The Project has no provision to update 
marks after the report card is generated.

❖ The project does not incorporate the 
provision of producing the result of the 
entire class for a particular examination.

❖ The project is limited to the examination 
system of class-XI and XII and does not 
provide the yearly summary sheet report 
generation facility.
