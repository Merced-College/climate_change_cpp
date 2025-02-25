# climate_change_cpp
You will use this github repo for this assignment.

C++ Assignment: Binary Search on State Climate Data
Objective:

Modify the existing StateClimate program to allow the user to enter a state name, then use binary search to find and display the corresponding climate data.

Instructions:
Sort the vector of StateClimate objects by state name (you may need to modify the class to include state names).
Implement binary search to find the state entered by the user.
If the state is found, print its climate data.
If the state is not found, display an appropriate message.
Ensure proper input validation and case-insensitive search.
Requirements:
Modify StateClimate to include a state name field.
Use std::sort() to sort the vector before searching.
Implement binary search (do not use std::find or std::map).
Allow the user to search multiple times until they choose to exit.
Example Input/Output:
Enter a state name to search (or 'exit' to quit): California
FIPS: 6, Year: 2022, Temp (F): 65.2, Temp (C): 18.4

Enter a state name to search (or 'exit' to quit): Texas
FIPS: 48, Year: 2022, Temp (F): 70.3, Temp (C): 21.3

Enter a state name to search (or 'exit' to quit): Atlantis
State not found. Please try again.

Enter a state name to search (or 'exit' to quit): exit
Goodbye!

Bonus Challenge:
Allow partial name matching (e.g., searching for "Tex" should match "Texas").

Submission Instructions:
Submit your updated main.cpp and StateClimate.h/cpp.
Include comments explaining your binary search logic.
Ensure the program compiles and runs without errors.

This assignment tests sorting, searching, input handling, and vector manipulation in C++. 
