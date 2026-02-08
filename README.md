🎬 Movies Streaming Platform
==========================
A Netflix-style Movie Streaming Web Application that allows users to browse and watch movies online.
This project simulates an OTT platform with user management and movie database storage.

📖 Description
---------------
Movies Streaming is a Netflix-inspired OTT (Over-The-Top) web application developed to simulate a real-world online movie streaming platform. The system allows users to register, log in, browse a collection of movies, and stream video content directly through a web interface. The main objective of this project is to demonstrate how a complete streaming service works by integrating frontend design, backend logic, and database management into a single functional system.

This application follows a client–server architecture, where the frontend provides an interactive and responsive user interface, while the backend handles authentication, data processing, and communication with the database. All important data — such as user accounts, movie details, and watch history — is stored and managed in a structured database system. This ensures that user sessions, preferences, and movie information can be dynamically loaded and maintained.

The platform includes essential OTT-style functionalities such as user authentication, movie catalog display, and a dedicated video player page for streaming. Each component of the system is designed to reflect the workflow of modern streaming platforms, helping in understanding how media content is delivered and managed online.

From a learning perspective, this project highlights key full-stack development concepts, including:

Frontend and backend integration

Session handling and user management

Database connectivity and CRUD operations

Dynamic content rendering

Web application architecture

Overall, this project serves as an educational implementation of an OTT streaming model, built to gain practical experience in developing database-driven web applications and understanding how online entertainment platforms operate behind the scenes.


📌 Project Overview
---------------
This system is designed to provide an online platform where users can:

Browse available movies

Watch/stream movies

Manage user accounts

Store watch history

The application connects to a database to store movie details and user information.

✨ Features
-----------
👤 1. User Registration & Login System

The platform provides a secure authentication system where new users can create an account and existing users can log in. User credentials are stored in the database, and session handling ensures that only authenticated users can access movie streaming features. This simulates real-world OTT account systems.

🎬 2. Movie Listing & Catalog

All available movies are displayed in a structured layout. Each movie entry contains information such as title, thumbnail/poster, and description. The data is dynamically loaded from the database, allowing easy updates and scalability.

▶ 3. Movie Streaming / Playback

Users can select any movie from the catalog and play it on a dedicated video player page. The system handles video file retrieval and playback through the browser, demonstrating how streaming platforms deliver media content.

🗄 4. Database Integration

The system is fully connected to a database that stores:

User account details

Movie information (name, path, description)

Watch history

This ensures dynamic content loading and persistent data storage.

📱 5. Responsive User Interface

The application interface adapts to different screen sizes (desktop, tablet, mobile). This improves accessibility and reflects modern web design standards used in real streaming services.

📊 6. Watch History Tracking

Every time a user watches a movie, the system records this activity in the database. This feature demonstrates how streaming platforms track user activity for personalization and analytics.


🧰 Tech Stack Table

Frontend	      HTML, CSS, JavaScript
Backend        	PHP
Database	      MySQL
Server	        XAMPP / Localhost

📁 Project Structure
---------------------
Movies_Streaming/
│
├── index.php        # Home page (movies display)
├── login.php        # User login page
├── register.php     # User registration page
├── logout.php       # Logout logic
├── movie.php        # Individual movie details page
├── player.php       # Video streaming page
│
├── includes/
│   ├── db.php       # Database connection
│   ├── header.php   # Navigation bar
│   └── footer.php   # Footer section
│
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
│
├── uploads/         # Movie video files storage
└── database.sql     # Database structure file

⚙️ How to Run
---------------
1. Install XAMPP.

2. Copy the Movies_Streaming project folder into:
C:\xampp\htdocs\

3. Open XAMPP Control Panel and start Apache and MySQL.

4. Open your browser and go to:
http://localhost/phpmyadmin
→ Create a new database
→ Import the database.sql file.

5. In the browser, open:
http://localhost/Movies_Streaming

🧪 Testing Instructions
------------------------
1. Register a new user account.

2. Log in using the registered credentials.

3. Check if movies are displayed on the homepage.

4. Click a movie and verify that it plays properly.

5. Log out and confirm that protected pages are not accessible.

📸 Screenshots
---------------
Here are some screenshots of the project's UI:
📝 License
----------
This project is licensed under the MIT License.
It is developed for learning and educational purposes.
