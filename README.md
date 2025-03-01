# Students

## Description  
This is a menu-driven Java program that demonstrates classes, constructors, array of objects, instance members, and CRUD operations.  
The program allows users to **add, display, search, update, and delete students** using an **ArrayList**.

## Features  
**Add Students** (with attributes like PRN, Name, Branch, Batch, CGPA)  
**Display All Students**  
**Search Students** (by PRN, Name, Position in List)  
**Update Student Details**  
**Delete a Student by PRN**  
**Menu-driven using switch-case**  


## How to Run 
<li> <ol> Clone this repository </ol>
git clone https://github.com/yourusername/Student-Management-Java.git
<ol>Navigate to project folder</ol>
<ol>Compile and Run the Java Program</ol></li>
javac Main.java
java Main

## Metods and Functionalities
<li><ol>1️. Student.java (Defines Student Class)</ol>
<p>This class represents a Student with attributes such as name, PRN, branch, batch, and CGPA. It includes getters, setters, and a method to display student details.</p>

<h5>Method	Description</h5>
<li> <ol>Student(String name, long prn, String branch, String batch, double cgpa)	Constructor to initialize student details</ol>
String getName()	Returns the student's name
void setName(String name)	Updates the student's name
long getPRN()	Returns the student's PRN
void setPRN(long prn)	Updates the student's PRN
String getBranch()	Returns the student's branch
void setBranch(String branch)	Updates the student's branch
String getBatch()	Returns the student's batch
void setBatch(String batch)	Updates the student's batch
double getCGPA()	Returns the student's CGPA
void setCGPA(double cgpa)	Updates the student's CGPA
void display()	Displays student details </li>

<ol>2️. StudentOperations.java (CRUD Operations)</ol>
<p>This class manages student records using an ArrayList and provides methods to add, display, search, update, and delete students.</p>

Method	Description
void addStudent(Student student)	Adds a new student to the list
void displayStudents()	Displays all students in the list
Student searchByPRN(long prn)	Searches for a student by PRN and returns the student object
Student searchByName(String name)	Searches for a student by name and returns the student object
Student searchByPosition(int position)	Searches for a student at a given position (index) in the list
boolean updateStudent(long prn, String name, String branch, String batch, double cgpa)	Updates student details by PRN
boolean deleteStudent(long prn)	Deletes a student from the list based on PRN

<ol>3️. Main.java (Menu-Driven Program)</ol></li>
<p>This class serves as the entry point for the program, displaying a menu for users to interact with. It calls methods from StudentOperations.java based on user input.</p>


