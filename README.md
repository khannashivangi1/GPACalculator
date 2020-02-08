# GPACalculator

I created this project for my INFO 101 class at University of Massachusetts, Amherst.

The program is a GPA calculator. The user is asked to provide the following information:

A.	The number of courses the user has completed.
B.	The number of credit hours for each course.
C.	The letter grade for each course.

The program, then, converts the letter grade into number grade using the following scale:
| Letter grade  |  Numerical grade
| :-------------| :----------------
|A+ |  4.0
|A   | 4.0
|A-	 | 3.7
|B+  |3.3
|B    | 3.0
|B-	 |2.7
|C+  | 2.3
|C    | 2.0
|C-	 |1.7
|D+  | 1.3
|D    | 1.0
|F | 0.0


Then, the number of credits of each course is multiplied with its respective number grade to compute the total grade points earned. Finally, the GPA is calculated by dividing the total grade points by the total number of credits earned and rounding the result to 2 decimal places. 
If the GPA is greater than 2.0, the code prints a statement saying that the user is in good academic standing. Otherwise, it advices the user that he/she needs to improve his/her GPA. 
