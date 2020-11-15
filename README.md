# Interview Preparation
- **S - Situation**
- **T - Task**
- **A - Action**
- **R - Result**

## Agile, Scrum and general methodologies
### What is Agile?
Agile is an iterative methodology that allows for rapid delivery
of increments throughout development of a product. The 4 key values:
1. **Individuals and Interactions over Process and Tools** - Promotes team work
2. **Working software over comprehensive documentation** - Focus is put on
building rather than writing documents. Aided with epics and user stories
3. **Customer collaboration over contract negotiation** - Customer feedback
helps in delivering a successful product
4. **Responding to change over following a plan** - Adaptability helps
in delivering a product
- **Example** - Weekly sprints covering small topics which all contribute to 
the DevOps course

### What is Scrum? Ceremonies
Scrum is a **framework** used to implement an agile methodology, it helps teams work 
together and encourages them to learn through experiences, self-organise while 
working on a problem, and reflect on their wins and losses to continously improve.
Scrum is very similar to Agile, it is based on continous learning and adjustment to 
fluctuating factors.

**Ceremonies:**

Ceremonies are designed to heavily reflect the values of Agile promoting collaboration
within the team and to have a clearly defined process to follow. 
1. **Organise the backlog** - An ordered and dynamic list of everything that is to be completed
during the project overseen by the product owner. 
2. **Sprint planning** - Meeting to understand what is to be done in this sprint by everyone. 
Led by scrum master and a sprint goal is created. User stories created and team knows what
is expected - usually two days of work.
3. **Sprint** - Typically 2 weeks, actual period when the scrum team works together to finish an
increment.
4. **Daily Scrum or Stand-up** - Daily **super-short** meeting 15 mins usually. Goal is for 
everyone on the team to be on the same page aligned with the sprint goal. A time to voice
any concerns or change things up. 
5. **Sprint Review** - At the end of each sprint team gets together to inspect what has been done. 
Everything is showcased to stakeholders if they attend. Aim is to gain feedback and determine
whether everything was done to satisfactory standard or to change things up. Backlog can change
6. **Sprint Retrospective** - Team comes together at end of sprint 90 mins, and allows them to evaluate
what worked and what didnt work in the sprint.  The idea is for the team to focus on what went well, and 
what needs to be improved for the next time and less about what went wrong. 

### Scrum roles, artifacts and events
**Roles:**
1. **Product Owner** - Represent customers and stakeholders. They are focused on understanding
business and customer needs then prioritising work to be done by the team. They build and 
manage the product backlog, give the team guidance and decide when to ship the product
2. **Scrum master** - Leaders of the Scrum, they coach teams, product owners and look for ways
to fine-tune their practice of scrum. They make sure the scrum is understood by EVERYONE
and they give people responsibility of sprint planning/stand-up/retrospective/review.
3. **Development Team** - Usually 5-7 members or small enough to share 2 pizzas! Self-organising
team responsible for delivering the products and fulfill each sprint etc while working together. 
They decide how long each iteration will take.

**Artifacts**

Enable the team and stakeholders to understand the development process and identify
what will be done, and what was completed.:
1. **Product Backlog** - Master list of work that needs completing. The list is constantly
evolving due changing customer requirements or stakeholder needs. The team "TO DO" list.
2. **Sprint Backlog** - Everything that needs doing in a current sprint. Can evolve during the
sprint however the fundamental sprint goal cannot be compromised. List of items, user stories etc.
3. **Increment or Sprint Goal** - Where the sum of everything that was done during the 
sprint is showcased. It must meet Definition of Done "DoD" which is a predefined criteria 
for a successfully finished product. It is the decision of the team on whether to release
their product or work on it further after this point. 

**Example of SCRUM/Agile**
- Throughout the DevOps course we implemented Agile and Scrum values in order to finish
projects. Everyday we would have morning stand-ups where we discussed what topics/projects
will need to be completed by the end of the day and what is expected of us. Trello was
a key tool which showcased the sprint backlog for the course and outlined what needs doing
for every task we were set. 

### Difference between Agile & Scrum
Agile is a methodology whilst Scrum is a framework. Scrum is used to implement agile. There
are other potential frameworks that can implement agile such as Kanban. Agile if more of an
idea of how to work, Scrum is a method of implementing that idea in a set of rules to follow.

### 3 Amigos
Refers to the primary perspectives to examine an increment of work before, during and after development:
- **Business Analyst** - What problem are we trying to solve? Make sure everyone understands user stories.
- **Developer** - How might we build a solution to solve that problem? Responsible for requirements of project.
- **Tester** - What about this, what could possibly happen? Will try and find issues to enhance testing process.

### Persona
Fictional characters which are created by a team to represent different user types that
might use your product/service. Helps the team understand users' needs, experiences, 
behaviours and goals. 

### Starfish retrospective
Ask the team for feedback
- **Keep Doing** - Something the team is doing well
- **Less of** - Something that is being done but might need refining because it is not currently
helpful or productive e.g. behaviour, an activity or routine
- **More of** - Activities that should be done more often
- **Stop Doing** - Things that dont bring value or are getting in the way
- **Start Doing** - New Idea. Something you would like to bring to the table to improve the 
process.

### Information radiators
A display whether handwritten or electronic which a team places in a highly visible location
so that all team members and anyone else can see latest info of current projects
e.g. count of automated tests, velocity, reoprts etc. AKA Big Visible Chart
- **Example** - Trello

