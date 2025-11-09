# ADR-002 – Technology Stack

## Context and Problem Statement

The project will be developed mainly on macOS and in the university lab.  
I want to use basic web technologies that I already know and can test easily on XAMPP.

## Decision Drivers

* Simple setup    
* Familiar languages


## Considered Options

* HTML, CSS, JavaScript (frontend), PHP (backend)
* Node.js with Express 
* Java with Spring Boot  

## Decision Outcome

Chosen option: **HTML, CSS, JavaScript for the frontend and PHP for the backend**, because I am comfortable with them and they are enough to create both the frontend and backend for the CMS.

## Consequences

* Good, because I can build, test, and deploy locally and manage both the frontend and backend easily.  
* Bad, because it might not handle very large systems if the project grows in the future.

## Confirmation

I tested the setup locally and it worked well for my development environment.

## Frontend Technology
**HTML, CSS, JavaScript**
The frontend will handle user interaction and data presentation.
* HTML builds the structure of web pages.
* CSS manages layout and responsive design.
* JavaScript handles client-side validation and dynamic updates.
  
**Reasons for choice:**  
These are easy to design, run directly in any browser, and integrate smoothly with a PHP backend.

## Backend Technology
**PHP**
The backend will manage data processing, authentication, and complaint management.  
* PHP controls API endpoints, and user sessions.  
  
**Reasons for choice:**  
PHP fits naturally with Xampp, and MSQL and supports rapid web app development.

## Pros and Cons of the Options
### HTML, CSS, JavaScript (frontend), PHP (backend)
* Good, because I already know these tools and can build both frontend and backend easily.  
* Neutral, because performance is fine for now but may need optimization later.
* Bad, because it’s not as modern or scalable as newer frameworks.

## More Information

PHP backend can later be extended with REST APIs or chatbot integration.
