🏋️ **Fitness Center Membership Portal**

A Salesforce-based solution designed to replace manual gym management processes. This project streamlines member registration, class bookings, and payments while providing real-time operational insights for staff and a self-service portal for members.

🚀 Project Overview

Traditional fitness centers often rely on manual or fragmented systems for managing memberships, schedules, and payments.
This project modernizes gym operations by leveraging Salesforce automation and custom development to deliver a scalable and efficient solution.

Key Objectives:

Eliminate manual paperwork and spreadsheets

Automate membership and class booking workflows

Provide real-time dashboards for decision-making

Enable a seamless self-service experience for members

🛠️ Technologies Used

Salesforce Platform

Salesforce Flow – Business process automation

Apex – Backend logic and validations

Lightning Web Components (LWC) – Modern, responsive UI

Salesforce Reports & Dashboards – Analytics and insights

✨ Features
👤 Member Management

Automated member sign-up and profile management

Membership status tracking (Active / Expired / Suspended)

📅 Class Booking System

Browse available fitness classes

Book or cancel classes through the portal

Capacity control and schedule management

💳 Payment Handling

Membership payment tracking

Automated updates on successful or pending payments

📊 Admin Dashboards

Real-time view of active members

Class attendance insights

Revenue and membership trends

🌐 Self-Service Portal

Members can:

Register and manage profiles

Book classes

View membership details

🧩 Architecture Overview
Members (Portal)
     ↓
Lightning Web Components (UI)
     ↓
Salesforce Flow (Automation)
     ↓
Apex Classes (Business Logic)
     ↓
Salesforce Objects & Dashboards

📂 Repository Structure
Fitness-Center-Membership-Portal/
│
├── apex/
│   ├── MemberController.cls
│   ├── BookingController.cls
│
├── lwc/
│   ├── memberRegistration/
│   ├── classBooking/
│   ├── paymentStatus/
│
├── flows/
│   ├── Member_Onboarding.flow
│   ├── Class_Booking.flow
│
├── dashboards/
│   ├── AdminDashboard.dashboard
│
├── docs/
│   ├── Project_Overview.md
│   ├── Data_Model.md
│
└── README.md

⚙️ Setup Instructions

Clone the repository:

git clone https://github.com/your-username/Fitness-Center-Membership-Portal.git


Deploy components using Salesforce CLI:

sfdx force:source:deploy -p force-app


Assign required permission sets to users

Configure Experience Cloud for the member portal

Activate Flows and Dashboards

📈 Future Enhancements

Online payment gateway integration

Mobile-first UI improvements

AI-based class recommendations

Automated reminders via Email/SMS

🤝 Contribution

Contributions are welcome!
Feel free to fork the repository, raise issues, or submit pull requests.
