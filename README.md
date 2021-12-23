# D2-s
D2's is a Leave Management System developed in PHP/MySQL. D2'S is designed to provide simple leave request workflows for small organizations.

Installation

IMPORTANT:

If you want to install Jorani in production, please download it from the Release tab.

See the installation instructions for advanced configuration. In a nutshell :

•	If you use Apache, mod_rewrite must be activated and the config must allow overwriting settings with .htaccess file.

•	Download or clone Jorani. If you clone, please update the vendor folder with composer.

•	Upload the content of this folder on your server (in /var/www/...).

•	Create a database with /sql/leave-staff.sql script.

•	Create a user with SELECT, INSERT, UPDATE, DELETE, EXECUTE permissions on the database.

•	Update /application/config/database.php according to your database settings.

•	Update the end of /application/config/email.php with your e-mails settings.

•	Update the end of /application/config/config.php if you want to change the default behaviour.

•	It is recommended to change the private and public RSA keys (in assets/keys).

•	Check your installation with the requirements.php page at the root of your installation

•	The default user email is kurtis@gmail.com and password is curtis.


Status

This project is stable and ready for production.

Features

Comprehensive online documentation (English).

Notifications by e-mail (requested, accepted, rejected and new user).

Leave request approval workflow (1 validator).

Leave balance report (filtered by department).

Monthly presence report.

Export to XLSX (Excel, LibreOffice) in a click (almost all pages of the application).

HOD users can edit any leave or overtime request.

Set your own contracts and leave types.

Calendars of leaves (individual, team, collaborators, etc.).

Describe your organization in a tree structure and attach employees to entities, define a supervisor per entity.

REST API (OAuth2) fully documented and examples with PHP clients.
