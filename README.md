# VulZero

## Overview
VulZero is a platform designed to streamline the reporting and handling of security vulnerabilities in software systems. It offers a collaborative environment for hackers, companies, and internal teams to work together efficiently in identifying, reporting, and resolving security issues.

## Key Features
- **User Registration**: Register with different roles such as Hacker, Company, Internal Team, or Manager.
- **Secure Authentication**: Log in securely using your registered credentials.
- **Vulnerability Reporting**: Submit detailed reports on identified security vulnerabilities.
- **Efficient Management**: Managers can oversee and manage disclosed vulnerability reports effectively.
- **Scoring Mechanism**: Hackers earn points based on the severity of reported vulnerabilities.
- **Leaderboard**: Check your ranking among other hackers based on earned points.
- **Program Management**: Companies can create and manage their vulnerability disclosure programs.

## Technologies Utilized
- **Java**: Primary programming language for backend development.
- **SQLite**: Lightweight relational database for efficient data storage.
- **JDBC**: Java Database Connectivity for seamless interaction with the SQLite database.
- **Apache Commons Codec**: Library for secure password hashing.

## Getting Started
1. Clone the repository to your local machine.
2. Ensure Java and Maven are installed on your system.
3. Set up the SQLite database by executing the provided SQL scripts (`create_tables.sql`).
4. Configure the database connection in `DatabaseService.java`.
6. Run the application: `java -jar VulZero.jar`.

## Usage Guide
1. Register with your desired role.
2. Log in securely with your registered credentials.
3. Submit vulnerability reports or manage reports if you're a manager.
4. Earn points based on the severity of reported vulnerabilities.
5. Monitor your ranking on the leaderboard.
