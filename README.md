# Security-authentication-program 

The program below is a security authentification program that asks the user to enter a 4 digit pin number. 
The user is allowed to encrypt and decrypt the code. The encrypted code is also compared with an authorised access code i.e. {4523}
this comparision is also stored in a variable. The program allows provides the number of times right and wrong code was entered by 
the variable that was stored while comparision during enxryption call. However, the user is allowed to decrpt the code if and only if 
it was encrypted first. Moreover, all the function parameters are passed by refrence. After each function is called the parameter is 
passed  back to main and the menu is displayed. The program will end when the user selects option 5.


input function description:-
1) Reads a 4 digit individual integer value and stores it in an integer array 



encryption function description:-
1) Swaps the 1st with 3rd element and 2nd with 4th element and adds 1 to each idividual digit.
2) If the individual digit is equal to 10 then the array elemet is changed to 0
3) Pointer notation and dereference operators are used.
4)Also comapres with available access code and verifies if the code entered is right or wrong and the counter is incremented by 1 using derefrence operator


decryption function description:-
1) If the individual digit is less than 1 to 9 then the array elemet is changed to 0
2) Swaps the 1st with 3rd element and 2nd with 4th element and adds 1 to each idividual digit.
3) Pointer notation and dereference operators are used.

display function description:-
1) Displays the number of time right and wrong code was entered


**IDE** :- Dev C++ (The program was developed and tested in Dev C++.)

**Language** :- C

**Author** :- _**Khushboo Jayan**_
