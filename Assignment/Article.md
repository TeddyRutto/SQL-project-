SQL BASICS AND DATA TRANSFORMATION.
SQL (Structured Query Language) is a standard programming language designed for managing, manipulating and retrieving data stored in a relational database management system. It operates by sending queries to a database, which then returns the requested information. 
SQL commands are categorized based on their function. Commands are generally categorized into two main groups: DDL (Data Definition Language and DML (Data Manipulation Language). 
1. DDL
This commands are used to create, modify, change or delete database. Its commands includes, CREATE, ALTER and DROP. 
CREATE
Create database or schema table. During the Nairobi Academy assignment, we started by defining the structure of the table using CREATE. We created tables and its columns like student table with student_id, first_name, last_name, gender, date_of_birth, class and city, ensuring each piece of data had a designated home.
ALTER 
After defining your table one can do changes such as add column, change table or column name using ALTER.
DROP 
This is used to delete a column or table 

phone number column is deleted.2.DML
DML commands are used to manage the data inside structures. They allow you to add, change, update or remove rows and data. Command include; INSERT, UPDATE, DELETE, SELECT.
INSERT
Once the tables existed, we use INSERT INTO to populate them.
We added 10 students, 10 subjects, and their corresponding exam results, turning empty structures into a functional dataset.UPDATE
We use UPDATE to modify existing records-such as correcting a student's marks or updating a teacher's name-ensuring the information remained accurate without having to delete and re-type it.
DELETE 
When data is no longer needed or entered in error, we use DELETE to remove it. This is important for precision, to ensure we don't accidentally wipe out the entire table.
SQL FILTERING WITH WHERE.
WHERE is mainly used to filter data. It prevents information overload by allowing us to see only the rows that matter. By using different operators, we can get very specific:
= (Equality): Finding students in a specific city (WHERE city = 'Nairobi').
> (Greater Than): Identifying top performers (WHERE marks > 80).
BETWEEN (Range): Finding data within a specific window, such as an exam period (WHERE exam_date BETWEEN '2024-03-01' AND '2024-03-31').
IN (Membership): Selecting from a list of options without writing multiple "OR" statements (WHERE city IN ('Mombasa', 'Kisumu')).
LIKE (Search): Finding partial matches using wildcards, such as finding all students name start with A or E(WHERE student_name LIKE 'A'%' OR 'E%').

DIFFERENT OPERATORS IN USETRANSFORMING DATA WITH CASE WHEN 
CASE WHEN is SQL'S way of asking 'if this, then that'. Used in making decisions. In the case of our assignment, we used this to turn numerical marks to performance level.
This transformation is vital because it turns a technical table into a readable report that a teacher or principal can understand at a glance. It allows the database to do the analysis for you, moving beyond just storing data to actually interpreting it.
CONCLUSION
My journey with SQL was a mix of technical hurdles. While I initially found the placement of the asterisk and the logic of the LIKE function to be challenging, overcoming these syntax hurdles was rewarding. Ultimately, I was impressed by how effortlessly SQL handles data transformation and analysis, turning complex datasets into clear, actionable insights.