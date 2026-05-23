Conditional Menu

A beginner-friendly Python project that demonstrates how to use conditional statements to create a simple menu system.

📌 Description

This program:

Takes a menu choice from the user
Checks the entered option using if-elif-else
Prints the selected operation
Displays an error message for invalid input

🧠 Concepts Used

if-elif-else
Conditional Statements
User Input
Integer Conversion using int()
print() function

💻 Code

choice = int(input("enter choice:"))

if choice == 1:
    print("addition")

elif choice == 2:
    print("substraction")

else:
    print("invalid input")

▶️ Example Output

enter choice: 1
addition
enter choice: 5
invalid input
