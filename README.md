java c158337, S2, 2024 Page 1 of 9 Project Instructions IN 
CONFIDENCE 
158.337 Group Project Instructions: Part A 
(Course mark - 17.5%) 
 
You will work in groups of 3-4 members for this assignment. Register yourself on the 
Group registration link (under the Assignment section on the Stream site). Use the 
following set of steps to guide you in completing the assignment project. You should 
turn the work in for grading by the due date (Tuesday, 27th Aug 4.00 pm). Lateness: 
There is a 10% penalty / per day, and no submission is permitted after 3 days. 
 
Note: Make sure you have altered the password of your allocated group Oracle a/c 
from the given default (GROUP01, GROUP02,…case sensitive). You do not want 
other people accessing your account. Remember it is your responsibility to protect 
your work. For the assignment, it is the joint responsibility of all the group members. 
 
 Logical and Physical Database Design 
 
Read Te Ohanga Village - Massey University Student Accommodation Office 
Case Study given in the Appendix A. 
 
For Part A, complete the three steps (Step 1 – Step 3). 
 
Part A: Step 1 (30 marks) 
 
Create a logical (relational) data model (e.g., Database or ER diagram). Use J 
Developer or Visio* to create this diagram. Use one of these two tools only. 
 
Note*: Do not extract your diagram from SQL Developer after creating tables or 
DataModeler (notation is different and some required modelling information to fully 
assess will be missing so cannot be graded fairly). Use of other tools (e.g. Generative 
AI tools), extractions from tools such as SQL Developer will all lead to a straight 
Zero. 
 
Use appropriate naming conventions while naming tables, attributes, relationships, etc. 
in your diagram. Also, use appropriate attribute datatypes, data sizes, etc. in the 
diagram and ensure to flag PKs, FKs, etc. 
 
State the business rules very clearly (no ambiguity), consistently under a separate 
section (in your report). There should be two business rules for each relationship 
shown on your diagram (For example, if there are 10 relationships then there should 
be 10 pairs of rule statements). Similarly, state your reasonable assumptions (this 
helps us to evaluate your design better) under a separate section. The work presented 
in these two sections should be consistent with your ER diagram. 
 
