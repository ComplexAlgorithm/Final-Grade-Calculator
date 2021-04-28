# Final-Grade-Calculator
Calculates final grade in computer science class.



Create a program that allows a user to calculate their final percentage and their letter grade in
this CSC 200 class based on their scores for each graded activity. The user will be prompted for
the score of each graded activity. There are 16 graded activities in this class. They are Concept
Test 1, Programming Test 1, Concept Test 2, Programming Test 2, Project 1, Project 2, Project 3,
Project 4, Project 5, Project 6, Project 7, Project 8, Project 9, Project 10, Concept Final, and
Programming Final. Every time a user enters a value for one of the graded activities the program
should check to make sure the value entered is a valid score for that graded activity. Every time
a user enters a value for one of the graded activities the program should check to make sure the
value entered is not less than 0 or greater than 100. If it is less than 0 or greater than 100, the
program should print an error message and prompt the user again to enter a valid score for that
activity. The user will continue to be prompted for a score until the user enters a score between 0
and 100.
This part of the program should be accomplished by the getScore method with the following
heading:
public static int getScore(String message)
After all the scores have been entered, the program will replace any lower score(s) from Concept
Tests with the one from the Concept Final. Then the program will replace any lower score(s)
from the Programming Tests with the one from the Programming Final.
This part of the program should be accomplished by the overrideScore method with the
following heading:
public static int overrideScore(int test, int finalTest)
Then the program will calculate the final percentage in the class based on the relative weight of
each the activities. Tests are 15% each, Programming Projects are 2% each, and each Final is
10%.
This part of the program should be accomplished by the calculateFinalPercentage method with
the following heading:
public static double calculateFinalPercentage(int conceptTest1, int programmingTest1, int
conceptTest2, int programming Test2, int Project1, int Project2, int Project3, int Project4,
int Project5, int Project6, int Project 7, int Project8, int Project9, int Project 10, int
conceptFinal, int programmingFinal)
Finally, the program will determine which letter grade the user should receive based on their
final percentage in this class (90-100 A, 80-89 B, 65-79 C, 1-69 D, 0 F).
This part of the program should be accomplished by the determineLetterGrade method with the
following heading:
public static char determineLetterGrade(double finalPercentage)
The program should end by printing the final percentage and the letter grade associated with that
percentage.
This part of the program should be accomplished by the printInfo method with the following
heading:
public static void printInfo(double finalPercentage, char letterGrade)

