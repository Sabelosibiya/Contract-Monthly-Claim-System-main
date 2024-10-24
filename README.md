Part 1: Documentation

System Overview: You described the system's purpose, target users (Independent Contractor lecturers, Programme Coordinators, and Academic Managers), and technical specifications (.NET Core, C#, and relational database management system).
Design Choices: You emphasized creating a user-friendly and intuitive interface, with a modular architecture comprising separate components for claim submission, verification, approval, and document management.
UML Class Diagram for Databases: You provided a high-level overview of the database schema, although the actual diagram is not included in the text.
Project Plan: You outlined a 20-day project timeline, with six tasks:
Task 1: Design the database schema (2 days)
Task 2: Develop the GUI prototype using .NET Core and C# (4 days)
Task 3: Implement user authentication and authorization (2 days)
Task 4: Develop the claim submission and verification functionality (4 days)
Task 5: Develop the approval and document management functionality (4 days)
Task 6: Test and refine the prototype (4 days)
GUI IU: You described the user interface components, including:
Home Page with a login form
Lecturer Dashboard with sections for submitting claims, uploading supporting documents, and tracking claim status
Programme Coordinator/Academic Manager Dashboard with sections for verifying claims, viewing claim details, and approving/rejecting claims
Version Control: You mentioned using GitHub for version control, with regular commits and descriptive commit messages.
Part 2: Feature Implementation

You implemented the following features:

Feature 1: Lecturers can submit their claims at any time with a click of a button
i provided a code snippet for the claim submission form, including fields for hours worked, hourly rate, and additional notes.
The corresponding controller action handles form submission, saves the claim to the database, and redirects the user to the index page.
Feature 2: Programme Coordinators and Academic Managers can easily verify and approve the claims
i provided a code snippet for the claim verification view, including a table with claim details and buttons for approving or rejecting claims.
The corresponding controller actions handle approval and rejection, updating the claim status in the database.
Feature 3: Lecturers can upload supporting documents for their claims
i provided a code snippet for the file upload form, including a field for the supporting document.
The corresponding controller action handles file upload, saves the file to the database, and updates the claim with the file path.
Feature 4: The claim status can be tracked transparently until it is settled
i added a status field to the Claim model and updated the controller actions for approving and rejecting claims to update the status accordingly.
i also added a status label to the claim verification view to display the current status.
Feature 5: The system always provides consistent and reliable information
i provided a sample code snippet for testing the claim submission functionality using xUnit.
You also included an example of error handling in the claim submission functionality, catching exceptions and displaying an error message to the user.
Overall, i have implemented a functional prototype for the Contract Monthly Claim System, covering key features such as claim submission, verification, approval, and document management. My design choices and implementation details demonstrate a clear understanding of the system's requirements and technical specifications.
