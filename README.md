Contact Form Application
The Contact Form Application is a simple web-based form that allows users to submit their contact information and messages. The submitted data is stored in a MySQL database.

Requirements
Before running the application, make sure you have the following prerequisites installed on your system:

PHP (Version 7.0 or higher)
MySQL Database Server
Web server (e.g., Apache, Nginx, XAMPP, or WAMP)
Installation
Follow these steps to set up and run the Contact Form Application:

Clone the repository or download the source code.

Copy the application files to your web server's root directory (e.g., htdocs in XAMPP or www in WAMP).

Create a MySQL database:

Open phpMyAdmin or any MySQL client tool.
Create a new database named contact.
Configure the database connection:

Open the submit_form.php file located in the application directory.
Update the database connection parameters ($host, $dbname, $user, and $pass) with your MySQL credentials.
Create the contact_form table:

Open a Command Prompt or Terminal.

Navigate to the application directory.

Execute the following command:

Copy code
php create_table.php
This will create the contact_form table in the contact database.

Start your web server and MySQL database server.

Open a web browser and access the application:

arduino
Copy code
http://localhost/contact-form/
Usage
Open the Contact Form Application in your web browser.

Fill in the required contact information: Name, Email, Contact Number, and Message.

Click the "Submit" button to save the data to the database.

After successful submission, a success toast will appear, and the form fields will be cleared.

Troubleshooting
If you encounter any issues while accessing the application, make sure your web server and database server are running.

Check the PHP error logs for any error messages or issues related to the application.

License
The Contact Form Application is released under the MIT License.

Authors
Your Name
