NAME: ABDIKANI MOHAMED ABDILLE

Exercise A: Explaining the SDLC
The Software Development Life Cycle (SDLC) is a structured process used to develop software from the initial idea to deployment and maintenance. The main phases are:

Planning – Identify the problem, project goals, resources, budget, and timeline.
Requirements Analysis – Gather and document what users and stakeholders need from the software.
Design – Create the system architecture, database structure, user interface, and technical design.
Development – Programmers write the code and build the software.
Testing – The software is tested to find and fix errors and ensure it meets requirements.
Deployment – The completed software is released for users.
Maintenance – The software is monitored, updated, improved, and repaired after release.

Summary:
The response explains SDLC as a structured process for developing software. It identifies seven common phases and explains the purpose of each one. The explanation is simple and covers the entire development process from planning to maintenance.

Prompt 2: Role Prompting

Prompt:

Act as an experienced software engineering instructor teaching first-year university students. Explain the Software Development Life Cycle (SDLC) in simple language. Use clear headings and a numbered list to explain the seven main phases, including the purpose of each phase and one simple example for each phase. Finish with a short summary.

AI Response:

Software Development Life Cycle (SDLC)

The Software Development Life Cycle (SDLC) is a step-by-step process that software teams use to plan, create, test, release, and maintain software.

Planning
The team identifies the problem, goals, budget, resources, and schedule.
Example: A university decides to create an online system for students to book study rooms.
Requirements Analysis
The team finds out what users need the software to do.
Example: Students need to see available rooms and reserve them online.
Design
Developers plan how the software will look and work, including databases and system architecture.
Example: The team designs the booking screen and database for storing reservations.
Development
Programmers write the code and build the system.
Example: Developers create the login, room-search, and booking functions.
Testing
The software is tested to identify errors and make sure requirements are satisfied.
Example: Testers check whether two students can accidentally book the same room at the same time.
Deployment
The finished software is made available to users.
Example: The university launches the booking system for students.
Maintenance
Developers fix problems, provide updates, and improve the software after release.
Example: Developers add notifications when a student's booking is about to begin.
Summary

SDLC provides a structured way to develop reliable software. Each phase has a specific purpose, from understanding the problem to maintaining the finished product. Following these phases helps teams manage resources, reduce errors, and create software that meets users' needs.
:::

Compare

The role-prompting response was more useful because it was designed specifically for first-year university students. I changed the prompt by giving the AI the role of a software engineering instructor, specifying the audience, and requesting headings, numbered phases, examples, and a summary. The role encouraged the AI to explain the topic like a teacher rather than simply giving a general definition. Specifying the audience also made the language simpler and more suitable for beginners.

Exercise B: Software Development Models
Prompt

Act as an experienced software engineering consultant. For each of the following four situations, recommend the most appropriate software development model:

A project with stable, clearly defined requirements.
A startup where requirements change frequently based on user feedback.
A large project with significant technical and security risks.
A project where testing and verification are extremely important.

For each situation, provide:

The recommended development model.
A brief explanation of why it is appropriate.
One limitation of the recommended model.

Present the answer in a clear table followed by a short conclusion.

AI Response:

Situation	Recommended Model	Why It Is Appropriate	One Limitation
Stable, clearly defined requirements	Waterfall Model	Requirements are known in advance, so the project can progress through clearly defined stages such as requirements, design, development, and testing.	Changes later in the project can be expensive and difficult.
Requirements change frequently based on user feedback	Agile Model	Agile uses short development cycles and frequent feedback, making it easier to adapt to changing requirements.	It can be difficult to predict the exact final cost and schedule.
Large project with significant technical and security risks	Spiral Model	Spiral focuses heavily on identifying, analyzing, and reducing risks during repeated development cycles.	It can be expensive and complex to man age.
Testing and verification are extremely important	V-Model	The V-Model emphasizes testing and verification alongside each development stage, making it suitable when quality and verification are critical.	It is less flexible when requirements change frequently.

Conclusion:
The best development model depends on the project's requirements, risks, flexibility, and quality needs. Waterfall works well when requirements are stable, Agile is suitable for changing requirements, Spiral is useful for high-risk projects, and V-Model is appropriate when testing and verification are particularly important.

Reflection

I learned that there is no single software development model that is best for every project. The choice depends on factors such as how stable the requirements are, how much user feedback is expected, the level of technical risk, and how important testing is. For example, Agile is better when requirements change frequently, while Waterfall is more suitable when requirements are clearly defined from the beginning.

Exercise C: Requirements Extraction
Prompt

Act as a business analyst and software requirements engineer. Analyze the following client brief for a local bookstore:

Track books, quantities, and prices.
Manage supplier payments.
Alert staff when stock is low.
Identify best-selling books.
Allow customers to check availability online.
Produce clear records for a part-time assistant.
The owner has a limited budget.

Organize your analysis into these six sections:

Functional requirements.
Non-functional requirements.
Must Have requirements.
Should Have requirements.
Nice to Have requirements.
Questions or ambiguities that need clarification.

