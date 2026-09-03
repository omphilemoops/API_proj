# API_proj
# RaceDay – Part 1

## 1. Project Overview

RaceDay is a web-based event management system designed for running, walking and cycling events. The system allows Organisers to manage events, categories, participant enrolments and results, while Participants can register, browse events, enrol in events and view their results.

Part 1 focuses on planning the system and creating the database structure before developing the RESTful API.

2. Part 1 Objectives

The main objectives of Part 1 are:

Design the database using an Entity Relationship Diagram (ERD).
Plan the RESTful API endpoints.
Create a SQL Server database script.
Identify the different user roles and their responsibilities.
Prepare the project for development in Part 2.

3. User Roles
Organiser

An Organiser is responsible for managing race events.

An Organiser can:

Create events.
Edit events.
Delete events.
Manage event categories.
View participant enrolments.
Capture participant results.
Manage event information.

Participant

A Participant is a user who takes part in events.

A Participant can:

Create an account.
Log in.
Browse available events.
View event information.
Enrol in an event.
Select an event category.
View their enrolments.
View their personal results.

4. Section A – Entity Relationship Diagram
The ERD represents the database structure for the RaceDay system.
The ERD includes the entities, attributes, primary keys, foreign keys and relationships required by the system.
The ERD is included in the /docs folder.

5. Section B – API Endpoint Plan

The API endpoint plan identifies the RESTful endpoints that will be implemented in Part 2.

The endpoint plan includes:

HTTP Method
Route
Description
Role Required
Request Body
Expected Response

The planned API functionality covers:

Authentication
User Profile
Events
Categories
Event Enrolments
Results

The completed endpoint plan is included in the /docs folder.
