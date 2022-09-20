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

### Non Functional Requirements

