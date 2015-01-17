Keypawa
This repo holds the code for the keypawa app.
TODO
How to setup Keypawa dev and production
How to auto backup database

NOTE
Always work on the feature Branch;
Create your branch from the master
NEVER make changes to the master

How to setup Dev server
Clone the repo to the root of your webroot
Import the database into your mysql server.
The database dump is located in `/sites/default/files/private/db_backup/` folder
Copy the file `/sites/default/settings.sample.php` to `/sites/default/settings.php`
Edit the file to reflect the username, password and the database of your local mysql server
