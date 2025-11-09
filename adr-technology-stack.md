# ADR-002 – Technology Stack

## Context and Problem Statement

The project will be developed mainly on macOS and in the university lab.  
I want to use basic web technologies that I already know and can test easily on XAMPP.

## Decision Drivers

* Simple setup    
* Familiar languages


## Considered Options

* HTML, CSS, JavaScript, PHP  
* Node.js with Express 
* Java with Spring Boot  

## Decision Outcome

Chosen option: **HTML, CSS, JavaScript, and PHP**, because I am comfortable with them and they are enough to create both the frontend and backend for the CMS.

## Consequences

* Good, because I can finish the proof of concept faster and manage both the frontend and backend easily.  
* Bad, because it might not handle very large systems if the project grows in the future.

## Confirmation

I tested the setup locally and it worked well for my development environment.

## Pros and Cons of the Options

### HTML, CSS, JavaScript, PHP

* Good, because I already know these tools and can build both frontend and backend easily.  
* Neutral, because performance is fine for now but may need optimization later.
* Bad, because it’s not as modern or scalable as newer frameworks.

## More Information

PHP backend can later be extended with REST APIs or chatbot integration.