Clearly explain each requirement and avoid adding features that are not reasonably supported by the brief. Consider the limited budget when prioritizing the requirements.

AI Response:

1. Functional Requirements
The system must store book information, including titles, quantities, and prices.
The system must allow staff to update book quantities and prices.
The system must record and manage supplier payments.
The system must automatically alert staff when stock reaches a low-stock level.
The system must generate reports showing best-selling books.
Customers must be able to check whether books are available online.
The system must produce clear records that can be used by the part-time assistant.
2. Non-Functional Requirements
Usability: The system should be simple enough for staff and the part-time assistant to use.
Performance: Stock and availability information should load quickly.
Reliability: Records should be stored accurately and remain available when needed.
Security: Supplier payment and business information should only be accessible to authorized users.
Cost: The system should fit within the bookstore's limited budget.
3. Must Have Requirements
Book inventory tracking.
Quantity and price management.
Supplier payment records.
Low-stock alerts.
Basic customer online availability checking.
Clear records for staff.
4. Should Have Requirements
Best-selling book reports.
User access controls.
Simple reporting features.
Automatic backups.
5. Nice to Have Requirements
Mobile application.
Advanced sales analytics.
Automated supplier payment processing.
Customer recommendations.
6. Questions or Ambiguities
What does "low stock" mean? Should the owner set the minimum quantity?
Should supplier payments be recorded only, or should the system make payments?
How frequently should best-selling reports be produced?
Should customers be able to reserve or purchase books online?
Does the bookstore already have a website?
How many books and suppliers need to be managed?
What is the exact budget?
How many staff members will use the system?
Evaluation

Two things the AI did well:

It correctly separated functional requirements from non-functional requirements.
It considered the limited budget and identified important clarification questions.

One thing it missed or categorized incorrectly:
The AI placed automatic backups under "Should Have," but depending on the importance of protecting inventory and payment records, basic data backup could reasonably be considered a Must Have.

One improvement to the prompt:
I would ask the AI to provide a clear reason for why each requirement is classified as Must Have, Should Have, or Nice to Have. This would make the prioritization easier to evaluate.

Exercise D: Prompt Iteration Challenge
Version 1

Prompt:

Create a project plan for a mobile application that allows university students to book campus study rooms.

AI Response:

A project plan for the study-room booking application would include:

Define project requirements.
Design the application.
Develop the application.
Test the application.
Deploy the application.
Maintain and update the application.

The team should identify users, create the booking system, develop the mobile application, test it, launch it, and provide ongoing support.

What is missing?

The prompt does not specify the SDLC phases in detail, time estimates, deliverables, risks, risk mitigation, team roles, or budget. It also does not provide enough information about the application's required features.

Version 2

Prompt:

Create a project plan for a mobile application that allows university students to book campus study rooms.

The application should allow students to:

View available study rooms.
Select a date and time.
Book a room.
Cancel a booking.
Receive booking confirmation.

The system should prevent double-booking and should be simple and easy for university students to use.

Organize the project plan according to the major SDLC phases and explain the main activities in each phase.

What I changed:

I added information about the users and the main features of the application. I also added important system requirements such as preventing double-booking and making the application easy to use.

Why:

The AI now has enough context to create a more realistic project plan instead of producing only a general software development plan.

Version 3

Prompt:

Act as a project manager and software development expert. Create a realistic project plan for a mobile application that allows university students to book campus study rooms.

The application should allow students to:

Create an account and log in.
View available study rooms.
Search rooms by date, time, capacity, and location.
Book and cancel rooms.
Receive booking confirmations and reminders.

The system must prevent double-booking and protect student account and booking information.

Use the seven SDLC phases: planning, requirements analysis, design, development, testing, deployment, and maintenance. For each phase, explain the main activities and expected outcome. Use clear headings and a table where useful.

What I changed:

I added a specific AI role, more detailed application requirements, security requirements, and the seven SDLC phases.

Why:

These changes make the response more structured and technically realistic. They also help the AI understand what should be developed and how the project should be organized.

Version 4: Final Prompt

Final Prompt:

Act as an experienced software project manager and SDLC consultant. Prepare a realistic project plan for a mobile application that allows university students to book campus study rooms.

Application Requirements

The application should allow students to:

Create accounts and log in securely.
View and search available study rooms.
Search by date, time, capacity, and location.
Book and cancel rooms.
Receive booking confirmations and reminders.
Prevent double-booking.
Protect student account and booking information.
Project Plan Requirements

Use all seven SDLC phases:

Planning
Requirements Analysis
System Design
Development
Testing
Deployment
Maintenance

For each phase, provide:

Main activities.
Estimated time.
Key deliverables.
Major risks.
Risk mitigation strategies.

Also include:

Recommended team roles and responsibilities.
A rough budget estimate in Kenyan Shillings (KES).
Key assumptions used for the budget and timeline.
A short overall project timeline.

Present the answer using clear headings and tables. Keep the estimates realistic for a university-level mobile application and clearly state that the budget and timeline are approximate.

AI Response:

Mobile Study-Room Booking Application Project Plan
1. Planning

Estimated time: 1–2 weeks

Activities:

