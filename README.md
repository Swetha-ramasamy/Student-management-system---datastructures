# Student-management-system---datastructures

Student management system – using data structures 

Data structures concepts used 
•	Linked list -Store the details of students 
•	Stack – for undo and redo options 
•	Bubble sort – sorting student marks to show rank 

Options in student management system 
•	Add 
•	Delete 
•	Modify 
•	Display rank list 
•	Search student 
•	Search for blood group 


PROBLEM DEFINITION

To create a student record management system that can perform certain operations using data structures 

Contents of the record 
•	Roll number 
•	Name 
•	Class
•	Tutor name
•	Address
•	Contact number 
•	Marks
•	Percentage 
•	Grade
•	Blood group

Operations performed 

1. Create and insert a record into list 
2.Delete a record 
3.Modify a record
4.Search and display a record 
5.Displaying all the records in list 
6.Displaying the students details having same blood group 
7.Displaying the rank list of the students 

1.create and insert a record into list 
The details of the students are stored in structure using create function.
The records are inserted at the beginning of the singly linked list.

2.delete a record 
Deleting the record based on roll number given by the user 
Traverse the list , if the given roll number matches the roll no in the list delete that particular record

3.Modify a record 
Modification is done by getting roll number as input and if the roll number matches with the record in the list then get the details of the student else print the record is not found 

4.Search and display the record 
If the roll number matches then display the details of the student

5. Displaying all the records in the list
Simply traverse the list and display all the records in the list 

6.Displaying the students details having same blood group 
Enter the blood group which the user needs , if the blood group matches with the user’s need , it will display the details of the student having that blood group.Here linear search technique is used 

7.Displaying the rank list of the students 
The marks is sorted using buuble sort and first 10 students marks is displayed with rank


