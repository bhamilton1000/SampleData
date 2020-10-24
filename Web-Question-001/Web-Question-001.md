# Web-Question-001

##EASY
---
1.  Given an array of integers, find the best series of 3 within the array.  Return the index of the starting position and the sum of the qualifying elements.
	int[] intArray = new int[] { 1, 2, 3, 1, 3, 2, 5, 0, 1, 2 };

	> NOTE: (1) The array could be different each time the code is run
		(2) The best series number, in this case 3, could change
		(3) Handling of edge cases and exceptions

2.  Given a string, traverse the string to get the count of the number of times each character appears.  Sort the result ascending.
	string myString = "The quick brown fox jumps over the lazy dog";

	> NOTE: (1) The string could be different each time the code is run
		(2) Handling of upper-case, lower-case, accents, non-alpha and non-numeric characters, non-printable characters
		(3) Handling of edge cases and exceptions

3.  Given a string, rotate (or pivot) the string on a given index, in this case index = 5 (the comma). 
	string myName = "Smith, Jonathan";

	> NOTE:	(1) The string could be different each time the code is run
		(2) Handling of edge cases and exceptions

4.  Given a 2 dimensional array of char, starting at 0,0 (the S) determine the path through the 2D plane to get to the end (the E).  Return a list of points (X, Y) for the path.
	`char[,] gameBoard = new char[,] {
		{ 'S', ' ', 'X', 'X', 'X', 'X' },
		{ 'X', ' ', 'X', 'X', 'X', 'X' },
		{ 'X', ' ', ' ', ' ', 'X', 'X' },
		{ 'X', 'X', 'X', ' ', 'X', 'X' },
		{ 'X', 'X', 'X', ' ', ' ', ' ' },
		{ 'X', 'X', 'X', 'X', 'X', 'E' }
	};
	`
	> NOTE:	(1) The 2D array could be different each time the code is run
		(2) 'E' could be anywhere, but assume there always has to be 1 'S' and one 'E'

---
##MEDIUM
---

1.  Without using any library or framework classes, create your own singularly linked list (forward only) in C#.
	Add 5 nodes to the list.
	Create a new Node object.
	Insert the new Node object into position 3.

2.  Without using any library or framework classes, create you own bubble sort.  Sort this data on StateName descending.
	https://bhamilton1000.github.io/SampleData/Web-Question-001/UnitedStatesWithCounties.json

	> NOTE:	(1) You do not need to call and load the data, you may simply include the file locally in your solution

3.  Without using any library or framework classes, write a program which uses recursion to iterate the list of states and for each StateName, get the count of counties recursively.
	https://bhamilton1000.github.io/SampleData/Web-Question-001/UnitedStatesWithCounties.json

	> NOTE:	(1) Although this data is laid out to easy iterate the items to get the data, do not linearly process the list.  Recurse!

4.  Given a list of string, for each item in the list, determine if the word is a palindrome.  A palindrome is a word which is spelled the same way forward and backwards.
	https://bhamilton1000.github.io/SampleData/Web-Question-001/PalindromeData.cs


---
##HARD
---
