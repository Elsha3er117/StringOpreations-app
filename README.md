# StringOpreations-app
 
You will develop an application for performing operations on strings.
- First, develop a class StudentName that represents your full name and has only a variable name
of type string.
- Your class should contain a constructor that takes a string from user. The input string should
contain at least 2 spaces. If the user violates this rule, you should copy the last name many times
to make the names variable a name with 2 spaces.

“ahmed Mohamed sayed”➔ “ahmed Mohamed sayed”

“sara ahmed” ➔ “sara ahmed ahmed”

“Khaled” ➔ “ khled Khaled Khaled”

“aya ali ahmed sayed” ➔ “ aya ali ahmed sayed”

- Add a function print that prints the detailed parts of the name each in one line.
“aya ali ahmed sayed”
detailed parts of the name are:
1) aya
2) ali
3) ahmed
4) sayed
- Add function replace(int i,int j) that replaces the name at position I with the name at position j
and return true if operation is valid and false if one of the two indices is out of range.
“ahmed hassan ali”

replace(1,2) ➔ true ➔ “Hassan ahmed ali”

replace(3,1) ➔ true ➔ “ali Hassan ahmed”

replace(2,4) ➔ false

- Write a main function and 5 test cases with different names. For each test case you should call
the replace function and the print function to check the effect of the replacement if valid.
