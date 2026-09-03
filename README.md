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

6. Section C – SQL Database Script

The SQL script is used to create and populate the RaceDay database using SQL Server Management Studio (SSMS).

The SQL script includes:

Database creation.
Table creation.
Primary keys.
Foreign keys.
Relationships.
Required sample data.

The database structure in the SQL script is designed to match the ERD.

7. Folder Structure
RaceDay
│
|
│   ├── RaceDay_ERD.png
│   ├── RaceDay_API_Endpoint_Plan.pdf
│   └── RaceDay_Database.sql
│
└── README.md

8. Technologies Used

The technologies planned for the RaceDay project include:

C#
ASP.NET Core Web API
SQL Server
SQL Server Management Studio (SSMS)
GitHub
GitHub Actions

9. Part 1 Status

Part 1 planning consists of:

Entity Relationship Diagram (ERD)
API Endpoint Plan
SQL Database Script

These documents provide the foundation for developing the RESTful API in Part 2.

 Future Development

In Part 2, the planned system will be developed into a working ASP.NET Core RESTful API.

The API will include:

Database connectivity.
Authentication.
Organiser and Participant roles.
Event management.
Category management.
Event enrolments.
Results management.
Swagger documentation.
Unit testing.
GitHub Actions CI/CD.

 RESTful API Design

The RaceDay system will use a RESTful API in Part 2.

The API will use standard HTTP methods, including:

GET – Retrieve information.
POST – Create new information.
PUT – Update existing information.
DELETE – Remove information.

The API routes will follow a consistent structure beginning with /api/.

Example:

GET /api/events
POST /api/events
PUT /api/events/1
DELETE /api/events/1

Authentication and Authorisation

The system will support user registration and login.

Authentication will be used to identify users.

Authorisation will be used to determine what functionality each user is allowed to access.

The two roles are:

Organiser
Participant

Organisers will have access to event management and result management functionality.

Participants will have access to event browsing, enrolment and personal result functionality.

Testing

Testing will be implemented during Part 2.

Unit tests will be used to verify that the API behaves correctly.

Testing will include both:

Successful requests.
Unsuccessful requests.

Testing will cover areas such as:

User registration.
User login.
Event management.
Role-based access.
Event enrolments.

The tests will also be executed through the GitHub Actions CI/CD workflow

Swagger

Swagger will be used in Part 2 to document and test the API.

Swagger will allow the implemented endpoints to be viewed and tested directly through a web browser.

Each endpoint will provide information about:

The HTTP method.
The route.
The request.
The response.
Possible errors.

Continuous Integration and Continuous Deployment

GitHub Actions will be used to automate the project build and testing process.

The CI/CD workflow will:

Build the project.
Run the unit tests.
Check whether the tests pass.
Display the workflow result on GitHub.

A successful workflow will be shown with a green check mark.

Setup Instructions
Requirements

The following software is required to work with the project:

Visual Studio.
.NET SDK.
SQL Server.
SQL Server Management Studio (SSMS).
Git.
GitHub account.
Database Setup
Open SQL Server Management Studio.
Open RaceDay_Database.sql.
Execute the SQL script.
Confirm that the RaceDay database and tables were created successfully.
Project Setup
Clone the GitHub repository.
Open the project in Visual Studio.
Ensure that the required .NET SDK is installed.
Configure the database connection.
Build the project.
Run the application.