Examine each table’s (entity's) attributes for dependencies and apply the rules of 
normalisation discussed in Chapter 6 of the textbook. You are required to show the 
detailed normalisation process {e.g., how you move from lower normal form (e.g., 
1NF) to the next (e.g., 2NF)} in the submitted work. Use dependency diagrams for 
depicting all the relationships among a table’s attributes. Normalise tables up to the 158337, S2, 2024 Page 2 of 9 Project Instructions IN 
CONFIDENCE 
highest NF (up to 4th
 NF should be fine). State the normal form for each of the tables 
at every step in the process. 
 
Part A: Step 2 (20 marks) 
 
Generate the physical model based on the logical model created in the Step 1. To 
create the required set of tables, relationships, constraints, etc. write SQL scripts using 
a text editor (e.g., Notepad++). Use SQL Developer for initial checking / debugging 
and running of the code. Keep improving your code until you are satisfied with the 
design. Please ensure that it is consistent with your ERD (you may have to revise your 
ERD if you come up with better design during this stage). 
 
Check the DDL code in your script file and make sure that all the attribute definitions 
(e.g., names, data types, data sizes, whether required, domain values including 
defaults, etc.), table constraints (e.g., entity integrity, referential integrity, etc.), etc. 
are specified adequately and correctly. 
 
Validate your work by ensuring that query transactions {(a) - (v) listed towards the 
end of the case study} are supported by your design. Make sure that the physical 
design is robust i.e., meets the requirements of a good design. Remember 
normalisation alone does not produce a good design. In the end, ensure that both 
logical and physical designs are consistent with each other. 
 
Run your final scripts to generate the database (i.e., physical model). Use your Group 
Oracle a/c to implement the final DDL code. 
 
Part A: Step 3 (10 marks) 
 
Finally, create appropriate test data to populate the tables you created in Step2. Use 
SQL Developer to run a script file that contains SQL INSERT statements. 
 
There should be sufficient rows of the test data across all the tables. No table should 
contain less than five rows. Make sure your test data appropriately and sufficiently 
reflects your design (this would usually mean adding more than 5 rows in some 
tables) and does not violate any of the constraints declared while creating the 
database design in Step1 and Step2 (i.e., create table scripts and the ERD). Set up all 
the tables and their constraints in the correct order before you load any data into 
the database. In summary, the grader should be able to verify your design 
convincingly, comprehensively and with ease. 
 
Notes: 
Apply good naming conventions, which are also self-explanatory (e.g., name create 
table script file as createTables.sql, name your tables, attributes appropriately, etc.). 
Additionally, annotate your code (both DDL and DML) with appropriate and enough 
comments to enhance understandability. Consistency between work done in all the 
steps is very important otherwise you will unnecessarily risk losing a good number of 
marks for this reason. 
Check your project work and make sure that all the scripts run without any errors. 
Also, ensure that appropriate names have been given to all files. 158337, S2, 2024 Page 3 of 9 Project Instructions IN 
CONFIDENCE 
This assignment is also testing only your basic SQL knowledge, so write code for all 
the DDL and DML statements. Do not give us automated statements that are derived 
from Oracle tools (i.e., SQL Developer or JDeveloper). No marks will be allocated 
for DDL/DML scripts generated by Oracle tools. The code should NOT be tied to the 
schema, and we should be able to run the code from any Oracle account. 
 
Assignment Submission 
 
Organise your project report (printer-friendly, in case we need to print – grader’s 
preference) to include all the assignment requirements. Make sure the report contents 
are also in the same order as the laid requirements. 
 
There are three parts to this assignment submission: 
• a project report (word/pdf – soft copy), 
• scripts (2 code files – sets of create and insert statements), 
• database (tables, etc under your Group account). 
 
Note: 
Enter your names, student ids on the project marking sheet (Appendix B). 
Remember to provide the (Group) Oracle username in your report. The 
Password not needed. 
Checklist for project report (word/pdf) contents 
 
 1. A logical relational model (database or ER diagram) that is laid out clearly 
and legibly for grading. The text font size should not be very small (otherwise 
risk getting a straight zero)*. The diagram should show all the entities, 
attributes (with appropriate data types, sizes, etc.), primary keys, foreign keys, 
and relationship details (appropriate association names, cardinality, strength 
(identifying or non-identifying), participation (mandatory or optional)), etc. 
Make sure you have applied and shown the normalisation process to arrive at 
the final model. Pay special attention to the readability of the ER diagram so 
that one could print and assess with ease (as this is the core of all the work). 
 
2. A discussion of the reasonable assumptions you make about the ambiguous 
aspects and / or reasonable extensions to the given case study. We anticipate 
that each group's design will differ** from those of other groups based on 
the underlying assumptions. 
 
3. A list of business rules for each relationship on your diagram (clearly state 
two unambiguous rules for each relationship as these are bi-directional). 
 
4. DDL and DML code that is taken from the command files used for creating 
(create statements) and populating (Insert statements) your Oracle tables. 
 
This should NOT be auto generated code and/or linked to your schema 
account. Remember to include declarative constraints, etc in Create table code. 
Do not provide Alter statement code separate to the Create statements i.e. 158337, S2, 2024 Page 4 of 9 Project Instructions IN 
CONFIDENCE 
place all the constraints next to the attributes where possible. Basically, use 
only one single statement to create a table. 
 
5. Test Data (well formatted, readable dump of contents for all the tables) that 
can be referred to with ease. This helps in evaluating the design. 
 
Checklist for submission under your Group Oracle a/c 
 
All the tables with test data must be available via your Group Oracle a/c. 
Checklist for submission on Stream 
Compressed Folder – containing Report (a word/pdf file) and coding files (2 .sql 
files). Include your IDs in the name of your compressed file. 
Submit on the Assignment (Part A) link. Only one single submission per group. 
Plagiarism and other project guidelines: 
* If your diagram elements are too small then a ZERO mark would be awarded. In 
addition, ensure that the layout of your diagram is good (e.g., avoid many crisscrosses,
etc.) and the font size of the entities, attributes etc. is at least Arial 11 (or 
similar size if using a different font family, style). Make your diagram easy to read for 
the grader. You might want to use print settings for ERD with multiple (A4) pages or 
format diagram as per A3 size. Please put in effort to make it presentable and readable 
or risk losing marks. 
Use of any AI tools is NOT Permitted for the course assessments. You can find 
more information about the Student Academic Integrity Policy here. This will lead 
to a ZERO and may lead to an academic investigation by the Academic lead. 
We suggest you keep a record of the intermediate work (work in progress) leading up 
to your assignment submission as you may be asked to establish that this is your work 
and is done over a period of time. 
 
**A ZERO mark wil代 写158.337、Java/Python
代做程序编程语言l be given to ALL the collaborating parties (no discussion on 
who did the original work and who copied). Any partial copying will also be awarded 
a straight ZERO. 
Make sure all your work is complete before you submit. Graders will not be 
searching/chasing you for any not easily traceable/missing assignment components. 
Not adhering to any of the assignment requirements, may also be given a straight 
ZERO. 
Note: Turnaround time for assignment may be slightly over the usual three weeks. 158337, S2, 2024 Page 5 of 9 Project Instructions IN 
CONFIDENCE 
Appendix A 
Te Ohanga Village, Albany - Massey University Student 
Accommodation Office Case Study 
The Director of Te Ohanga Village, Albany - Massey University Student 
Accommodation Office requires you to design a database to assist with the 
administration of their accommodation office. After involving various stakeholders, 
the requirements collection and analysis phase of the database design process has 
provided the following requirements for the Student Accommodation Office database. 
These requirements are followed by examples of the query transactions that must all 
be supported by the database design. 
1. The data stored on each full-time student must include student details such as the 
identification number, name, home address, age, gender, category of student (e.g., 
undergraduate, postgraduate), nationality, smoker/non-smoker, special needs, any 
additional comments, status (e.g., placed/waiting), and what degree course the 
student is studying towards, etc. Accommodation is available for students with 
accessibility requirements, but these must be recorded in the system. 
 
The student information stored relates to those currently renting some form of 
accommodation and those on the waiting list. Students may rent a room in a hall 
of residence or a student flat (4-5 bedrooms apartments). Post-graduate, mature 
students may in addition opt for renting studio units. 
When a student joins the university, he or she is assigned to a staff member who 
acts as his or her Advisor (of studies). The Advisor is responsible for monitoring 
the student's welfare and overall academic progress. The data held for a student's 
Advisor includes their name, position, name of department, internal telephone 
number, room number, etc. 
2. Each hall of residence has a name (e.g., Tui, Pukeko, Weka), address, telephone 
number, and a hall manager who supervises the operations of the hall. The halls 
provide only single rooms, which have a room number, place number, and 
monthly rent rate. These have shared, private bathrooms and communal areas on 
each floor. Currently, each of the three halls can accommodate up to 70 students. 
Halls of residence offer fully catered services (2 meals per day) but can 
accommodate to various dietary requirements. 
The place number uniquely identifies each room in all the halls controlled by the 
student accommodation office and is used when renting a room to a student. 
3. The accommodation office also offers student flats. These flats are fully furnished 
and provide single room accommodation for groups of four to five students. They 
have common areas that flat members share. The information held on student flats 
includes a flat number, address, and the number of single bedrooms available in 
each flat. The flat number uniquely identifies each flat. Flats are self-catered. 
Currently there are 70 flats. 158337, S2, 2024 Page 6 of 9 Project Instructions IN 
CONFIDENCE 
Each bedroom in a flat has a monthly rent rate (this can occasionally very based 
on the room area), a room number, and a place number. The place number 
uniquely identifies each room available in all student flats and is used when 
renting a room to a student. 
4. The studio units offered by the accommodation office allow only for single 
occupancy (i.e., cannot be shared by the students). Mature students with small 
families usually rent these units (e.g., they can have a partner and/or a child living 
with them). The number of members residing in a unit needs to be recorded along 
with some essential details about each of the members (name, age, etc). 
Each studio unit has a monthly rent rate, and a unique studio unit number. In 
addition, studio units have the fully or partly furnished options but are selfcatered.
Currently there are 12 units. 
5. A student may rent a room (in a hall or student flat) or a studio unit for various 
periods. They need to sign a rent lease agreement before they can move in. 
New lease agreements are negotiated at the start of each academic year with a 
minimum rental period of one year, which includes semesters 1, 2 and the summer 
semester. Each individual lease agreement between a student and the 
accommodation office is required to be unique. 
The data stored on each lease includes the duration of the lease (given as 
semesters), student details, place number, room number, address details of the hall 
/ student flat / studio, the date the student wishes to enter the room, and the date 
the student wishes to leave the room (if known), etc. 
6. At the start of each semester, each student is sent an invoice for the ensuing rental 
period. Each invoice has a unique invoice number. 
The data stored on each invoice includes the invoice number, lease number, 
semester, payment due, student’s ID number and full name, place number, room 
number, and the address of the hall or flat. Additional data is also held on the 
payment of the invoice and includes the date the invoice was paid, the method of 
payment (e.g., cheque, cash, etc.), and the date the first or second payment 
reminder is sent (if necessary), etc. 
7. Staff on a regular basis inspect student flats and studio units to ensure that the 
accommodation is well maintained. The information recorded for each inspection 
is the name of the member of staff who carried out the inspection, the date of 
inspection, an indication of whether the property was found to be in a satisfactory 
condition or not, any additional comments, etc. 
 
8. Some information is also held on members of staff of the accommodation office 
and includes the staff number, home address, sex, position (e.g., Hall Manager, 
Administrative Assistant, Cleaner, etc.), location (e.g., accommodation office, 
Hall), etc. 
 158337, S2, 2024 Page 7 of 9 Project Instructions IN 
CONFIDENCE 
9. The accommodation office also stores a limited information on the degree courses 
run by the University such as degree title, degree director name, internal telephone 
number, and room number, department name, etc. Each student is associated with 
a single degree course. 
 
10. Information on a student's next-of-kin is stored which includes the name, 
relationship, contact details, etc. This information disclosure is not mandatory. 
 
 158337, S2, 2024 Page 8 of 9 Project Instructions IN 
CONFIDENCE 
Query Transactions 
 
The following transactions must be supported by your database design. However, you 
are NOT required to implement these transactions (in Part B you will write code so 
there is no need to write the SQL code for these queries). Use the following only to 
validate your database design using a dry run. All the attributes are spelled out in the 
description above but may be part of the transactions listed below. 
a) Create a suburb-wise staff list (based on their residential address). 
b) Create a list of students and staff who have their birthday next month. 
c) Create a list of post-graduate students who live in studio units. 
d) Create a report listing halls of residence Manager’s name and telephone 
number. 
e) Create a report listing students’ names, ID numbers and the details of their rent 
lease agreements. 
f) Display the details of lease agreements that include the Semester 1 and 2. 
g) Display the students who are paying over $1500 monthly for their room in a 
flat. 
h) Create a report on students that have not paid their invoices by a given date. 
i) Display the details of flat and studio inspections where the property was found 
to be in an unsatisfactory condition along with the comments. 
j) Create a report of the names and ID numbers of students with their room 
number and place number in a hall of residence. 
k) Create a report listing the details of all students currently on the waiting list for 
accommodation. 
l) Display the total number of students in each student category. 
m) Create a report listing the names and ID numbers for all students who have not 
supplied details of their next-of-kin. 
n) Display the minimum, maximum, and average monthly rent for rooms in halls 
of residence. 
o) Create a report listing students who have opted for Vegetarian or Vegan as 
their catering option. In the report include their hall of residence as well. 
p) Display the total number of rooms currently occupied and total number of 
places available in each hall of residence. 
q) Display the staff number, name, age, and current location of the staff who 
have been working 5 years or more at the accommodation village. 
r) Create a staff telephone directory in the order of family name. 
s) Create a report listing names and internal telephone numbers of the Advisors 
along-with their student names. 
t) List students who have any accessibility requirements along with the special 
requirement(s). 
u) List details of all the members who are residing with students in their studio 
units. 
v) List the number of flats or studio units that are not rented.158337, S2, 2024 Page 9 of 9 Project Instructions IN 
CONFIDENCE 
Appendix B 
158.337 Project Marking Sheet (Part A – 17.5% course mark) 
 (Attach this to your project report BEFORE you turn it in.) 
(Please make sure you provide all the necessary details) 
Oracle Account: Group___ 
Group Member 1 (Who Submits) - ID number, Name 
Group Member 2 - ID number, Name 
Group Member 3 - ID number, Name 
Group Member 4 - ID number, Name 
 
(Grader’s section, please do not write below this) 
PART A: _____/60 marks 
 
Logical Database Design (Step 1): /30 marks 
 
 
Physical Database Design (Step 2 and 3): /30 marks 
  
Part A: 17.5%, Part B: 17.5% (Total Course Percentage for the project – 35%) 

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
