# SleepyBears

University Grading Platform made by a group of students at the Software Engineering Course.

# Client (web)

 ## Technology: Angular

# Backend

 Technology: Golang

# Database

 Technology: MongoDB

# Requirements

# Actors:

 All inherit User:
 
    • Student
    • Teacher
    • Chief of Department (inherits teacher)
    • Staff
    • Admin
    
# Actions:
  
User:

    • Sign In
    • Manage profile
    • Logout
    
Student Actions:
  
    • Enroll
    • View Curriculum
    • Manage optional courses
    • Sign contract of students
    • View Courses
    
Staff:
    
    • Assign student to optional
    • View students in group result
    • View students in year by result or criteria
    • View students ranking by semester
    • Generate document (extended above)

Teacher:
    
    • Propose optional courses
    • Add grade for student

Chief of Department:

     • Review list of optional courses
     • Set number of students for course
     • View teacher with best/worst results
     • View disciplines for teacher

Admin:

    • Create accounts

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

