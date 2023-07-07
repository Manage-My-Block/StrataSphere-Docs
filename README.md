# Quentin McKay & Matt Garrow - T3A2-A - Full Stack App (Part A)

## R1 - APP DESCRIPTION
### Purpose

This app is a building management tool that allows Owners Corporation Managers, Owners Committee Members, and Building Members to stay on top of everything happening in their building.

The current problem is that many buildings are managed in an informal way, with committee members messaging and emailing individually with little transparency, while the owners corporation management are unable to collate all the information about the building, as well as lacking their own communication and responsibility transparency. While there exists some forms of management software (such as Trello), these are unequiped for managing a building that needs to conform to state building management codes as well as maintaining building security. This app aims to tackle these issues.

### Functionality & Features

#### Features:
- Public notice board with comments
- Ticket board (similar to todo items)
- Voting mechanism within Tickets
- Meeting scheduler
- Budget tracker
- Authentication and authorisation

#### Functionality
- Admin roles can CRUD users/tickets/posts/votes/meetings/contacts/budget
- Committee member roles can CRUD tickets/posts/comments
- Building member roles can CRUD their own posts/comments

### Target Audience

This is an enterprise-facing application. The application will be provided for internal use by a Owners Corporation Management company that can then allow access to building members. The target audience will be the owners corp management and the owners/occupants of a building, with many buildings being potentially managed with the application.

### Tech Stack

This is a MERN application:
- MongoDB: This is the database.
- ExpressJS: This is the server framework that manages the back-end of the application.
- React: This is the front-end framework for building the client-facing views.
- Node: This is the javascript runtime environment that creates the server that ExpressJS runs on.

---

## R2 - DATAFLOW DIAGRAM
[Provides dataflow diagram(s) that strictly follow the standard convensions to clearly identify the processes within your application. Clearly depicts where data is coming from, where it is going and how it is being stored.]

Dataflow Diagram
-- TODO --

---

## R3 - APPLICATION ARCHITECTURE DIAGRAM
[Shows almost flawless understanding of the high level structure of the app]

Application Architecture Diagram
-- TODO --

---

## R4 - USER STORIES
[Provides multiple user stories that use ‘persona, what and why’ that outline meaningful features of project. Shows evidence of user story revision and refinement.]

The app will have 3 types of user:
- **Owners Corporation Manager**: This is an 'admin' role, they can CRUD users/tickets/notice board posts/meetings. They can also create data in the app such as adding contact information for services (plumber, elevator, electricians, etc), adding apartment numbers (to assign to users), approving the Owners Committee members, updating the budget balance. They can call votes, approve votes, and add minutes to meetings.
- **Owners Committee Members**: Owners Committee Members have all the abilities of a standard *Building Member* but can also cast votes when the Owners Corporation Manager calls a vote and CRUD tickets/notice board posts.
- **Building Member**: This is the standard role in the app. They can CRUD their own notice board posts and comment on posts. They can only read information about committee members, the owners corporation manager, other building members, services contact info, and tickets. They cannot create tickets, that needs to be done by a Owners Committee Member.


### Owners Corporation Manager User Stories
- "As an Owners Corporation Manager, I want to only allow approved building occupants to access the application, so that we can maintain building security."

- "As an Owners Corporation Manager, I want to be able to CRUD users, so I can make sure the users are approved occupants of the building with the correct contact information."

- "As an Owners Corporation Manager, I want to be able to schedule a meeting with the Owners Committee, so that we can discuss tickets and provide feedback"

- "As an Owners Corporation Manager, I want the ability to call a vote on tickets and approve the vote, so that there is input from the Owners Committee members that is officially recorded."

- "As an Owners Corporation Manager, I want to be able comment on tickets, so that I can provide additional information for committee members and show how the work is progressing."

- "As an Owners Corporation Manager, I want the finalise and close tickets, so that I can show the progress being made and keep the tickets log organised."

- "As an Owners Corporation Manager, I want to be able to moderate the notice board, so that I can keep it organised and remove unwanted posts."

- "As an Owners Corporation Manager, I want to be able to add contact information, so that building occupants can easily access emergency contacts to manage tickets."

- "As an Owners Corporation Manager, I want to be able to approve Owners Committee members, so I can update the roster after each Annual General Meeting."

- "As an Owners Corporation Manager, I want to be able to update the budget, so that I can inform the occupants how much money we have remaining in the budget."

### Owners Committee Member User Stories

- "As an Owners Committee Member, I want to be able to CRUD tickets for issues in the building, so that I can inform the owners corporation management of repairs/problems."

- "As an Owners Committee Member, I want to be able comment on tickets, so that I can provide additional information for other committee members and owners corp management."

- "As an Owners Committee Member, I want to be able to CRUD posts on the notice board, so that I can have discussions with other building members about topical issues in the building."

- "As an Owners Committee Member, I want to be able to cast votes on tickets, so that I can perform my task as a committee member and approve of any works that need to be done."




User Stories
-- TODO --

---

## R5 - WIREFRAMES
[Provides wireframes that show exceptional planning of project flow and structure including but not limited to space distribution, content prioritisation, intended actions, functions, relationships between screens.]

Wireframes for multiple standard screen sizes, created using industry standard software
-- TODO --

---

## R6 - PLANNING METHODOLOGY
[Simple and clear standards for planning methodology chosen and adhered to]  

Tasks are organised using [Trello](https://trello.com/b/L4fMRj3x/term-3-full-stack-project).

For our planning methodology we went with a simplified version of Kanban, while adhering to Agile procedures such as sprints, reviews and definition-of-done. At the start of each sprint we create the tasks, which are broken down into 'cards' and placed in the 'Current Sprint' bin. We then assign the tasks to each team member. Tasks move from left to right as they are completed. We also used a 'blocked' bin, which helps signal when a person is waiting on another piece of work to complete their task.

We used a colour-code system to visually see how long each task is estimated to take. We have estimates from 1 hour to 1 week. We try to limit the cards to a max of 2 days though some cards, like the wireframes, were estimated to take over a week. At the end of each sprint we review the estimates and update expectations based on improved effeciency.

<p align="center">
  <img src="./docs/trello_screenshots/colour-coding.png" />
</p>


Rubric items were also added to the Trello so we can track how the assignment is progressing and to have 'definition of done' for our sprints/cards.

<p align="center">
  <img src="./docs/trello_screenshots/rubric-items.png" />
</p>



July 5: NEEDS INITIAL IMAGES

July 6:
<p align="center">
  <img src="./docs/trello_screenshots/July%206_1.png" />
</p>

<p align="center">
  <img src="./docs/trello_screenshots/July%206_2.png" />
</p>

<p align="center">
  <img src="./docs/trello_screenshots/July%206_3.png" />
</p>

July 7

Matt split his tasks into more manageable cards to maintain a 2-4 hour window for tasks. This kept him more focused and on track, plus it had the added benefit of visualising the burn-down.

<p align="center">
  <img src="./docs/trello_screenshots/July%207_1.png" />
</p>
