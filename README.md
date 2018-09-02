# relationship-practice

Howdy y'all!

The following relationship is between a Student and a Tutor through a TutorSession

Student ----< TutorSession >------- Tutor

# Domain Model
- One-to-many Student and TutorSession
  - TutorSession belongs to a Student and a Student has many TutorSessions
- One-to-Many Tutor and TutorSession
  - Tutor has many TutorSessions and a TutorSession belongs to a Tutor
- Student has many Tutors through a TutorSession
- Tutor has many Students through a TutorSession

# Student
**** Marks that it has been completed
+++++ Malcome has completed
- ****A student is initialized with a grade (Fixnum), name (String)
- ****Student.all
  - Expected Result: An array of student objects
- ****Student#create_session(tutor,time,weekday)
  - Expectation is to create a TutorSession
  - We know we need to pass in all the requirements to make a TutorSession
- ****Student#tutor_sessions
  - To see every tutor session that this student has done
  - Expectation Result: An array of TutorSessions
- ****Student#tutors
  - This student wants to see all of their tutors
  - Expected Result (the data type):  An Array of Tutors
- ++++++Student.highest_grade
  - Find the name of the student that has the highest grade.
  - Expected Result: An array of a string or strings of students names

# TutorSession
**** Marks that it has been completed
+++++ Malcome has completed
- ****A TutorSession is initialized a with a Student (Student object), a Tutor (Tutor object), time (Fixnum),
day_of_the_week (string)
- +++++++ Student.over_60_minutes
  - Find all students that were tutored for more then 60 minutes and find their grades. Put the result in an array.
  - Expected Result: Show an array of TutorSessions objects of tutorsessiosns at or over 60 minutes

# Tutor
**** Marks that it has been completed
+++++ Malcome has completed
- ****A tutor is initialized with a number of years tutored (Fixnum), name (String)
- ****Tutor#total_years
  - Returns the total years that this tutor has taught
- ++++++ Tutor.all
  - Returns an array of all tutor objects
- +++++++ Tutor.avg_exp 
  - Finds the average years of experience of all tutors
  - Expected Result: An integer for the average of total_years(years of experience)
# oo-relationships-practice-
# oo-relationships-practice-
# practice-relationships-oo
# practice-relationships-oo
