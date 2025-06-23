# 🔐 Role-Based Access Web App (PHP + MySQL + AJAX)
A role-based access web app built with PHP, MySQL, and AJAX. Features secure login, session handling, and three roles: Admin, Agent, and User. Admins manage users and agents, with real-time updates via AJAX. A foundational full-stack project focused on access control and UX.

---

````markdown
## 🛠️ Setup & Installation

Follow these steps to run the project locally:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/saad-subhani/php-session-based-mini-project.git
````

Or download the ZIP file and extract it into your local server directory.

2. **Move to Server Directory**

   * For **XAMPP**: Move the extracted folder to `C:/xampp/htdocs/`
   * For **WAMP**: Move the folder to `C:/wamp/www/`

3. **Start Local Server**

   Open XAMPP or WAMP and start both the **Apache** and **MySQL** services.

4. **Import the Database**

   * Go to [http://localhost/phpmyadmin](http://localhost/phpmyadmin)
   * Click the **Import** tab (no need to create the database manually)
   * Upload and import the `database.sql` file provided in the project root
   * It will automatically create and use a database named `phptask`

5. **Configure the Database Connection**

   Open `db.php` (or your database config file) and set your connection settings:
   $servername = "localhost";
   $username = "root";     // Default for XAMPP
   $password = "";         // Leave empty unless you set a MySQL password
   $dbname = "phptask";    // Matches the name in database.sql
   

6. **Run the Project**
Open your browser and go to:

http://localhost/php-session-based-mini-project/
 

 🔑 **Demo Login Credentials**

Use the following test accounts:

| Role  | Email                                     | Password |
| ----- | ----------------------------------------- | -------- |
| Admin | [admin@gmail.com](mailto:admin@gmail.com) | 123      |
| Agent | [agent@gmail.com](mailto:agent@gmail.com) | 123      |
| User  | [user@gmail.com](mailto:user@gmail.com)   | 123      |

 ⚠️ Important Notes:

 Admins must be added manually through phpMyAdmin or SQL.
 Agents can be added via the Admin dashboard.
 Users can register from the login form (redirects to `register.php`).


