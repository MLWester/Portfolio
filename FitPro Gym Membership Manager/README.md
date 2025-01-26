# FitPro Gym Membership Management System

## Overview
The FitPro Gym Membership Management System is a web application designed to manage gym memberships efficiently. Built using **ASP.NET Core** and **Entity Framework Core**, it allows administrators to manage members, membership plans, and other related data. This project demonstrates CRUD operations, database management, and responsive design.

## Features
- **Membership Management**: Add, edit, and delete gym members.
- **Membership Plans**: Manage and enforce unique membership plan names.
- **Search and Sorting**: Search members by attributes such as name, email, or phone and sort them by `FirstName` or `JoinDate`.
- **Data Validation**: Ensures data integrity through built-in validation rules.
- **Responsive Design**: Bootstrap-powered UI for a seamless user experience across devices.
- **Database Seeding**: Prepopulates the database with initial data, including 25 members.

## Technologies Used
- **ASP.NET Core**: Backend framework for web application development.
- **Entity Framework Core**: ORM for database operations and migrations.
- **C#**: Programming language used for logic and interaction.
- **SQL Server**: Relational database for data storage.
- **Bootstrap**: Frontend framework for responsive design.
- **Visual Studio Code**: IDE for development and debugging.

## How It Works
1. **Membership Management**:
   - Administrators can add new members, edit member details, and remove inactive members.
   - Membership plans can be updated and deleted while ensuring name uniqueness.

2. **Database**:
   - Uses Entity Framework Core for database management.
   - Seeds the database with 25 initial members and a set of membership plans.

3. **Search and Sorting**:
   - Search bar allows filtering members by name, email, or phone.
   - Sort options include ascending or descending order by `FirstName` or `JoinDate`.

4. **Validation**:
   - Validation rules ensure data correctness (e.g., no duplicate membership plan names).

[FitPro.pdf](https://github.com/user-attachments/files/18548576/FitPro.pdf)
