# Software Requirements Specification (SRS) for Library Management System

## Overview

This repository contains the Software Requirements Specification (SRS) for the Library Management System (LMS). The SRS document provides a detailed description of the system's functionalities, constraints, and interactions, serving as a blueprint for developers, testers, and stakeholders involved in the project.

## Purpose

The primary objective of this SRS is to:

* Define the functional and non-functional requirements of the LMS.
* Establish a clear understanding between stakeholders and developers.
* Serve as a foundation for system design, development, and testing.

## Scope

The LMS is designed to:

* Manage book inventory, including adding, updating, and deleting book records.
* Facilitate user registration and authentication for both librarians and members.
* Support book issuance and return processes.
* Maintain records of fines and dues.
* Provide search functionalities for books and members.
* Generate reports for administrative purposes.

## Functional Requirements

Key functionalities of the LMS include:

* **User Management**: Registration, login, and profile management for librarians and members.
* **Book Management**: CRUD operations for books, including categorization and availability status.
* **Issue/Return Management**: Processes for issuing and returning books, with due dates and fine calculations.
* **Search Functionality**: Search books by title, author, category, and ISBN.
* **Reporting**: Generation of reports such as overdue books, fine collection, and member activity.

## Non-Functional Requirements

The system should:

* Be accessible via web browsers.
* Ensure data security and privacy.
* Provide a user-friendly interface.
* Be scalable to accommodate future enhancements.
* Offer multilingual support.

## System Architecture

The LMS will be developed using a client-server architecture:

* **Frontend**: Web-based interface developed using HTML, CSS, and JavaScript.
* **Backend**: Server-side logic implemented using PHP or Python.
* **Database**: Relational database (e.g., MySQL) for data storage.

## Assumptions and Dependencies

* Users have access to a stable internet connection.
* The system will be deployed on a Linux-based server.
* Necessary hardware resources are available for deployment.

## Glossary

* **Librarian**: A user role responsible for managing the library's operations.
* **Member**: A user role that can borrow books and access library resources.
* **CRUD**: Create, Read, Update, Delete operations.

## References

* IEEE Std 830-1998: IEEE Recommended Practice for Software Requirements Specifications.
* [GitHub Repository](https://github.com/anum-349/Software-Requirement-Specification-of-Library-Management-System)

---

For detailed information, please refer to the full SRS document available in this repository.
