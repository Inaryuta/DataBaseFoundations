# Apartment Management App - Workshop

This project is part of a workshop that focuses on building a comprehensive solution for apartment complexes. It includes several interconnected modules to streamline tasks like apartment management, payments, reservations, maintenance, and visitor authorization.

## Features

1. **Apartments and Blocks**
   - List and manage all apartments and blocks.
   - Track apartment status and rent details.

2. **Payments**
   - Process payments for services such as rent, maintenance, and reservations.

3. **Common Space Reservations**
   - Allow residents to reserve common areas (gyms, halls, etc.).

4. **Maintenance and Incidents**
   - Report and track incidents or maintenance issues within apartments or common spaces.
   - Staff members handle and resolve these incidents.

5. **Visitor Authorization**
   - Residents can authorize visitors and track their entry/exit.

6. **Personnel Management**
   - Manage staff such as administrators, security, and cleaning personnel.

## Entities

The system is designed around the following entities:

- **Apartment**: Details about each apartment (status, rent value, etc.).
- **Block**: Describes apartment blocks (name, address, number of apartments, etc.).
- **Payment**: Records payments for various services.
- **Common Space**: Defines common spaces in the complex.
- **Reservation**: Tracks reservations made by residents.
- **Incident**: Details of maintenance issues and incidents.
- **Resident**: Information on the residents living in the apartments.
- **Visitor**: Details on visitors authorized by residents.
- **Staff**: Information on personnel (administrators, maintenance, security, etc.).
- **User**: Generic user entity to handle access and roles in the app.

## Database Design

- The database schema includes relationships between these entities, allowing for structured management of the complex.
- Foreign key relationships ensure that data integrity is maintained, connecting residents to apartments, staff to incidents, and more.

## Technical Decisions

The following technical considerations were made during the design process:

- Prioritization of entities and features was based on user feedback from surveys.
- A user-centric design was chosen, where roles such as residents and staff are derived from the general user entity.
- Maintenance incidents are linked to both apartments and common spaces, ensuring a flexible system for managing issues.
