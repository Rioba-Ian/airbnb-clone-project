# AIRBNB Clone Project

## Objective

This project is a mimic of the popular Airbnb website. The backend is designed to provide a robust and scalable solution for managing listings, bookings, and user interactions. It includes features such as user authentication, listing creation and management, booking management, and payment processing.

### Technology Stack

- Python (programming language)
- Django (web framework to build RESTful APIs)
- Django REST Framework (framework for building web APIs)
- GraphQL (query language for APIs in a structured format for data retrieval and manipulation)
- PostgreSQL (robust database management system that can handle large volumes of data and provide high performance)
- Docker (containerization platform )

### Database Design

We have five tables in our database:

- Users
  To manage user information, authentication, and authorization. We will also manage user preferences and settings. Details about the user shall also be stored: name, email, phone number, address, profile picture, etc.

- Properties
  To manage property information, including details such as location, amenities, pricing, and availability. We will also manage property preferences and settings. Details about the property shall also be stored: name, description, address, photos, etc.

- Bookings
  To manage the specific booking details, including check-in and check-out dates, guest information, and payment status.

- Payments
  The payment requests processed, done using payment methods such as credit card, PayPal, or bank transfer. We also see the users and the amount they paid.

- Reviews
  Very important for the user experience and reputation management. We will manage reviews, ratings, and feedback from guests. Details about the review shall also be stored: title, content, rating, date, etc.

You can have a close look at the entity diagram below:

![Entity Diagram](./docs/images/database-entity.png)

#### Team Roles

Backend Developer - Responsible for handling business logic, API design, and database interactions.
Database Administrator - Responsible for managing the database schema, optimizing queries, and ensuring data integrity.
Frontend Developer - Responsible for building the user interface, implementing user interactions, and integrating with the backend API.
Devops Engineer - Responsible for managing the deployment and infrastructure of the application.
QA Engineer - Responsible for testing the application, identifying bugs, and ensuring quality.
UX/UI Designer - Responsible for designing the user interface, creating wireframes, and ensuring a seamless user experience.
