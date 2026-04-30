SE2020 – Web and Mobile Technologies

Faculty of Computing

SLIIT

Lab Test

2 Hours

Item Manager MERN Application Enhancement and Deployment

1. Lab Test Overview

You are provided with a starter MERN Item Manager project containing separate frontend and backend applications.

Your task is to complete the given project, extend it by adding a new field called Availability Status, test it locally

using your own MongoDB connection string, publish the source code to a public GitHub repository, and deploy the

frontend and backend separately using free hosting platforms.

2. Expected Skills Demonstrated

•  Understanding and completing an existing MERN project structure.

•  Updating both frontend and backend to support a new data field.

•  Testing the system locally using MongoDB Atlas or an equivalent MongoDB connection.

•  Using Git and GitHub to publish the full project in a public repository.

•  Deploying frontend and backend separately and connecting the live frontend to the live backend.

3. Resources Provided

•  Frontend project of the Item Manager application.

•  Backend project of the Item Manager application.

•  Basic CRUD functionality already included in the starter project.

•  You are expected to complete, test, and deploy the provided codebase during the lab test.

Item Manager Lab Test – 2 Hour Practical

4. Tasks to Be Completed

Task 01 – Project setup and local verification

• Extract the provided Item Manager project (Frontend & Backend).

Backend Setup

• Open the backend project in a terminal or VS Code.

• Install required dependencies:

npm install

• Configure the environment variables:

•  Add your MongoDB Connection URL in the .env file

•  Example:

MONGO_URI=your_mongodb_connection_string

PORT=5000

• Start the backend server:

npm run dev

• Ensure the backend runs without errors.

Frontend Setup

• Open the frontend project in a new terminal or VS Code.

• Install dependencies:

npm install

• Start the frontend application:

npm run dev

Item Manager Lab Test – 2 Hour Practical

Verification

• Open the application in your browser (http://localhost:5173).

• Verify the following:

•  Application loads successfully

•  You can navigate between pages

•  Existing features (Add Item / View Items) are working

•  Capture screenshots of the local running existing system.

Task 02 – Functional enhancement

•  Modify the application by adding a new field named Availability Status to the Add Item form.

•  Update the relevant frontend component(s) to collect this value from the user.

•  Update the backend model, controller logic, and API flow as needed so the value is saved correctly.

•  Ensure that the Availability Status value is shown on the Home page together with the other item

details.

•  Make sure the new field behaves correctly during add, read, and any related update operations.

•  Capture screenshots of the local running updated system as instructed in the submission section.

Task 03 – GitHub publication

•  Create a new public GitHub repository using your own GitHub account (Use your SLIIT GitHub account.

If there are any issues, you may use your personal GitHub account.)

•  You may choose ONE of the following approaches:

•  Option 01: Use a single repository containing both frontend and backend

•  Option 02: Use two separate repositories (one for frontend and one for backend)

•  Push the complete project to GitHub after testing locally

•  Ensure:

•  The repository structure is clean and well organized

•  Both frontend and backend codes are clearly separated (if using a single repository)

•      The GitHub repository/repositories must be created before starting deployment

Item Manager Lab Test – 2 Hour Practical

Task 04 – Separate deployment

•  Deploy the backend to a free hosting platform such as Railway, Render or another equivalent service.

•  Deploy the frontend to a free hosting platform such as Netlify, Vercel or another equivalent service.

•  Update the frontend configuration so that it communicates with the deployed backend URL.

•  Verify that the live system works successfully after deployment.

5. Required Contents of the Submission Word Document

Your submitted Word document must include all of the following items clearly and in order:

•  Student Name

•  Student ID

•  GitHub Repository Links

•  Screenshot of the locally running existing project Add Item page

•  Screenshot of the locally running existing project Home page

•  Screenshot of the locally running updated project Add Item page

•  Screenshot of the locally running updated project Home page

•  Frontend Live URL

•  Backend Live URL

•  Brief deployment notes including the platforms used

6. Marking Scheme (100 Marks)

Component

Description

Marks

Comments for Students

Correctly configures the

Local setup and

connection URL and

MongoDB configuration

verifies the project locally

10

System should run

without major local errors.

New field integration

before deployment.

Adds the new field to the

form and updates the

relevant frontend and

backend logic correctly.

This is the main

20

development task in the

lab test.

Home page display and

application behavior

New field is shown

properly on the Home

10

Visible evidence must

match the

Item Manager Lab Test – 2 Hour Practical

Component

Description

Marks

Comments for Students

page and the overall flow

works correctly.

Creates a public

GitHub repository

repository and pushes the

management

complete project in a clear

structure.

Deploys the backend

Repository must be

10

accessible to the

examiner.

Backend deployment

successfully and provides

20

a valid live backend URL.

Deploys the frontend

Backend should support

the required live requests.

Frontend deployment and

successfully and connects

integration

it to the live backend

25

Live application should

function end to end.

correctly.

Submission document

quality

Includes all requested

details, screenshots, and

5

deployment notes clearly.

Missing evidence will

reduce marks.

7. Important Rules

•  This is an individual lab test.

•  Use only your own GitHub account and your own deployment accounts.

•  Do not remove existing core functionality from the provided starter project.

•  Do not submit broken, inaccessible, or private links.

•  Make sure screenshots are readable inside the submission document.

Item Manager Lab Test – 2 Hour Practical
