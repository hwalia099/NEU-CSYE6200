This is a group project for course CSYE6200 and belowing the details mentioned:
 
The projects flow is mainly concentrated on developing using MVC and Factory Design Pattern.
In Model, the dependencies and fields are created through Person, Classroom, Student, Teacher, Immunization classes .
In View, the main GUI components are built using Java Swing.
The Controller represents the classroom grouping with Immunization records of students recording and retrieving the timelines of Vaccinations through StudentController, TeacherController, ImmunizationController. This acts as an interface between the model and view components.
The GUI part shows the DayCare Website where Student registration, Immunization records tracking and Teacher records with classroom grouping on different ratio rules of the data.
Through CSV files the  data is inputted to H2 Database Engine which retrieves the Student’s and Teacher’s data Immunization records of students, and the timelines are recorded and depending on the different timelines of vaccination due alerts are created.
The detailed website is created for all the Daycare activity tracking using JavaSwing with Spring Boot has back-end element and different threading elements are also implemented.
Objects from CSV:  
   	Student: Student Enrollment Roster
   	Teacher: Employee Roll
	 DayCare Ratio Rules: Student to Teacher::Groups to Classroom
