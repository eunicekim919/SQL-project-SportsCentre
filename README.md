# SQL-project-SportCentre
A full SQL database application for managing sports centers. This system streamlines management processes and features a GUI for intuitive data visualization and user interaction.

https://www.students.cs.ubc.ca/~jung/selecttest.php

## Overview
This project implements a comprehensive SQL database application designed to manage a sports center's operations. It includes a structured schema for handling members, reservations, facilities, and employees, along with a GUI for user-friendly data visualization and interaction. The focus of the system includes:

* Managing offered services such as equipment rentals, coaching sessions, and employee management.

* Providing functionality for users to check availability and make reservations easily.

## Features
* Member Management: Track member details, including their personal information and family members.
* Facility Management: Manage various facilities like ice rinks, tennis courts, and swimming pools.
* Reservations: Maintain reservation records and schedule activities under each facilities and members.
* Employee Roles: Organize staff by roles, such as instructors, receptionists, and janitors.
* Equipment Tracking: Manage and monitor equipment usage.

## Database Schema

Logical Design including Relational Schema, SQL DDL, and Normalization

Member: Tracks member details, including ID, name, address, phone number, and email.

FamilyMemberAddedTo: Links family members to primary members.

SportsCenter: Records details about sports center locations.

Facility: Represents different facilities within a sports center.

Reservation: Stores reservation details for members.

Employee: Tracks employee details, including their roles and assignments.

Rents: Manages the rental of facilities by members.

HasEquipment: Tracks equipment assigned to various facilities.

## Application Technology Stack 

The technology stack for this project includes:

Database RDBMS: Oracle

Frontend: HTML, CSS

Backend: PHP

## Installation and Setup

1. Clone the repository:

`git clone https://github.com/eunicekim919/SQL-project-SportsCentre.git`

2. Import the provided `test.sql` file to create the Oracel database

3. Update the database connection settings in the PHP configuration file.

4. Run the application using a php server and access the application through the browser. 


## Usage

* User Registration: Users can sign up by providing their personal and contact information.

* Check Availability: Users can view the availability of facilities and equipment in real-time.

* Make Reservations: : Users can create and modify reservations for facilities or equipment as needed. 

* Employees Management: Assign roles and track staff information.
  
* Manage Data: Update personal details, view reservation history, and equipment data.
  

## Future Improvements

* Enhanced application: Develop a more interactive and visually appealing interface.

* Advanced Reporting: Add features for generating detailed payments.


