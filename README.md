# Project
These all done by my self

# ABC Restaurant Management System

ABC Restaurant Management System is a web-based application developed for managing various operations of a restaurant such as reservations, orders, contact queries, and user management. This system provides different functionalities for admins, staff, and customers.

## Features

User Registration and Login: Users can register and log in to their accounts to make reservations and view orders.
Online Reservations: Customers can make reservations for dining in or delivery.
Order Management: Admins and users can view and manage orders.
Contact Form: Customers can submit queries or feedback via the contact form.
Admin Dashboard: Admins can view and manage reservations, contacts, users, and orders.
Technologies Used

Java: Backend logic is written in Java.
Spring Boot: The project uses Spring Boot for creating a RESTful web application.
JSP (JavaServer Pages): Used for rendering the frontend pages.
MySQL: Database used to store data for users, reservations, orders, etc.
JUnit: Unit testing is performed using JUnit 5.
Maven: Project management and build automation tool.
Installation and Setup

To run this project locally, follow these steps:

Clone the repository: bash git clone https://github.com/jananik124/ABCRestaurant.git

# EHR for Diabetic Care

## Introduction
This project is an Electronic Health Record (EHR) system designed specifically for Sri Lankan National Diabetic care. 
This aims to provide a comprehensive platform for healthcare providers and patients to efficiently manage records and improve the quality of care.
In this system there are main 6 users as Doctor, Patient, Lab-Technician, Pharmacist, Reciptionist and Admin. 

## Features
- Patient Record Management: Allows staff users to create, update, and access patient records securely.
- Diabetic Care Tools: Provides specialized tools and features for managing diabetic care, such as glucose monitoring, medication tracking, and treatment plans.
- User Authentication and Authorization: Implements secure user authentication and role-based access control to ensure data privacy and confidentiality.
- Search and Filter Functionality: Enables users to search and filter patient records based on various criteria, such as demographics, medical history, and treatment status.

## Technologies Used
Backend Development: PHP, JavaScript

Database: SQL

Server: XAMPP

Frontend Framework: CSS, Bootstrap,

## Installation
Clone the repository

Navigate to the project directory and locate "ehr_db.sql" file

Export database (Recommend using phpmyadmin's SQL Server)

Initialize proper connection according to "conn.php"
(File path: ehr-final-project -> Final-Project -> data -> conn.php)

Start from preferred login pages using respective sample credentials given in "Login-Info.txt" file
(File Path: ehr-final-project -> Login-Info.txt)

## Usage
### Admin 
- Create and manage staff user accounts
- Manage dietary and activity recommendations plans
- View system audit trails

### Doctor
- Search for a patient using a Patient Health Number(PHN)
- Color-coded risk visualization
- Enter visit records
- View auto-generated charts according to Vital Signs
- Request lab test
- Place prescriptions

### Receptionist 
- Search for a patient using a Patient Health Number(PHN)
- Register a new patient

### Lab-Technician
- View and search for requested lab tests
- Enter result values
- View past lab tests and results
  
### Pharmacist
- View and search for placed prescriptions
- Confirm a prescription's status
- Manage Inventory
- Change the Unavailiablty of a medicine

## Patient
- View patient details, visit records, prescriptions and lab tests
- Access risk-tailored activity and diet plans

Clone the repository: bash git clone https://github.com/mariyadavid03/diabetic-ehr-final-project.git


# Online Crime Management System (OCMS)

The **Online Crime Management System (OCMS)** is a web-based application designed to simplify the process of reporting and managing crime cases. It enables citizens to report crimes online, track case progress, and request escalations with additional evidence. The system also provides law enforcement with powerful tools for monitoring and resolving cases more efficiently.

## Features

- **Online Crime Reporting** – Citizens can report crimes through a simple digital form.
- **Real-Time Case Tracking** – Users can view the status and progress of their cases.
- **Case Escalation Requests** – Users can request case escalation by submitting extra evidence.
- **Geospatial Crime Mapping** – Authorities can view crime hotspots using GIS maps.
- **Chatbot Support** – AI-powered chatbot helps citizens get instant assistance.
- **Geolocation Alerts** – Detects user location to raise alerts in high-risk areas.
- **Role-Based Access Control** – Admins, officers, and citizens have secured login portals.
- **Multi-Language Support** – Available in Sinhala, Tamil, and English.

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: PHP  
- **Database**: MySQL (phpMyAdmin)  
- **GIS Integration**: QGIS, Google Earth  
- **Security**: Password hashing with bcrypt  
- **Tools**: Visual Studio Code, R, R-Studio (for analysis)

## System Modules

1. **Citizen Module** – Register, login, report crimes, request escalations, and track cases.
2. **Police Module** – View and manage crime reports and escalation requests.
3. **Admin Module** – Dashboard management for system monitoring.
4. **Chatbot Module** – FAQ-based intelligent support.
5. **Crime Mapping Module** – QGIS-based heatmap visualization.

## Installation Guide

1. Clone the repository: https://github.com/jananikodithuwakku/OCMS.git

