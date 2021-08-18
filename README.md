# Checkbook balancing program.
The program will read in, from the console, the following for all checks that were not cashed as of the last time you balanced your checkbook: the number of each check (int), the amount of the check (double), and whether or not it has been cashed (1 or 0, boolean in the array). 
Use an array with the class as the type. The class should be a class for a check. There should be three member variables to record the check number, the check amount, and whether or not the check was cashed.
The class for a check will have a member variable of type Money (as defined on page 662 in the book; Display 11.9) to record the check amount. So, you will have a class used within a class. 
The class for a check should have accessor and mutator functions as well as constructors and functions for both input and output of a check.  

In addition to the checks, the program also reads all the deposits (from the console; cin), the old and the new account balance (read this in from the user at the console; cin). You may want another array to hold the deposits. The new account balance should be the old balance plus all deposits, minus all checks that have been cashed.

The program outputs the total of the checks cashed, the total of the deposits, what the new balance should be, and how much this figure differs from what the bank says the new balance is. It also outputs two lists of checks: the checks cashed since the last time you balanced your checkbook and the checks still not cashed. 

[ edit: if you can, Display both lists of checks in sorted order from lowest to highest check number.]
