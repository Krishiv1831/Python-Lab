📋 LOOPS IN PYTHON

Name- Krishiv Sharma <br/>
Branch- EnTC A3 <br/>
PRN- 25070123065 <br/>

📘 Title Page

Project Name: Loops in Python <br/>
Purpose: Study of Looping Statements and Control Flow <br/>
Language: Python <br/>

---

🎯 Aim of the Study

The aim of this project is to study different looping statements in Python such as while, for, break, continue, and conditional statements like if and nested if.

This helps in understanding how to execute a block of code repeatedly and control the flow of execution efficiently.

📌 Introduction

Loops are used in programming to execute a block of code multiple times. Instead of writing repetitive code manually, loops allow automation of repeated tasks.

Python provides two main types of loops:

for loop

while loop

Additionally, control statements such as:

break

continue

if

nested if

are used to control loop execution.

📖 Study of Loops (Instructions)

Understand what loops are and why they are used <br/>

Learn syntax of for and while loops <br/>

Practice using break and continue <br/>

Understand conditional statements inside loops <br/>

Learn nested loops and nested if statements <br/>

Observe output changes with different conditions <br/>

Practice programs regularly for better understanding <br/>

🔑 Key Concepts

for loop

while loop

break statement

continue statement

if statement

nested if

nested loops

loop control flow

📘 Theory (Loops in Python)
1️⃣ For Loop

A for loop is used to iterate over a sequence (list, tuple, string, range).

Syntax:
for variable in sequence:
    # code block

Example:
for i in range(1, 6):
    print(i)

2️⃣ While Loop

A while loop runs as long as the condition is true.

Syntax:
while condition:
    # code block

Example:
i = 1
while i <= 5:
    print(i)
    i += 1

3️⃣ Break Statement

break is used to exit the loop immediately.

Example:
for i in range(1, 10):
    if i == 5:
        break
    print(i)

4️⃣ Continue Statement

continue skips the current iteration and moves to the next iteration.

Example:
for i in range(1, 6):
    if i == 3:
        continue
    print(i)

5️⃣ If Statement in Loop

Conditional statements help in decision making inside loops.

Example:
for i in range(1, 6):
    if i % 2 == 0:
        print("Even:", i)

6️⃣ Nested If Statement

An if inside another if is called nested if.

Example:
num = 10
if num > 0:
    if num % 2 == 0:
        print("Positive Even Number")

7️⃣ Nested Loops

A loop inside another loop is called a nested loop.

Example:
for i in range(1, 4):
    for j in range(1, 4):
        print(i, j)

🧠 Algorithm (Example: Print Numbers from 1 to 5 using While Loop)

Start

Initialize variable i = 1

Check condition i <= 5

If true, print i

Increment i by 1

Repeat steps 3–5

Stop when condition becomes false

🧠 Algorithm (Example: Check Even Numbers Using For Loop)

Start

Use for loop from 1 to 10

Check if number % 2 == 0

If true, print number

End loop

Stop

🔄 Flowchart (While Loop)
        ┌───────────┐
        │   Start   │
        └─────┬─────┘
              │
        ┌─────▼─────┐
        │ Initialize │
        │   i = 1    │
        └─────┬─────┘
              │
        ┌─────▼─────┐
        │ i <= 5 ?   │
        └─────┬─────┘
          Yes  │  No
              ▼
        ┌───────────┐
        │  Print i  │
        └─────┬─────┘
              │
        ┌─────▼─────┐
        │  i = i+1  │
        └─────┬─────┘
              │
              └───────────(Back to condition)
                        │
                        ▼
                   ┌────────┐
                   │  Stop  │
                   └────────┘

🔄 Flowchart (For Loop with Break)
        Start
          │
    Initialize Loop
          │
     Check Condition
          │
     ┌────┴────┐
   True       False
     │           │
 Check if i==5   Stop
     │
  ┌──┴──┐
 Yes    No
  │      │
 Stop   Print i

✅ Advantages of Loops

Reduces code repetition

Saves time and effort

Improves efficiency

Makes code cleaner and readable

Useful for data processing

❌ Disadvantages of Loops

Infinite loop risk

Hard to debug complex nested loops

Can reduce performance if not optimized

🛠 Tools Used

Python Interpreter

IDLE

VS Code

PyCharm

Command Prompt / Terminal

📂 Applications of Loops

Printing patterns

Searching elements

Data analysis

Game logic

Automation tasks

Mathematical calculations

🎯 Conclusion

Loops are fundamental building blocks in Python programming. They allow repetition of tasks efficiently and reduce manual coding effort. Understanding for, while, break, continue, and conditional statements is essential for writing powerful and structured programs.

📎 Extra Notes

Be careful of infinite loops

Always update loop variable in while loop

Use break to exit early

Use continue to skip unwanted values

Practice nested loops carefully

✨ End of README
