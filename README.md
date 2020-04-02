# Department database 
The program help user to store data of each person in the department. And shows the realtive people taking/teaching the same course. The program uses the inheritance.

##  Author
Runduo(Melody) Ma (rma76@wisc.edu)
##  Organization of the code
- Person.h, Person.cpp, Employee.cpp, Employee.h, Student.cpp, Student.h, Faculty.cpp, Faculty.h, TeachingAssistant.cpp, TeachingAssistant.
These classes represent the different kind of people in the department. Employee's base class is Person. Student's base class is Person. Faculty's base class is Employee. TeachingAssistant's base class is Student and Employee.
-  DisplayUtility.h, DisplayUtility.cpp. They are used to show the specific kinds of people with the same course ID.
- demo.cpp
it calls the class and function.


### Requirement  
- g++ 7.4.0 or above

## Compile and Run
The program has its own makefile, if you use linux:

* type make to compile
* type ./demo to execute
'''
make
./demo
'''
Then the program will work and show the result.




