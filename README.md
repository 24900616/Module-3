# List Operations in Python: Sum of List Items

NAME: Swetha K

REG NO: 212224230284

### 🎯 Aim
To write a Python program that calculates the sum of all elements in a list.

### 🧠 Algorithm

1.Define a list of numbers.

2.Use Python’s built-in sum() function to calculate the total.

3.Print the result.

### 🧾 Program
```
list=[1,2,-8]
total=sum(list)
print(total)
```
### Output
![image](https://github.com/user-attachments/assets/2e50aa73-53ad-4ad7-a9cc-1713893462e2)

### Result
Thus,the program has been executed successfully.

# Regex in Python: Filter Words Without the Letter 'e'

Name: Swetha K

Register No: 212224230284

### 🎯 Aim
To write a Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex).

### 🧠 Algorithm

1.Import the re module.

2.Initialize an empty list l1 to store results.

3.Define a list of words:

4.items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

5.Iterate through each word in the list:

6.Use re.search(r"e", i) to check if the word contains 'e'.

7.If not, append the word to l1.


8.Print the final filtered list.

### 🧾 Program
```
import re
l1=[]
items=['goal', 'new', 'user', 'sit', 'eat', 'dinner'] 
for i in items:
   if not re.search(r"e",i):
      l1.append(i)
print(l1)
```
### Output
![image](https://github.com/user-attachments/assets/25744d73-44f7-4159-8879-31891be287bf)

### Result
Thus,the program has been executed successfully.

# 🧹 Strings-Remove Nth Index Character from a String

Name: Swetha K

Register No: 212224230284

### 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

### 🧠 Algorithm


1.Define a function named remove that takes the input string as an argument.

2.Read the index n from the user input.

3.Initialize an empty string a to store the new string.

4.Iterate over each index of the string using a for loop.

5.Check if the current index i is not equal to n.

6.If i != n, append the character at index i to string a.

7.After the loop, return the modified string a.

8.Print the final result.

### 💻 Program
```
def remove(str):
  l=len(str)
a=""
n=int(input())
for i in range(0,l):
  if i==n:
    a=a+""
  else:
    a=a+str[i]
print(a)
```
### Output
![image](https://github.com/user-attachments/assets/239e9410-779d-4ce1-b133-c90d6cc12994)

### Result
Thus,the program has been executed successfully.

# Strings-Palindrome Check in Python (Without Built-in Functions)
Name: Swetha K

Register No: 212224230284

### 🎯 Aim
To write a Python program to check whether the string "google" is a palindrome or not, without using built-in palindrome checking functions.

### 🧠 Algorithm

1.Assign the string "google" to a variable.

2.Reverse the string manually using slicing ([::-1]).

3.Compare the original string with the reversed string.

4.If they are equal, print that the string is a palindrome.

5.Otherwise, print that it is not a palindrome.

6.Execute the program.

### 🧾 Program

```
string="google"
if string==string[::-1]:
   print ("The entered string is palindrome") 
else:
   print ("The entered string is not palindrome")
```
### Output
![image](https://github.com/user-attachments/assets/34c41ba9-6e09-4c48-82a5-810368d6078d)

### Result
Thus,the program has been executed successfully.

# Tuple in Python: Check Element Existence
Name: Swetha K

Register No: 212224230284

### 🎯 Aim
To write a Python program that checks if the element 'n' and the element 8 exist within a given tuple.

### 🧠 Algorithm

1.Define a tuple x with some letters and numbers.

2.Use the in operator to check if the string 'n' exists within the tuple.

3.Use the in operator to check if the integer 8 exists within the tuple.

4.Print the results.

### 🧾 Program
```
tuplex = ("s", "8", "a", "v", "n", "g", "u", "r", "c", "e")
print("n" in tuplex)
print("8" in tuplex)
```
### Output
![image](https://github.com/user-attachments/assets/8c90bfdc-0f4a-4d89-a1b3-7060667f58f4)


### Result
Thus,the program has been execueted successfully.


