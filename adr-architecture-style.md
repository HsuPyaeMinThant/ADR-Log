# ADR-001 – Architecture Style

## Context and Problem Statement

The Complaint Management System (CMS) must let users from different companies log and track complaints safely.  
The system also needs to be easy for me to build for the first version and possible to expand later.

## Decision Drivers

* Easy to design and test  
* Can be upgraded later if needed  

## Considered Options

* Layered Architecture
* Microservices Architecture
* Service-Oriented Architecture (SOA)

## Decision Outcome

Chosen option: **Layered architecture**, because I want a clear structure that separates the user interface, business logic, and database.  
It also matches what I can build easily with PHP.

## Consequences

* Good, because it helps me understand how each part of the system works and keeps the code clean.
* Bad, because it might not scale easily if many features or services are added in the future.

## Confirmation

I compared different styles in class and decided this fits the project size and my current skills.

## Pros and Cons of the Options

### Layered Architecture

* Good, because it separates presentation, logic, and data clearly.  
* Neutral, because it can be improved later by splitting layers into services.  
* Bad, because it might not be ideal if the system grows very large.

## More Information

Later, I can split parts of the application (like notifications) into services if needed.
