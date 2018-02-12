# Basic JS Exercises

### Exercise 1: Percentage

**Write a JavaScript function to calculate the percentage (%) of a given number.**

Test:
console.log(percentage(2000, 37.12));

Output:
742.4

------

### Exercise 2: Area of Triangle

**Write a JavaScript function to calculate the area of a triangle given the base and height.**

Test:
console.log(areaTriangle(5, 20));

Output:
50

------

### Exercise 3: Rotate String

**Rotate a given string in the right direction by periodically removing one letter from the end of the string and attaching it to the front.**

Test:
rotateString("cat");

Output:

cat

tca

atc

cat

HINT: Use *substring()*

------

### Exercise 4: Hide part of email address

**Write a JavaScript function to hide email addresses to protect from unauthorized user.**

Test:
console.log(protect_email("tom_jenkins@example.com"));

Output:
"tom_j...@example.com"

HINT: Use *split()* and *substring()*

------

### Exercise 5: Remove First Occurrence

**Write a JavaScript function to remove the first occurrence of a given 'search string' from a string.**

Test:
console.log(remove_first_occurrence("The quick brown fox jumps over the lazy dog", 'the'));

Output:
"The quick brown fox jumps over lazy dog"

HINT: Use *indexOf()* and *slice()*

------

### Exercise 6: Alphabetical Order

**Write a JavaScript function that returns a passed string with letters in alphabetical order.**

Test:
console.log(alphabetic_order('textbook'));

Output:
bekoottx

HINT: Use *join()*, *split()* and *sort()*

------

### Exercise 7: Most Frequent Item

**Write a JavaScript function to find the most frequent item in a given array.**

Test:
most_frequent([3, 'c', 'c', 'c', 2, 3, 'c', 3, 'c', 2, 4, 9, 3]);

Output:
c occurs 5 times

------

### Exercise 8: Remove Duplicate Values

**Write a JavaScript program to find and remove duplicate values in a JavaScript array.**

Test:
remove_duplicates([3, 'a', 'a', 'a', 2, 3, 'a', 3, 'a', 2, 4, 9, 3]);

Output:
[3, 'a', 2, 4, 9]

------

### Exercise 9: Dash between Even Numbers

**Write a JavaScript program which accepts a number as input and inserts dashes (-) between two consecutive even numbers.**

Test:
dash_in_even(012345684);

Output:
"012-456-8-4"

------

### Exercise 10: Guessing Game

**Write a JavaScript program where the program takes a random integer between 1 to 10, the user is then prompted to input a guess number. If the user input matches with guess number, the program will display a message "Good Work" otherwise display a message "Not matched"**

HINT: Use *Math.ceil()* and *Math.random()*

------

Source: [w3resource](http://www.w3resource.com/)
