# ADR-004 –  Database Choice

## Context and Problem Statement
The CMS needs a relational database that works smoothly with PHP and XAMPP for a fast PoC.

## Decision Drivers
* Easy local setup with PHP   
* Familiar tooling (phpMyAdmin)
* Free and widely supported  

## Considered Options
* MySQL 
* PostgreSQL
* SQLite

## Decision Outcome
Chosen option: **MySQL**, because it integrates with PHP/XAMPP and I can move quickly using tools I already know.

## Consequences
* Good, because development is fast and setup is minimal. 
* Bad, because advanced features (e.g., JSON indexing, extensions) are stronger in PostgreSQL.

## Confirmation
Local tests on XAMPP were successful. 

## Pros and Cons of the Options
### MySQL

* Good, because it’s common with PHP, easy to host, and has phpMyAdmin. 
* Neutral, because it can migrate later if required. 
* Bad, because some advanced extensions features are limited.
