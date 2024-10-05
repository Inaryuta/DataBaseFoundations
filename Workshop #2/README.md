# Apartment Management App - Workshop 2

This project is part of the second workshop for developing the **Apartment Management App**. Defining ways to extract meaningful information using **Relational Algebra**. The goal is to answer specific queries and validate them by presenting the results in a table format.

## Objectives

### Apartment Data Extraction
- Filter and retrieve information about apartments based on area, rooms, and owners.
- Present apartment numbers, owners, and associated services based on specific conditions.

### Owner Information
- Extract detailed information about apartment owners, such as age, children, and pets.
- Perform filtering operations based on owner age, number of children, pets, and name substrings.

### Reservation Queries
- Retrieve reservation details such as apartment numbers, owners, dates, and common spaces.
- Extract reservations based on specific dates, common spaces, or apartment numbers.

### Entity-Relationship Diagram (ERD)
- Design an ER diagram to visualize relationships between apartments, owners, reservations, and services.
- Optionally add new entities to improve data organization and manage many-to-many relationships.

## ER Diagram

An ER Diagram is required to visualize relationships between the tables **Apartment**, **Owner**, **Reservations**, and **PublicServices**. Add the new entity **ApartmentServices** to break the many-to-many relationship between **Apartment** and **PublicServices**.

## Technical Decisions
- All relational algebra expressions were written to retrieve meaningful data and validate relationships between the entities.
- A new entity (**ApartmentServices**) was added to handle the many-to-many relationship between **Apartments** and **PublicServices**.
- Queries were designed to meet ApartaApp's requirements and tested for data accuracy.
