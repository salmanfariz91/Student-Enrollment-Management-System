# Student-Enrollment-Management-System
“I built a full-stack Student Management System in Zoho Creator, integrated with Zoho CRM & Zoho Catalyst.

🔑 Modules (Forms & Fields)
1. Student Registration Form

Fields: Name, DOB, Age (formula), Phone, Email, Address, Course Lookup.

Validations:

Auto-calc Age from DOB.

Phone = 10 digits.

Only @gmail.com allowed.

Age < 18 → reject.

2. Course Management Form

Fields: Course Name, Duration, Fees, Trainer Lookup.

3. Trainer Form

Fields: Name, Expertise, Phone, Email.

4. Payment Form

Fields: Student Lookup, Course Lookup, Amount, Payment Date, Payment Status.

Auto-calc pending fees.

🔑 Reports

Student Report → Table of all students (filters: Course, Age).

Course Enrollment Report → Shows students per course.

Fee Collection Report → Pending vs Paid fees.

Trainer Report → Trainer details + assigned courses.

Dashboard (Pages) → Charts (Pie: Enrollment by Course, Bar: Fees collected vs pending).

🔑 Workflows (Deluge Scripts)

Age Validation → Block if < 18.

Phone Validation → Exactly 10 digits.

Auto Email on Registration → “Welcome, you are registered for [Course].”

Payment Reminder (Scheduled) → Send reminder email for pending fees.

Auto-assign Trainer → Based on course selection.

🔑 Roles & Permissions

Admin → Full access.

Trainer → View only their students.

Student → View their own details + payment history.

🔑 Integrations

Zoho Books / Invoice → Auto-create invoice on payment.

Zoho Mail → Send welcome emails & reminders.

Zoho Crm -leads manage.

API → Expose student enrollment API (to show you know integrations).

