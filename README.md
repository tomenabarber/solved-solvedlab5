Download Link: https://assignmentchef.com/product/solved-solvedlab5
<br>
This hands-on lab allows you to follow and experiment with the critical steps of developing a program including the program description, Analysis, , Design(program design, pseudocode), Test Plan, and implementation with C code. The example provided uses sequential, repetition statements and nested repetition statements.

Program Description:This program will calculate the average of 3 exams for 5 students. The program will ask the user to enter 5 student names. For each of the students, the program will ask for 3 exam scores. The student name and the average exam score for each student will be calculated and printed.

Analysis:The program will consist of two loops. An outer loop for each student and an inner loop for the exams of each student. I will define one String to store student name: StudentName.

I will define three Float variables: Examvalue, Sum, Avg to store exam values, the sum of the exams, and the average of the exams.

The sum will be calculated by this formula: Sum = Sum + Examvalue

For example, if the first value entered was 80.0 and second was 90.0 and the third exam was 100.0: sum = sum + Examvalue = 0.0 + 80.0

sum = 80.0 + 90.0 = 170.0

sum = 170.0 + 100.0 = 270.0

Avg is then calculated as: Avg = sum/3.0

For example 270.0/3.0 = 90.0

A nested repetition loop can be used to loop through each of the 5 students and each of the 3 exams: For (students=0; students &lt;5; students++)

For (exams=0;exams&lt;3;exams++) End For

End For

Sum values will need to be reset for each student to ensure only one student data is used for calculations each time.