
🎓 Student-Teacher Appointment Booking System
A web-based application that allows students to schedule appointments with teachers online. It simplifies the interaction between students and faculty by eliminating traditional queuing and manual scheduling, and provides real-time access through web or mobile browsers.

📌 Problem Statement
Modern appointment booking systems aim to eliminate inefficiencies of traditional queue-based systems. This project enables both students and teachers to schedule, approve, and manage appointments remotely. It allows students to send messages regarding appointment purpose and timing, improving communication and transparency.

🚀 Features
👨‍🎓 Student
Register & login

Search for teachers

Book appointments

Send messages

View appointment status

👨‍🏫 Teacher
Login

View appointment requests

Approve or cancel appointments

View messages from students

🛠️ Admin
Add/Update/Delete teacher details (name, department, subject, etc.)

Approve student registrations

View all appointments

Monitor logs

🧩 Modules
Authentication: Secure login/register for students and teachers

Teacher Management: Admin can add/update/delete teacher profiles

Appointment Scheduling: Students can request bookings; teachers approve/cancel

Message Handling: Students can send purpose-specific messages to teachers

Logging: All actions are logged using JavaScript logging techniques

🛠️ Technologies Used
Frontend: HTML, CSS, JavaScript

Backend / Database: Firebase (Firestore, Authentication)

Hosting: Firebase Hosting (optional for deployment)

📐 Architecture Overview
lua
Copy
Edit
+---------------------+
|   Web Interface     | <--- Students / Teachers / Admin
+---------------------+
         |
         V
+---------------------+
|     Firebase        |
| - Auth              |
| - Firestore DB      |
| - Hosting (optional)|
+---------------------+
✅ Code Quality Guidelines
Modular structure

Safe and maintainable

Testable at component level

Portable across environments

GitHub version-controlled with clear commit history

Logging for every significant event

📊 Evaluation Metrics
Functional correctness of modules

Modular and reusable code

Firebase integration quality

Code documentation and readability

Logging functionality

README completeness

📄 Project Setup
Clone the repository

bash
Copy
Edit
git clone https://github.com/Annishivakumara/Student_Teacher_Booking_Appointment.git
cd Student_Teacher_Booking_Appointment
Open index.html in a browser
Ensure Firebase is connected properly for real-time features.

Firebase Setup

Create a Firebase project

Add Firestore & Authentication

Replace Firebase config in the JS file

🧪 Testing
All major modules tested locally on browser

Firebase test data used to validate login, appointment flow, and approval logic

Edge cases like duplicate bookings, blank inputs, and invalid login tested

📦 Future Improvements
Add email notifications via Firebase Functions

Add responsive design for better mobile experience

Calendar integration for appointment slots

📂 Submission Checklist
✅ Code pushed to GitHub

✅ README with system workflow

✅ Logging implemented

✅ Firebase project setup

✅ Project report with design architecture (LLD, wireframe)

🤝 Contribution
This is a Unified Internship #unified project by Anni Shivakumara. Contributions, ideas, and suggestions are welcome via issues or pull requests.

