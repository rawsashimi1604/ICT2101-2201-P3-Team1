# ICT2101-2201-Team1 - Train Operations Management System

## Team Member Roles

| Member    | Role(s) 	|
| ---------- | ------------------------- |
| Christabelle    | Team Lead/Full Stack Developer |
| Gavin    | Tech Lead(Architect)/Full Stack Developer |
| Yong Chong    | Front End Developer/UI&UX Designerr |
| Irfaan    | Back End Developer/QA Engineer |

## Introduction
### Scope
The scope of this project is a web application that supports the company’s operational system for train services. Managers will be able to have an overview of the company’s manpower strength and allocate work. Staff will be able to view their job assignment information and inform managers of their availability.
<br/>
<br/>
The system will be based on a relational database with work management and staff management functions. We will have a database server supporting all managers and staff and a user-friendly interface.

### Background
In the train operation division of a train company, work allocation is assigned weekly every Monday. The workload allocation planning will start every Thursday of the week. Hence, all employee’s availability must be informed in the system every Wednesday to be considered in the planning. If employees miss the weekly deadline, requests would be dealt with on a case-by-case basis. The weekly roster is dependent on the length of the train and route. Currently, the company runs five Pendolino trains (https://en.wikipedia.org/wiki/Pendolino) between Singapore and Kuala Lumpur. The route takes approximately 4 hours one way. There are eight stops along the way, and the service normally will stop for about 10 minutes at each station. There should always be at least an engine driver at the locomotive throughout the journey. Onboard the train for all services, there should be one train conductor. One assistant conductor and a cleaner will also be assigned for every two passenger carriages. Typically, the train would have anywhere between seven to thirteen passenger carriages. The manager will make their assignments such that staff should not need to travel between routes and trains should not stay stationary for more than three hours. The service runs every two hours bidirectional from either end daily. The first train starts at 5.30 am, and the last train is at 9.30 pm. By law, the engine driver can only operate the locomotive for a maximum of two hours at one time. Hence, the manager will need to consider this when allocating their work assignments.

## Frameworks
| Application    | Framework(s) 	|
| ---------- | ------------------------- |
| Frontend application   | React.js / Next.js	|
| Backend application    | Express.js	|
| Database management system   | PostgreSQL	|

## System Architecture Diagram

## Use Case Model

## Requirements 
### UI Requirements
- Login Screen
- Employee:
	- Landing page that shows his current job assignments, working hours, engaged assignments/ upcoming assignments
	- Page to Inform system of availalbities (for upcoming roster), they can indicate up to 1 month earlier
	- Page to inform manager that you cmi (for engaged/existing roster)
- Manager:
	- Landing page that visualize manpower availability up to 1 month earlier
	- Job assignment page for employees (upcoming and engaged roster)
	- Employee workload and availability (status)

### Functional Requirements
- The system should allow users to log into their account by entering their username and password.
- The system should allow users to log out of their account.
- The manager should be able to view all staff’s current workload on the landing page.
- The manager should be able to view the total manpower on the landing page.
- The manager should be able to view the top three staff with the lowest workload on the landing page.
- The manager should be able to view the workload assigned, staff’s preferred time slot, staff’s location, and availability for the week in the staff availability table on the job allocation page.
- The manager should be able to sort staff by the amount of workload assigned in the staff availability table on the job allocation page.
- The manager should be able to view staff exceeding 40 hours of work highlighted in red in the staff availability table on the job allocation page.
- The manager should be able to allocate jobs to staff for one week at a time in the staff availability table on the job allocation page.
- The manager should be able to add new staff to the system.
- Staff should be able to view their weekly job assignments on their landing page.
- Staff should be able to view their overall workload for the month on their landing page.
- Staff should be able to indicate their work availability up to 1 month in advance of the job on the calendar page.
- Staff should be able to edit their work availability from the following Thursday up to one month on the calendar page.
- Staff should be able to reject the jobs assigned to them by the manager on the calendar page.

### Non Functional Requirements
- The system shall be based in the form of a web application. It will consist of a frontend application to display and input data for the user, and a backend application to process it. The two applications will connect to each other using REST service calls.
- The manager should take no more than 2 hours to complete job allocation for the week.
#### Performance Requirements
- A REST service call must respond within 3 seconds.
- The system should be able to support up to 100 concurrent users.
- The system should be available for end users 95% of the time.

#### Safety and Security Requirements
- After 3 unsuccessful login attempts, the system will lock an account to protect a user's information from potential hackers.
- All Personally Identifiable Information (PII) will be encrypted.
- The system shall be secured using HTTPS protocol with an SSL certificate.
- The application should not store hard coded sensitive information.

#### Other requirements
- The system should be accessible from Google Chrome, Mozilla Firefox, Microsoft Edge, Brave and Safari.
- The system should be responsive, catering to any devices with any resolution.
- The system shall meet the Web Content Accessibility Guidelines WCAG 2.1.
- Username should not be NRIC due to PDPA.