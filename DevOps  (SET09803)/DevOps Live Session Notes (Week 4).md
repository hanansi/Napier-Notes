## Group Assessment
### Issues, User Stories, Use Cases, & Use Case Diagrams
- Clump the 32 requirements by groups for similar cases (eg. Countries, Cities, Population, etc..)
- That reduces the 32 requirements to be around 5-6 use cases instead (groups decide how to break it down)
- Issue title can be worded like: "I need to create reports ..... + {grouped requirements name}"
- The specific requirements (reports) that each issue includes will go into the description

### Kanban Board, Zube.io, Github Projects
- Zube.io only limited to 4 people
- Alternative is to use the Kanban board provided in the github projects
- The To-do column will be the product backlog and you can add a sprint column to carry out the allotted time frame for that given sprint
- Issues will be added to the product backlog

### Use Case Diagrams Software:
- Draw.io - recommended by Dr. Kevin
- PlantUML - not recommended by Dr. Kevin but can still use it
- Both are available in Intellij plugin section

### Extra Miscellaneous Stuff:
- DB Navigator Plugin and Database Panel to view the database within Intellij using the Dockerfile
	- Shows database relationship
	- Able to test sql queries using MySQL Console
- Note: use mysql server docker image for updated labs
- Groups decide how they want to structure the Java code:
	- Breakdown each report as a Java Class
	- Hold database queries in a text file to shorten length of Java code
	- Make an Object for each table in the database (Table -> Tools -> Scripted Extensions ->Generate POJO )

- [x]  GitHub project for coursework set-up.
- [x]  Product Backlog created.
- [x]  Project builds to self-contained JAR with Maven.
- [x]  Dockerfile for project set-up and works.
- [x]  GitHub Actions for project set-up and build is working using JAR, and Docker on GitHub Actions.
- [x]  Correct branches for GitFlow workflow created - includes `master`, `develop`, and `release` branches.
- [ ]  First release created on GitHub.
- [x]  Code of Conduct defined.
- [x]  Issues being used on GitHub.
- [x]  Tasks defined as user stories.
- [x]  Project integrated with Zube.io.
- [x]  Kanban/Project Board being used.
- [ ]  Sprint Boards being used.
- [ ]  Full use cases defined.
- [ ]  Use case diagram created.