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
<ol> <li> Clone this repository </li>
git clone https://github.com/scitech-butterfly/Students.git
<li>Navigate to project folder</li>
<li>Compile and Run the Java Program</li></ol>
javac Main.java
java Main

## Metods and Functionalities
<ol><li>Student.java (Defines Student Class)</li>
<p>This class represents a Student with attributes such as name, PRN, branch, batch, and CGPA. It includes getters, setters, and a method to display student details.</p>

<b>Method Description</b>
<ol>
    <li>Student(String name, long prn, String branch, String batch, double cgpa) Constructor to initialize student details</li>
    <li>String getName() Returns the student's name</li>
    <li>void setName(String name) Updates the student's name</li>
    <li>long getPRN() Returns the student's PRN</li>
    <li>void setPRN(long prn) Updates the student's PRN</li>
    <li>String getBranch() Returns the student's branch</li>
    <li>void setBranch(String branch) Updates the student's branch</li>
    <li>String getBatch() Returns the student's batch</li>
    <li>void setBatch(String batch) Updates the student's batch</li>
    <li>double getCGPA() Returns the student's CGPA</li>
    <li>void setCGPA(double cgpa) Updates the student's CGPA</li>
    <li>void display() Displays student details</li>
</ol><p></p>

<li>StudentOperations.java (CRUD Operations)</li>
<p>This class manages student records using an ArrayList and provides methods to add, display, search, update, and delete students.</p>
<ol><b>Method Description</b>
<li>void addStudent(Student student) Adds a new student to the list</li>
<li>void displayStudents() Displays all students in the list</li>
<li>Student searchByPRN(long prn) Searches for a student by PRN and returns the student object</li>
<li>Student searchByName(String name) Searches for a student by name and returns the student object</li>
<li>Student searchByPosition(int position) Searches for a student at a given position (index) in the list</li>
<li>boolean updateStudent(long prn, String name, String branch, String batch, double cgpa) Updates student details by PRN</li>
<li>boolean deleteStudent(long prn) Deletes a student from the list based on PRN</li></ol> <p></p>


<li>Main.java (Menu-Driven Program)</li></ol>
<p>This class serves as the entry point for the program, displaying a menu for users to interact with. It calls methods from StudentOperations.java based on user input.</p>