Define project objectives.
Identify stakeholders.
Determine the target student population.
Define the project scope.
Estimate resources and costs.

Deliverables:

Project charter.
Initial scope.
High-level schedule.

Risks:

Unclear project scope.
Insufficient funding.

Risk mitigation:

Agree on project scope before development begins.
Prioritize essential features within the available budget.
2. Requirements Analysis

Estimated time: 2–3 weeks

Activities:

Interview students and university staff.
Document functional and non-functional requirements.
Define booking rules.
Identify security requirements.

Deliverables:

Requirements specification.
User stories.
Acceptance criteria.

Risks:

Missing important user requirements.
Conflicting stakeholder expectations.

Risk mitigation:

Conduct user interviews and reviews.
Obtain stakeholder approval of requirements.
3. System Design

Estimated time: 2–3 weeks

Activities:

Design the mobile user interface.
Design the database.
Design the booking system.
Plan authentication and security.
Design the system architecture.

Deliverables:

UI wireframes.
Database design.
System architecture.
Technical design document.

Risks:

Poor system design.
Security weaknesses.

Risk mitigation:

Review designs before development.
Conduct an early security review.
4. Development

Estimated time: 6–10 weeks

Activities:

Build the mobile application.
Implement user accounts.
Build room search and booking.
Implement cancellation and notifications.
Implement double-booking prevention.
Connect the application to the database.

Deliverables:

Working application.
Source code.
Database.
Initial user documentation.

Risks:

Development delays.
Technical bugs.
Integration problems.

Risk mitigation:

Use version control.
Conduct regular code reviews.
Develop features incrementally.
5. Testing

Estimated time: 3–4 weeks

Activities:

Unit testing.
Integration testing.
System testing.
Security testing.
Usability testing.
User acceptance testing.

Deliverables:

Test plans.
Test results.
Bug reports.
User acceptance approval.

Risks:

Important defects remaining.
Insufficient testing time.

Risk mitigation:

Begin testing during development.
Prioritize critical functions such as booking and authentication.
6. Deployment

Estimated time: 1–2 weeks

Activities:

Configure production infrastructure.
Deploy the backend and database.
Release the mobile application.
Train administrators.
Monitor the initial release.

Deliverables:

Production application.
Deployment documentation.
Administrator training materials.

Risks:

Deployment failure.
Unexpected problems after launch.

Risk mitigation:

Use a staged release.
Maintain backups and a rollback plan.
7. Maintenance

Estimated time: Ongoing

Activities:

Fix bugs.
Monitor performance and security.
Update the application.
Add improvements based on student feedback.

Deliverables:

Updates and patches.
Maintenance reports.
New application versions.

Risks:

Increasing maintenance costs.
Security vulnerabilities.

Risk mitigation:

Schedule regular security updates.
Monitor system performance.
Maintain a prioritized improvement backlog.
Team Roles
Role	Main Responsibility
Project Manager	Planning, scheduling, coordination, and monitoring
Business/System Analyst	Requirements gathering and documentation
UI/UX Designer	User interface and user experience
Mobile Developer	Mobile application development
Backend Developer	APIs, database, and server-side functionality
QA/Test Engineer	Testing and quality assurance
Security/DevOps Support	Security, deployment, and infrastructure
Rough Budget

An approximate university-level project budget could be:

Item	Estimated Cost (KES)
Planning and analysis	50,000
UI/UX design	60,000
Mobile development	250,000
Backend/database development	180,000
Testing	100,000
Deployment/infrastructure	60,000
Initial maintenance	75,000
Estimated total	775,000 KES

The actual cost could vary significantly depending on whether the university uses its own developers, contracts external developers, uses existing infrastructure, or requires additional features.

Overall Timeline

The initial project could take approximately 15–25 weeks, followed by ongoing maintenance.

Final Reflection

Yes, the prompt improved significantly from Version 1 to Version 4. The biggest improvements came from adding specific application requirements, defining the seven SDLC phases, assigning the AI a professional role, and requesting time estimates, deliverables, risks, mitigation strategies, team roles, and a budget. These details made the final response much more specific, practical, and useful for project planning.

Overall Reflection
1. What makes a prompt effective?

An effective prompt is clear, specific, and provides enough context for the AI to understand the task. It can also specify the desired audience, format, role, and expected output.

2. Which prompting technique did you find most useful?

Role prompting was the most useful because assigning the AI a suitable role helped produce a more focused and professional response.

3. Why is context important when working with AI?

Context helps the AI understand the situation, requirements, limitations, and intended audience. Without enough context, the response may be too general or may not address the actual problem.

4. Why should we review AI-generated responses instead of accepting them automatically?

AI can misunderstand requirements, make incorrect assumptions, or provide inaccurate information. Reviewing the response allows users to identify errors and make sure the result meets the project's actual needs.

5. How can AI support software engineers across the SDLC?

AI can help with planning, requirements analysis, system design, coding, testing, documentation, deployment, and maintenance. It can generate ideas, identify possible risks, explain code, create test cases, and help developers troubleshoot problems. However, software engineers should still verify AI-generated work before using it in real projects
