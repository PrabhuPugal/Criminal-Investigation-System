# Criminal Investigation System
## Project Description
The Criminal Investigation System is designed to assist law enforcement agencies in managing and solving criminal cases more efficiently. This system integrates various functionalities to track, analyze, and manage criminal records, investigations, and related data.

## Features
1. Case Management: Create, update, and manage criminal cases.
2. Suspect Tracking: Maintain records of suspects, including personal details, criminal history, and current status.
3. Evidence Management: Log and track evidence related to each case.
4. Reporting: Generate detailed reports for cases, suspects, and evidence.
5. User Management: Role-based access control for different types of users (e.g., investigators, administrators).
## Technologies Used
Frontend: Java Swing
Backend: Java
Database: MySQL
Version Control: Git
Installation Instructions
## Clone the repository:
```
git clone https://github.com/PrabhuPugal/Criminal-Investigation-System.git
cd Criminal-Investigation-System
```
## Set up the database:
1. Install MySQL and create a database named criminal_investigation.
2. Import the provided SQL file to set up the necessary tables:
```
mysql -u root -p criminal_investigation < database/criminal_investigation.sql
```
3. Configure the database connection:
4. Update the database configuration in the project files to match your MySQL credentials.
5. Compile and run the application:
```
javac -d bin src/*.java
java -cp bin Main
```
## Usage
1. Login: Use the credentials provided during the setup to log in.
2. Navigate through the system.
3. Dashboard: Overview of the system.
4. Cases: Manage criminal cases.
5. Suspects: Track and manage suspects.
6. Evidence: Log and track evidence.
7. Reports: Generate and view reports.
8. Users: Manage user accounts and roles.
   
## Contributing
Contributions are welcome! If you would like to contribute to the development of the Criminal Investigation System, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test thoroughly.
4. Submit a pull request with a clear description of the changes.
5. Please ensure that your code adheres to the project's coding standards and includes appropriate documentation.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact
For questions or feedback, please reach out to me at prabhupugal01@gmail.com.
