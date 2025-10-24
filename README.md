# AC-Repair-and-service-system
This web-based application gives potential customers of Air Conditioner Repair and Services Company an online platform to schedule a service request. MySQL and PHP were the primary development tools used for this project. It uses the NiceAdmin Template and the Bootstrap 5 Framework to provide a pleasing user experience. The project has a number of features and functionalities that are easy to use.
### Features and Functionalities

- **Management Site**
  - Login and Logout
  - Dashboard Page
  - Services Summary
  - Booking Summary
  - Image Slider
  - **Services Management**
    - Add New Service
    - List All Services
    - View Service Details
    - Update Service Details
    - Delete Service
  - **Booking Management**
    - Add New Booking
    - List All Bookings
    - View Booking Details
    - Update Booking Details
    - Delete Booking
  - **Inquiries Management**
    - List All Inquiries
    - Read Inquiry Details
    - Delete Inquiry
  - **User Management**
    - Add New User
    - List All Users
    - Update User Details
    - Delete User
  - Update Company Contact Information
  - Update System Information
  - Update Account Details
- **Public Site**
  - Home Page
  - "Our Services" List
  - Service Details Page
  - "About Us" Page
  - Submit Booking Request
  - Contact Page
  - Send a Message or Inquiries
### Prerequisites

- **Basic Knowledge of HTML, CSS, and JavaScript**: Needed to understand the front-end parts of the project.
- **PHP**: Required for running the back-end code that powers the app’s functionality.
- **MySQL**: Necessary for managing the database where project data is stored.
# Installation
1. Install XAMPP
2. Clone the repository:
   https://github.com/Bhoomikapm0116/AC-Repair-and-service-system.git
3. Set up the MySQL database in XAMPP and configure the config.php file.
4. tart XAMPP, open the project in a browser, and begin testing.
## System Setup

1. **Enable the GD Library** in your `php.ini` file.
2. Open your XAMPP Control Panel and start **Apache** and **MySQL**.
3. Extract the downloaded source code zip file.
4. Copy the extracted source code folder and paste it into the **XAMPP's "htdocs"** directory.
5. Open **PHPMyAdmin** in your browser by visiting: [http://localhost/phpmyadmin](http://localhost/phpmyadmin)
6. Create a new database named `acrss_db`.
7. Import the provided SQL file: `acrss_db.sql` located inside the **database** folder.
8. Finally, browse the **AC Repair and Services System** in your browser at: [http://localhost/php-acrss/](http://localhost/php-acrss/)
## Default Admin Access

- **Username**: admin
- **Password**: sourcecodester&123
# What to do if the default password doesn't work:
## How to Generate a Password Hash

1. Create a PHP file (`generate_hash.php`) with this code:
   ```php
   <?php echo password_hash('newpassword123', PASSWORD_DEFAULT); ?>
   ```
2. Save the file and place it in your XAMPP htdocs folder and run it in your browser (http://localhost/generate_hash.php)
3. Copy the generated hash.
4. In phpMyAdmin, replace the admin password with the new hash and save.(in acrss_db)
