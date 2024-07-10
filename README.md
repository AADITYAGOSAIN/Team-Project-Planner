This project is an implementation of a team project planning system.
It allows for the creation of users,teams and project boards with tasks being assigned to users within a board.
The Team project planner is designed to facilitate the project management within teams.
Users can create accounts,form teams,and manage projects through boards where tasks can be assigned and tracked.
This setup aims to provide a streamlined and efficient way to handle team-based projects, ensuring clarity and accountability.

The project is divided into distinct modules for users,teams and project boards.This modular structure enhances maintainability,scalability and clarity.
Each module extends a base class to interact with the PostgreSQL database, ensuring a consistent approach to database operations.
PostgreSQL is an open-source database that supports complex queries and ensures data integrity.It is well suited for managing the relational data structure required for this project.

Database details are stored in .env file for security and ease of configuration.
Ensuring data integrity and avoiding duplicates are crucial for a reliable application.Constraints help maintain the quality and consistency of data.
Constraints on table columns and validation checks are enforced through SQL queries and error handling in Python.

JSON is a widely used data interchange format that is easy to read and write.Using JSON for API requests and responses facilitates integration with other systems and user interfaces.
Each method in the project modules accepts and returns JSON-encoded strings, ensuring a consistent and standardized approach to data handling.
The project is designed to be extensible allowing for future enhancements such as additional task management features, user roles and notification systems.
The current structure and coding practices support easy addition of new features.