[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/pG3gvzt-)
# PCCCS495 – Term II Project

## Project Title

Swing - Student Info App
## Problem Statement (max 150 words)

In many educational institutions, student information is still managed manually or using basic systems that are inefficient, time-consuming, and prone to errors. Tasks such as storing student records, searching for specific data, and maintaining consistency between stored and displayed information often become difficult.

There is a need for a simple, user-friendly, and efficient system that can:

Store student details digitally
Allow quick searching and retrieval of records
Ensure data accuracy and consistency
Provide an interactive graphical interface for better usability

To address these challenges, a Student Information System using Java Swing is developed, which offers an organized, responsive, and easy-to-use platform for managing student data.

## Target User

Education Fields means School Colleges etc
## Core Features

- User-Friendly GUI
- Add Student Records
- Search Functionality
- Data Validation
---

## OOP Concepts Used

Encapsulation: Data (student details) and related methods (save, load, search) are kept together inside classes, ensuring controlled access and better structure.
Abstraction:
Complex operations like file handling and data processing are hidden behind simple methods like handleSave() and loadFromFile().

Modularity: (Separation of Concerns)
The code is divided into different parts such as UI, logic, and data handling, making it easier to manage and debug.

Event-Driven Programming: (OOP Style)
Actions like button clicks are handled using objects (ActionListener), aligning with OOP principles.

Object Creation:
Swing components like JFrame, JButton, JTable are all objects created and managed in the program.

---

## Proposed Architecture Description

The proposed system follows a layered, event-driven GUI architecture using Java Swing. It is designed to ensure smooth interaction between the user interface, application logic, and data storage.

The architecture is divided into the following components:

User Interface (UI Layer)
Built using Swing components like JFrame, JTable, JTextField, and JButton.
It handles user input and displays student data.
Event Handling Layer
Uses ActionListener to capture user actions such as Save, Search, and Clear.
These events trigger the corresponding processing methods.
Application Logic Layer
Contains core methods like handleSave(), loadFromFile(), and search logic.
Responsible for validation, data processing, and decision-making.
Data Model Layer
Managed using DefaultTableModel, which temporarily stores student records during runtime.
Persistence Layer (File Storage)
Data is saved in a file (students.txt) to ensure permanent storage and retrieval.
Architecture Flow

UI → Event → Logic → Model → File → UI Refresh

This flow ensures:

Smooth data handling
Real-time updates
Consistency between UI and stored data

## How to Run
Install Java (JDK)
javac StudentInfoApp.java run in terminal
java StudentInfoApp execute in terminal
or 
simply press RUN button in VSCode
---

## Git Discipline Notes
Minimum 10 meaningful commits required.
