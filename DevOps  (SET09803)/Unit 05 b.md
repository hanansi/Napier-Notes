# User Stories and Use Cases
## User Stories
A **user story** is a definition of what our software should do for a user. The common template is:
> As a **< user role >**, I can **< activity >** so that **< business value >**.

The parts that need to add are:

- **User role** is who the story involves. It needs to be specific enough to allow a conversation. _User_ is not a legitimate user role.
- **Activity** is the task the user wants or is required to do.
- **Business value** is why the task is important.

A user story is defined using the **Three Cs formula**:

- **Card** is a physical token to hold concepts. Physical means a member of the team can take it, it can be used in a meeting, and it can be visualised easily on the wall.
- **Conversation** between stakeholders and the team. The story does not provide enough information for implementation, but allows a conversation to occur to discover the information.
- **Confirmation** means the objectives of the conversation have been reached.

### User Stories versus Requirements
- They are not detailed requirements specifications (something a system shall do) but are negotiable expressions of intent (it needs to do something about like this) .
- They are short, easy to read, and understandable to developers, stakeholders, and users.
- They represent small increments of valued functionality that can be developed in a period of days to weeks.
- They are relatively easy to estimate, so effort to implement the functionality can be rapidly determined.
- They are not carried in large, unwieldy documents but rather organized in lists that can be more easily arranged and rearranged as new information is discovered.
- They are not detailed at the outset of the project but are elaborated on a just-in-time basis, thereby avoiding too early specificity, delays in development, requirements inventory, and an over constrained statement of the solution
- They need little or no maintenance and can be safely discarded after implementation.
- User stories, and the code that is created quickly thereafter, serve as inputs to documentation, which is then developed incrementally as well.

### Conditions of Satisfaction
**Conditions of Satisfaction** are questions that need to be answered for the user story to be completed to the quality required by the Product Owner.

### Tasks
Tasks are pieces of work that can be completed by individual team members.

### Epics
An epic has a collection of features, which are decomposed into user stories for delivery. Epics are therefore more strategic, not specific.

### Working with User Stories
- A member of the development team takes responsibility for a backlog item (story, task, fix, etc.).
- The item is developed to meet the teams _Definition of Done_, e.g.,:
    - Refined.
    - Designed.
    - Coded.
    - Integrated.
    - Tested.
- The item is delivered by integrating it into the build.
- Signal that the item is developed and ready for acceptance testing.
- Get the item accepted by the _Product Owner_:
    - Passes acceptance tests.
    - Meets the _Conditions of Satisfaction_.

### Working with the Product Owner
There are three stages that the Product Owner helps the development team work with user stories:

- **Definition**: the developer needs to work with the Product Owner to understand what is meant by a story. A good rule of thumb for the Product Owner to think about here is _if you don't know how to do IT, then you don't really know what IT is_.
- **Building**: during development new topics and ideas may come out. Again the developer and Product Owner is required to ensure story understanding evolves during development.
- **Testing**: a story must pass an acceptance test which checks that the code delivers against the story. The Product Owner can assist by helping the developer understand the functionality of the user story, and doing some inspection of the behaviour defined.

### Story Acceptance Test
A **Story Acceptance Test** determines if a story has been implemented correctly.

### Story-Task Relationship
- A **backlog item** is either a _epic_, _feature_, or _task_.
- An **epic** is large body of related work to be undertaken in the project. This is realised by the delivery of one or more _features_.
- A **feature** is a particular facet of the project to be delivered. These are realised via one of more _stories_.
- A **story** is work that is undertaken by the development team as specified by the _Product Owner_. It has _Conditions of Satisfaction_ and is done when it passes one of more _acceptance tests_. A story can be decomposed into one or more _tasks_.

## Use Cases
So a use case is a _list of actions_ between a _actor and system_ to _achieve a goal_. This has similar concepts to a user story:

- We have a **user**: the **actor**.
- We have what they will do: **a series of actions**.
- We have why the value: the **goal**.

Here we will look at some of the sections:

- **Goal in Context**: _a longer statement of the goal, if needed_.
- **Scope**: _what system is considered black-box under design_.
- **Level**: _one of: Summary, Primary task, subfunction_.
- **Preconditions**: _what we expect is already the state of the world_.
- **Success End Condition**: _the state of the world upon successful completion_.
- **Failed End Condition**: _the state of the world if goal abandoned_.
- **Primary Actor**: _a role name for the primary actor, or description_.
- **Trigger**: _the action upon the system that starts the use case, may be a time event_.
- **Main Success Scenario**: _put here the steps of the scenario from trigger to goal delivery, and any cleanup after_.

# Lab 5
### UML Diagram Types
UML diagrams can be divided into two broad types:

- **Behavioural diagrams**: those which describe the behaviour of the system as it executes.
	- Use Case diagrams -  captures functionality required from a user story point of view
	- Activity diagrams - allows steps to be defined in the process
	- Sequence diagrams - map the communication between components (objects) as a system executes, and focuses on the method calls between objects
- **Structural diagrams**: those which describe the static structure of the system.
	- Class diagrams - attempts to capture the details of a class in a diagram
### Use Case Diagram
Use case diagrams try to capture the abstract behaviour of a system at specification time.

