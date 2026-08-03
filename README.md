# Inter-College Competition Database Management System

A relational database management system built using SQL to manage inter-college competitions, including organizers, sponsors, participants, teams, judges, registrations, and competition results.

## Overview

This project demonstrates the design and implementation of a normalized relational database for managing inter-college competitions. The database supports participant registration, team formation, sponsorship management, judging assignments, competition organization, and winner tracking.

The project includes:

- Database schema design
- Entity Relationship (ER) Model
- Relational Schema
- SQL table creation
- Sample data insertion
- Analytical SQL queries

---

## Features

- Manage competitions and organizers
- Store participant and college information
- Register teams for competitions
- Assign judges to competitions
- Track sponsors and sponsorships
- Record winners and prize money
- Execute analytical SQL queries for reporting

---

## Database Schema

The database consists of the following tables:

- Organizer
- Competition
- Sponsor
- Sponsorships
- Judge_List
- Judges
- College
- Participants
- Teams
- Make_Team
- Registers
- Winners

---

## Entity Relationships

- One Organizer → Many Competitions
- One College → Many Participants
- One Competition → Many Registrations
- Many Teams ↔ Many Participants
- Many Competitions ↔ Many Judges
- Many Competitions ↔ Many Sponsors
- Many Teams ↔ Many Competitions

---

## Technologies Used

- PostgreSQL
- SQL
- Relational Database Design
- ER Modelling
- Normalization

---

## Project Structure
├── README.md
├── Code.sql
├── ER_Model.png
├── Relational_Schema.png
└── Project_Report.pdf



---

## SQL Operations

### Schema Creation

- CREATE TABLE
- Primary Keys
- Foreign Keys
- Constraints

### Data Manipulation

- INSERT

### Query Operations

- SELECT
- INNER JOIN
- LEFT JOIN
- GROUP BY
- Aggregate Functions
- Nested Queries

---

## Sample Queries

- Find judges not assigned to any competition.
- Find winners of a competition.
- List registered teams.
- Count participants from a college.
- Find competitions in a particular city.
- Calculate sponsorship received by each competition.
- List teams not registered for any competition.

---

## Learning Outcomes

- Relational database design
- Entity Relationship modelling
- Normalization
- SQL joins
- Aggregate functions
- Foreign key constraints
- Query optimization fundamentals

---

## Future Improvements

- Web-based interface
- Authentication and authorization
- Online registration portal
- Competition scheduling module
- Automated leaderboard generation
- Dashboard and analytics
- Stored procedures and triggers

---

## Authors

- Linesh Malkam
- Ritik Raj Yadav
