# Final Project for Database II - Neo4j and Web Interface

This repository contains the code and documentation for the final project of the Database II course. The project leverages the Neo4j graph database to model and query complex relationships in the Star Wars universe. It includes a web interface for database interaction, data insertion scripts, and detailed presentation and report materials.

## Repository Structure

```
project-root/
├── src/
│   ├── data-insertion.cypher      # Cypher script for inserting data into Neo4j
│   └── web-interface.html         # Main web page for user interaction
├── docs/
│   ├── presentation.pdf           # Project presentation slides
│   └── report.pdf                 # Detailed project report
└── README.md                      # Project documentation (this file)
```

## Features

- **Neo4j Integration**: Models and queries complex relationships among Star Wars characters, locations, items, and affiliations.
- **Web Interface**: Allows users to interact with the database through a user-friendly HTML page, with features for:
  - Querying character details.
  - Exploring relationships (e.g., familial or mentor-apprentice connections).
  - Adding new characters and relationships.
- **Documentation**: Comprehensive slides and a report detailing the project design, implementation, and technologies used.

## Technologies Used

- **Neo4j**: A graph-oriented database used for storing and querying interconnected data.
- **Cypher**: Query language for defining, manipulating, and querying graphs in Neo4j.
- **HTML, CSS, and JavaScript**: For creating the web-based user interface.
- **Neo4j JavaScript Driver**: Integrates the web interface with the database for dynamic interactions.

## How to Use

1. **Setup Neo4j**:
   - Install and configure Neo4j on your machine.
   - Load the `data-insertion.cypher` script into Neo4j to populate the database with Star Wars universe data.

2. **Run the Web Interface**:
   - Open `web-interface.html` in a browser to interact with the database.
   - Use the interface to query character details, explore relationships, or add new data.

3. **Documentation**:
   - Review the `presentation.pdf` and `report.pdf` in the `docs/` folder for a detailed overview of the project, including design decisions and implementation details.

## Contributors

- Éric Fadul Cunha Yoshida
- Henrique Garcia Campanha
- Lidyane Küster
- Luiz Eduardo Casella
- Stella Hadassa Alves Vieira

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
