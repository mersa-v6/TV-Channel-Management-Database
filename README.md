
# TV Channel Management Database

This project aims to create a comprehensive database system for managing a TV channel, including various aspects such as programs, staff, studios, departments, and more. It provides a structured approach to designing, implementing, and querying a relational database model using MySQL.

## Project Overview

The TV Channel Management Database includes the following components:

- **Entities and Relationships**: Designed using an Entity-Relationship Diagram (EER) to define entities, attributes, and relationships between them.
- **Database Schema**: Implemented in MySQL Workbench, utilizing InnoDB engine for transactional support and foreign key relationships.
- **Tables**: Each major aspect of the TV channel management (e.g., programs, staff, studios) is represented as a separate table with appropriate primary keys and constraints.
- **SQL Queries**: Example queries to demonstrate the functionality and querying capabilities of the implemented database.

## Database Schema

The database schema consists of the following main tables:

- **Channel**: Stores information about broadcasting frequencies and related details.
- **Program**: Manages program details including name, type, and description.
- **Staff**: Includes information about personnel working within the TV channel.
- **Studio**: Describes the locations and associated channels of various studios.
- **Department**: Represents different operational departments within the TV channel.

And more specialized tables like Ads, Director, Season, Episode, and others to cater to specific functionalities and relationships within the TV channel environment.

## Usage

To use this project:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/3laaMersa/TV-Channel-Management-Database
   cd TV-Channel-Management-Database
   ```

2. **Import Database Schema**:
   - Open MySQL Workbench.
   - Run the SQL script (`CREATION SQL.sql`) provided in the repository to create the `VNC` schema and its tables.

3. **Execute Queries**:
   - Use MySQL Workbench or any MySQL client to execute example queries (`QUERIES.sql`) for testing and verification.
