USER FLOW
Step 0 — Registration
The user:
•	Creates an account
•	Enters their name
•	(Optional) Selects a learning goal: 
o	“For studies”
o	“For work”
o	“For personal development”
________________________________________
Step 1 — Level Selection (Self-Select)
The user is presented with the following options:
Select your level:
🟢 Beginner
“I have never programmed before or have very limited experience.”
🟡 Intermediate
“I have written code before and understand loops, conditionals, and functions.”
🔴 Advanced
“I can build programs and have experience with OOP, files, and possibly real projects.”
________________________________________
Step 2 — Path Allocation (Branching Logic)
A) If Beginner is selected → NO TEST REQUIRED
The user is immediately placed into the Beginner Track.
However, during the first two lessons, the system performs a soft diagnostic assessment (not labeled as a test) to understand the student’s learning needs.
________________________________________
B) If Intermediate is selected → INTERMEDIATE SCREENING (20 minutes)
Test Structure
Block 1 — Coding (4 tasks)
1.	Find the maximum value in a list without using max()
2.	Count word frequency in a string (dictionary-based solution)
3.	Implement a function is_palindrome(s)
4.	Implement FizzBuzz from 1 to n
Block 2 — Debugging (2 tasks)
Identify and fix the error in the following code:
nums = [1,2,3]
total =0for iinrange(len(nums)):
    total += nums[i+1]print(total)
________________________________________
Test Outcome (3 Scenarios)
Result	Next Step
Very weak (0–2/6)	Suggest moving to Beginner Track
Moderate (3–5/6)	Remain in Intermediate Track
Strong (6/6 + fast completion)	Offer upgrade to Advanced Track
________________________________________
C) If Advanced is selected → ADVANCED SCREENING (25–30 minutes)
Test Structure
Task 1 — Object-Oriented Programming (OOP)
Design the following class:
classBankAccount:pass
Requirements:
•	Maintain account balance
•	Implement deposit(amount)
•	Implement withdraw(amount) (must prevent negative balance)
•	Maintain a transaction log
________________________________________
Task 2 — Testing
Write at least 3 test cases for the withdraw() method (pytest-style acceptable).
________________________________________
Task 3 — Algorithmic Problem
Find the longest substring without repeating characters using a sliding window approach.
________________________________________
Test Outcome
 
