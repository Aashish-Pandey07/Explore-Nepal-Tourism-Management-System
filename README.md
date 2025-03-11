# Explore-Nepal-Tourism-Management-System
## Overview
**Explore Nepal - Tourism Management System ** is a full-stack web-based tourism management system designed to help users explore Nepal’s popular destinations, book trips, and manage travel-related services. The website provides a user-friendly interface for travelers, travel agencies, and administrators.

## Features
- 🌍 **Destination Listings**: Showcases popular travel destinations in Nepal.
- 🏨 **Hotel & Package Booking**: Allows users to book hotels and travel packages.
- ✈️ **Tour Management**: Provides an interactive platform for managing tour itineraries.
- 🔍 **Search & Filter**: Users can search and filter destinations based on preferences.
- 🔑 **User Authentication**: Secure login/signup for users and admins.
- 📊 **Admin Dashboard**: Admins can manage bookings, users, and content.

- ## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL

## Installation & Setup
### Prerequisites:
- Install **XAMPP** or **WAMP** (for PHP & MySQL).
- Ensure **Apache** and **MySQL** services are running.

- ### Steps to Set Up:
1. **Clone the repository**:
   ```sh
   git clone https://github.com/your-username/explore-nepal.git
2. Move the project to your server directory (e.g., htdocs in XAMPP):<br>
mv explore-nepal /xampp/htdocs/
3. Import the database: <br>
- Open phpMyAdmin (http://localhost/phpmyadmin/).
- Create a new database (e.g., explore_nepal).
- Import database.sql (provided in the project folder).
3. Configure Database Connection: <br>

4. Open config.php and update the database credentials: <br>
$host = "localhost";
$user = "root";  // Default for XAMPP/WAMP
$password = "";  // Leave empty if using local server
$dbname = "explore_nepal";

5. Run the Projects <br>
Open browser and go to: <br>
http://localhost/explore-nepal/

#Screenshots



# Contributing
We welcome contributions! To contribute:
- Fork the repository.
- Create a new branch: git checkout -b feature-branch
- Make your changes and commit: git commit -m "Added new feature"
- Push changes: git push origin feature-branch
- Submit a pull request.
