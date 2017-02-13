CS542 Design Patterns
Fall 2016
Assignment 2 

README FILE

Due Date: Friday, September 30, 2016.
Submission Date: Saturday, October 1, 2016.

Author(s): Sumanth Venkata Naga Satya Chadalla	
e-mail(s): schadal1@binghamton.edu	


PURPOSE:

Assignment Goal: Develop a program, using Java, to assign courses to students based on their preferences with multithreading.

PERCENT COMPLETE: I have completed 100% of this project.

PARTS THAT ARE NOT COMPLETE: There is no part that is not complete.

BUGS: None

FILES:
 ------driver:
				  --Driver.java [Base Class]
		------store:
				  --Results.java
				  --FileDsiplayInterface.java [Interface]
				  --StdOutDisplayInterface.java [Interface]
		------threadMgmt:
				  --CreateWorkers.java 
				  --WorkerThread.java 
		------util:
				  --CourseAssignor.java
				  --Scheduler.java				  
				  --Course.java
				  --FileProcessor.java
				  --Logger.java
				  --ObjectPool.java				 
				  —-Student.java
***************************************************
SAMPLE OUTPUT:

Student_1 B C D E F 20
Student_2 D E F G A 23
Student_3 A B C D E 15
Student_4 F G A B C 19
Student_5 C D E F G 25
Student_6 G A B C D 17
Student_7 E F G A B 21
Student_8 E F G A B 21
Student_9 F G A B C 19
Student_10 D E F G A 23

The average preference is 19.9125
***************************************************
TO COMPILE:

ant -buildfile build.xml all

NOTE: Please put the Input file where the source file is there in directory.

TO RUN:
Please go to the directory where build.xml is present and run 

ant -buildfile build.xml run -Darg0=input.txt -Darg1=output.txt -Darg2=3 -Darg3=4 

To CLEAN:
ant clean
 
TO UN-TAR:
tar xvzf sumanth_chadalla_assign2.tar.gz

Data Structure Used:
***************************************************
I am using ArrayList Data Structure.
I am using this beccause add and retrieve takes only O(1) time to execute. 
And is very easy to handle and use.

Time Complexity is 0(n).			   
			   
***************************************************			  
	


EXTRA CREDIT:

N/A
