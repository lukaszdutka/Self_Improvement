## Contract (Kontrakt)


## Component (Komponent)
Zestaw współpracujących klas, które tworzą wyższego poziomu kontrakt


## Container (Kontener)
środowisko uruchomieniowe dla komponentów
kontenerem może być też baza danych
jednostki gotowe na osobne wdrożenie (komunikują się między sobą 
za pomocą zewnętrznego API - np. rest/soap/messaging)

## System (System)
zestaw Kilku kontenerów współpracujących ze sobą razem tworząc jakąś
wartość biznesową 

## Context Diagram C1 (Diagram kontekstu)
It is high level of abstraction diagram
- Who uses our system?
- Why our system was created
- what interactions are there?
- what is the purpose of those interactions?

## Container Diagram C2 (Diagram kontenerów)

it contains containers described with:
name, responsibility, technology, interactions

## Component Diagram C3 (Diagram komponentów)

## classes of architectural drivers
- functional requirements (Patients can cancel visit)
- quality (scalable, extendable, secure, maintainable, observable etc.)  
It can be expensive to make changes there (introduce scalability later? hard)
- project constraints (limited time, budget, knowledge)
- conventions (rules used in company - i.e. we use one and only library for logging / make project more appealing)
- project goals (you create prototype or proper solution)

Short: 
- Functional
- Quality
- Project Constraints
- Conventions
- Project goals

## Stakeholder mapping
Is used for discovering architectural drivers.  
Brainstorming together in order to discover stakeholders and 
uncover their priorities and importance of those priorities.
Also - map decisiveness of a person.  
High decisiveness and high priorities or low decisiveness and low priorities.  
Client will tell what are functional requirements, but CTO will 
tell us about conventions or project constraints.

"is X priority is important?" - bad.   
"is X is more important than Y?" - good.

Some drivers can be related. Five 9's (quality) can cost 10 times more (project constraints)

