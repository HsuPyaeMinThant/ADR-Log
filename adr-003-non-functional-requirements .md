# ADR-003 – Non-Functional Requirements (NFRs)

## Context and Problem Statement
The CMS must be easy to use, available at all times, and safe for user data.  
It also needs to be accessible for everyone, including users with disabilities.

## Decision Drivers
* 24/7 availability for online users   
* Strong data protection
* Accessibility for different users  
* Smooth and responsive design  

## Considered Options
* Define clear NFR targets from the start  
* Focus only on core functions first  

## Decision Outcome
Chosen option: **Define clear NFR targets from the start**, because I want the system to have good quality and user experience, not just working features.


## Consequences
* Good, because it helps me design the system properly with usability and security in mind.  
* Bad, because it takes more planning and time to test those quality areas.

## Confirmation
I learned from past projects that setting NFRs early helps avoid rework later.

## Pros and Cons of the Options
### Define clear NFR targets from the start 

* Good, because it improves reliability and user satisfaction. 
* Neutral, because it adds some extra work in planning.  
* Bad, because it may extend development time slightly.

## More Information
Main goals:  
* Availability: 24/7 access for users  
* Security: password hashing, role-based access  
* Scalability: support more users each year  
