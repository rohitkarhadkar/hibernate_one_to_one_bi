# Hibernate Project with Bidirectional Relationships

This Hibernate project extends the previous project (uni-directional relationship) by implementing a bidirectional relationship between the `Instructor` and `InstructorDetail` entities. In this bidirectional mapping, you can access an instructor by first accessing its associated instructor detail, enabling more flexible querying and navigation of the data model.

## Features

- **Bidirectional Relationships**: Implements a bidirectional relationship between `Instructor` and `InstructorDetail` entities, allowing navigation from one entity to the other.
- **Enhanced Data Access**: Enables accessing an instructor through its associated instructor detail, providing more flexibility in querying and navigating the data model.
- **Updated Project Structure**: The project structure remains similar to the previous project but with additional annotations and configurations for bidirectional mapping.

## Project Structure

The project structure remains similar to the previous example, with the following components:

- `Instructor` entity: Represents an instructor with basic details such as first name, last name, and email.
- `InstructorDetail` entity: Stores additional details for an instructor, such as YouTube channel and hobby.
- `Main` class: Contains the main method to demonstrate CRUD operations and bidirectional mappings.

## Usage

To run the Hibernate project with bidirectional relationships locally, follow the same steps as before:

1. Clone this repository.
2. Open the project in your preferred IDE.
3. Update the Hibernate configuration file (`hibernate.cfg.xml`) with your database connection details.
4. Run the `Main` class to execute the CRUD operations and observe the behavior of bidirectional mappings.

## Contributing

Contributions are welcome! If you have any suggestions, bug fixes, or feature implementations, please open an issue or submit a pull request.

