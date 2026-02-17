# Smart-Registration-System
A university is developing a Smart Registration System to approve student accounts only if their credentials strictly follow university-defined rules. The goal of this challenge is to design a Credential Validator that checks multiple input fields and decides whether a student account should be approved or rejected.

📌 Project Title
Smart-Registration-System


📖 Description

This program validates:

Student ID

Email ID

Password

Referral Code

If all conditions are satisfied → prints Approved, otherwise Rejected.

🛠 Validation Rules
✅ Student ID

Must start with "CSE"

4th character must be -

Remaining characters must be digits
Example: CSE-123

✅ Email ID

Must contain '@' and '.'

Must not start or end with '@'

Must end with .edu

✅ Password

Minimum 8 characters

First letter must be uppercase

Must contain at least one digit

✅ Referral Code

Must start with "REF"

Characters at position 3 and 4 must be digits

Must end with @

▶️ How to Run
python filename.py

📤 Output
Approved


or

Rejected

🎯 Concepts Used

startswith()

endswith()

String slicing

Conditional logic

Boolean flag validation
