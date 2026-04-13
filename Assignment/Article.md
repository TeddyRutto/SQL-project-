**SQL BASICS AND DATA TRANSFORMATION**.

SQL (**Structured Query Language**) is a standard programming language designed for managing, manipulating and retrieving data stored in a relational database management system. It operates by sending queries to a database, which then returns the requested information. 
SQL commands are categorized based on their function. Commands are generally categorized into two main groups: DDL (Data Definition Language and DML (Data Manipulation Language). 

**1. DDL**
This commands are used to create, modify, change or delete database. Its commands includes, CREATE, ALTER and DROP. 

--**CREATE**
Create database or schema table. During the Nairobi Academy assignment, we started by defining the structure of the table using CREATE. We created tables and its columns like student table with student_id, first_name, last_name, gender, date_of_birth, class and city, ensuring each piece of data had a designated home.
<img width="1000" height="661" alt="image" src="https://github.com/user-attachments/assets/02756856-cd79-4836-98a5-70df821a1ec8" />

--**ALTER** 
After defining your table one can do changes such as add column, change table or column name using ALTER.
<img width="1000" height="139" alt="image" src="https://github.com/user-attachments/assets/115e1e58-1f50-4c80-8ec5-fb0de3f507ae" />

--**DROP** 
This is used to delete a column or table 
<img width="1000" height="139" alt="image" src="https://github.com/user-attachments/assets/8d19baac-09de-4548-a911-2e24da8a4b5e" />
phone number column is deleted.

**2.DML**
DML commands are used to manage the data inside structures. They allow you to add, change, update or remove rows and data. Command include; INSERT, UPDATE, DELETE, SELECT.

--**INSERT**
Once the tables existed, we use INSERT INTO to populate them.
<img width="1000" height="602" alt="image" src="https://github.com/user-attachments/assets/5b9d1c50-9b7d-45ad-9892-e24985f211a8" />
We added 10 students, 10 subjects, and their corresponding exam results, turning empty structures into a functional dataset.

--**UPDATE**
We use UPDATE to modify existing records-such as correcting a student's marks or updating a teacher's name-ensuring the information remained accurate without having to delete and re-type it.
<img width="1000" height="602" alt="image" src="https://github.com/user-attachments/assets/50502169-4aaa-4980-9d11-24e1d68c97a1" />

--**DELETE** 
When data is no longer needed or entered in error, we use DELETE to remove it. This is important for precision, to ensure we don't accidentally wipe out the entire table.
<img width="1000" height="68" alt="image" src="https://github.com/user-attachments/assets/4d90a5a9-62d2-4848-a4ab-8be507cda293" />

**SQL FILTERING WITH WHERE.**
WHERE is mainly used to filter data. It prevents information overload by allowing us to see only the rows that matter. By using different operators, we can get very specific:

= (Equality): Finding students in a specific city (WHERE city = 'Nairobi').

 (Greater Than): Identifying top performers (WHERE marks > 80).

BETWEEN (Range): Finding data within a specific window, such as an exam period (WHERE exam_date BETWEEN '2024-03-01' AND '2024-03-31').

IN (Membership): Selecting from a list of options without writing multiple "OR" statements (WHERE city IN ('Mombasa', 'Kisumu')).

LIKE (Search): Finding partial matches using wildcards, such as finding all students name start with A or E(WHERE student_name LIKE 'A'%' OR 'E%').
<img width="1000" height="563" alt="image" src="https://github.com/user-attachments/assets/a1609d06-1aa6-4082-a9d2-b5ea559ea19b" />
DIFFERENT OPERATORS IN USE

**TRANSFORMING DATA WITH CASE WHEN**

CASE WHEN is SQL'S way of asking 'if this, then that'. Used in making decisions. In the case of our assignment, we used this to turn numerical marks to performance level.
<img width="1000" height="298" alt="image" src="https://github.com/user-attachments/assets/59a017bf-5c60-4c4d-9060-7a3f4986952f" />

This transformation is vital because it turns a technical table into a readable report that a teacher or principal can understand at a glance. It allows the database to do the analysis for you, moving beyond just storing data to actually interpreting it.

**CONCLUSION**

My journey with SQL was a mix of technical hurdles. While I initially found the placement of the asterisk and the logic of the LIKE function to be challenging, overcoming these syntax hurdles was rewarding. Ultimately, I was impressed by how effortlessly SQL handles data transformation and analysis, turning complex datasets into clear, actionable insights.
