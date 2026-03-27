# CampusLife-planner
Logic of the Solution:
"I updated the project to version 2.0 by introducing a Class Hierarchy. Instead of using a single class, I created a base superclass called PlanItem to store shared attributes like title, estimated hours, and completion status.
I then implemented Inheritance by creating specialized subclasses: Assignment and StudySession. This allowed me to use Polymorphism:
* Each subclass overrides methods to define its own specific behavior.
* For example, the Assignment class has its own logic to calculate 'urgency' based on the due date.
In the main program, I used a single collection of the base type (PlanItem) to store different objects, demonstrating that the system can process various student activities through a shared interface."
