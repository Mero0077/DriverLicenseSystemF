# 🚗 Driving License Management System 🪪
A full-fledged project built with ADO.NET that simulates a real-world driving license system. This system manages user registration, license types, vehicle categories, driving tests, fines, and much more.

📌 Features 👤 User Management User registration & login

Profile management

Track test results and license status

🪪 License System Multiple license types (e.g., LMV, HMV, Motorcycle, Commercial)

License issuance based on passed driving test

Renewals and expiration tracking

🛻 Vehicle & Driver Types Categorize users based on their license type

Define and manage various vehicle types

Assign vehicle eligibility per license

🧪 Test Management Schedule driving tests

Automatic result recording (pass/fail)

Retake option if failed

Test history tracking per user

💸 Fines & Violations Issue fines to users based on violations

View fine history

Payment tracking and status update

🧑‍💻 Tech Stack 💻 Language: C#

🗃 Database: SQL Server

🔗 Data Access: ADO.NET

🧱 Architecture: 3-tier (UI, BLL, DAL)

🗂 Project Structure cpp Copy Edit 📁 DrivingLicenseSystem ├── 📁 DAL // Data Access Layer (ADO.NET) │ └── SqlHelper.cs, LicenseDAL.cs, UserDAL.cs ... ├── 📁 BLL // Business Logic Layer │ └── LicenseManager.cs, TestManager.cs ... ├── 📁 UI // Presentation Layer (WinForms or ASP.NET) │ └── LoginForm.cs, Dashboard.aspx ... └── 📄 README.md 🚦 Workflow Overview User Registration/Login

Choose License Type & Apply

Schedule Driving Test

System Records Result (Pass/Fail)

License Issued Upon Pass ✅

Retake if Failed ❌

Fines Imposed for Violations

User Can View and Pay Fines

🛠 How to Run Clone the repository

Set up the SQL Server database using the provided scripts

Update the connection string in app.config or web.config

Build and run the project using Visual Studio

📊 Database Schema Highlights Users: Stores user information

Licenses: Stores license details

Tests: Tracks driving test results

Vehicles: Vehicle types and mapping

Fines: Fine records with payment status

📌 Example Use Cases 👨‍🎓 A user registers and applies for a motorcycle license.

🚦 They take the test but fail — the system allows rescheduling.

✅ Upon passing, the license is issued and stored.

🛑 The user commits a violation — a fine is issued.

💳 The user logs in, sees the fine, and pays it.	