### Root cause Analysis
Method of problem solving used for identifying the root causes of faults or problems. 
Basic method to use:
- Define the problem.
- Gather information, data and evidence.
- Identify all issues and events that contributed to the problem.
- Determine root causes.
- Identify recommendations for eliminating or mitigating the reoccurrence of problems or events.
- Implement the identified solutions.

### V-Model, Agile, Waterfall - Differences and use cases
V-Model, Agile and Waterfall are all different methodologies used for design and development. The 
V-Model and Waterfall follow a similar flow where they dont start on the next phase until the previous
one has been completed with V-Model being more modern than Waterfall. Agile on the other hand combines
design development and testing and iterates on them throughout the lifecycle of the product development.

Use Cases:
- **Waterfall**:
   - If project has strict requirements and there is little room to make changes
   - If organisation has strict processes that they adhere to 
   - If the product owner doesnt want to be very hands on
- **V-Model**:
  - Used for small to medium sized projects where requirements are clearly defined and fixed
  - When ample technical resources are available with needed technical expertise. 
- **Agile**:
  - If there arent many requirements as this will drive creativity and decreased time to market
  - When you can work flexibly as you can choose your own work etc.
  - If product owner wants to be more hands on - allows for involvement. They can make all decisions
  on the scope and functionality of the final product. 
  
## SQL
### What is a foreign key
A foreign key is used to link two tables together via references to the primary key in one table. It is to
ensure consistency and ensures the data matches exactly. 

### What is DML, DDL etc. 
These are the operations which can be performed on a database:
- **DDL (Data Definition Language) - Rows** 
  - SELECT
  - INSERT
  - UPDATE
- **DML (Data Manipulation Language) - Tables**
  - CREATE
  - ALTER
  - DROP
- **DQL (Data Query Language)**
  - GRANT
  - REVOKE
- **DCL (Data Control Language)**
  - COMMIT 
  - ROLLBACK
 
**Example** 

During the course, I had the opportunity to use these actions to create tables and query the Northwind
sample Database. For one project, I was tasked to CRUD a database and import data from a csv file into SQL.
The task involved creating a new table in SQL and import the data from the csv file into that table. I was
also able to write functions which enabled the user to query the table in different ways such as find
a specific movie by title, or insert a new movie into the table. These were all achieved by utilising 
the above methods using SELECT, INSERT and CREATE. 

## Python 
### What is OOP - 4 pillars
OOP stands for object oriented programming. The purpose of using OOP over say procedural programming is to
reduce the amount of code being written and to prevent rewriting of code. Classes consist of attributes (variables)
and methods (functions).

**There are 4 pillars:**

1. **Inheritance (most used)** - **Eliminates redundant code**.
We can use all functions and variable from parent class
2. **Encapsulation** - **Reduce complexity and increase reusability**.
Also used to reduce access, making private methods/
variables etc.
3. **Abstraction** - **Reduce complexity and isolate impact of changes**.
4. **Polymorphism (Many Forms)** - **Refactor code or case statements**.
It allows us to change behaviour or attributes
/ variables 

**Example**

I have utilised OOP throughout most of the projects during the python component of the DevOps course. One 
example was a project to build a simple bank account manager. In order to this, I used OOP where I created
different classes for user personal details, their bank details and a bank account manager which inherited
from the other 2 classes. Each of the classes held their own functionalities which could later be called
by the manage account class. The account worked and allowed a user to input their details and deposit or
withdraw money from their accounts.

### What is TDD and how we used it
TDD stands for Test Driven Development and it is a methodology that focuses on creating tests, writing code
that passes the tests and then modifying the tests to improve the program. TDD helps minimise the risk
of failure before sending a unfinished/buggy product to production.

**Example**

For one of my project during the python element of the course, I was tasked with using TDD when building
a simple bread factory. The project showed the benefits of using TDD as I was able to first create tests
which would satisfy the requirements for a factory and then I was able to write code which passed the tests
meaning my factory was working.

## DevOps
### What is DevOps
DevOps is a new term emerging from the collision of two major related trends. It is a practice of operations 
and development engineers participating together in the entire service lifecycle, from design through the 
development process to production support. It is a bridge between development and operations which encourages
the teams to work closer together, share responsibility deploy code and automate the pipeline.

3 Primary Practice Areas of DevOps
- **Infrastructure Automation** - Create your systems, OS configs and app deployments as code
- **Continous Delivery** - Build, test and deploy your apps in a fast and automated manner
- **Site Reliability Engineering** - Operate your systems; monitoring and orcheastration, sure, but also designing for operability
in the first place.

CI/CD is the backbone of DevOps. 
- Continous Integration - A development team builds products, writes tests and stores code for collaborative 
purposes. 
- Continous Delivery - Engage with the operations side by deploying onto the cloud

Without DevOps - Dev and Ops separate:
- Development team develops code/finish project without considering the production environment (Operations) leading to errors
and warnings.
- Operations team are responsible for managing services and making sure they run smoothly as per company needs but similarly
to development they face issues during deployment and a decrease in deployment time.

So overall, using DevOps breaks down the barriers, makes teams work much closer together which dramatically
improves the speed of product delivery which in turn improves customer satisfaction.

### Why did I choose DevOps?
