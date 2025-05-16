#Hibernate Application with Custom Sequence Generator
This project demonstrates the use of Hibernate to persist the StudentInfo entity into a relational database using a custom sequence generator for ID management. It provides a simple example of Hibernate configuration, entity mapping, and database interaction.

#Features
Entity Mapping: Maps the StudentInfo class to a student database table.

Custom Sequence Generation: Demonstrates the use of @SequenceGenerator for custom ID generation.

Database Interaction: Shows how to insert data into the database using Hibernate.

#Technologies Used
Java: Programming language

Hibernate: ORM framework

Jakarta Persistence (JPA): Annotations for ORM

MySQL/PostgreSQL: (or any relational database)

Maven: Dependency management
#
Prerequisites
Before running this project, ensure you have:

Java Development Kit (JDK) installed.

A relational database (e.g., MySQL, PostgreSQL) with sequence support.

Maven installed for dependency management.

#Project Structure
src/
├── main/
│   ├── java/com/rocky/app/
│   │   └── LaunchStandardApp.java    # Main application class
│   ├── java/com/rocky/model/
│   │   └── StudentInfo.java          # StudentInfo entity class
│   ├── resources/
│       └── hibernate.cfg.xml         # Hibernate configuration file
