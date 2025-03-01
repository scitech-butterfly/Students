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
<li>
    <ol>Student(String name, long prn, String branch, String batch, double cgpa) Constructor to initialize student details</ol>
    <ol>String getName() Returns the student's name</ol>
    <ol>void setName(String name) Updates the student's name</ol>
    <ol>long getPRN() Returns the student's PRN</ol>
    <ol>void setPRN(long prn) Updates the student's PRN</ol>
    <ol>String getBranch() Returns the student's branch</ol>
    <ol>void setBranch(String branch) Updates the student's branch</ol>
    <ol>String getBatch() Returns the student's batch</ol>
    <ol>void setBatch(String batch) Updates the student's batch</ol>
    <ol>double getCGPA() Returns the student's CGPA</ol>
    <ol>void setCGPA(double cgpa) Updates the student's CGPA</ol>
    <ol>void display() Displays student details</ol>
</li>

<ol>2️. StudentOperations.java (CRUD Operations)</ol>
<p>This class manages student records using an ArrayList and provides methods to add, display, search, update, and delete students.</p>

<ol>Method Description</ol>
<ol>void addStudent(Student student) Adds a new student to the list</ol>
<ol>void displayStudents() Displays all students in the list</ol>
<ol>Student searchByPRN(long prn) Searches for a student by PRN and returns the student object</ol>
<ol>Student searchByName(String name) Searches for a student by name and returns the student object</ol>
<ol>Student searchByPosition(int position) Searches for a student at a given position (index) in the list</ol>
<ol>boolean updateStudent(long prn, String name, String branch, String batch, double cgpa) Updates student details by PRN</ol>
<ol>boolean deleteStudent(long prn) Deletes a student from the list based on PRN</ol>


<ol>3️. Main.java (Menu-Driven Program)</ol></li>
<p>This class serves as the entry point for the program, displaying a menu for users to interact with. It calls methods from StudentOperations.java based on user input.</p>


