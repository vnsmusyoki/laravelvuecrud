


1. Extracting the Laravel Project:
   - First, download the project files (the compressed .zip file) from the shared and save it to your local computer.
   - Next, extract the project files from the compressed file using an archive utility software like WinZip or WinRAR.
   - Once the files are extracted, place the project folder in your server directory or your local web server directory (like XAMPP, WAMP) and specifically in htdocs for xampp or www for wampp.

2. Installing Dependencies:
   - if you are doing this on a completely new machine, download and install the following apps
        - Xampp
        -Composer
        - Git
        -Node Js
   - Before you can run a Laravel project, you need to install the above dependencies. Open a terminal or command prompt and navigate to the project directory.
   - 
   - Run the command `composer global require laravel/installer`. this command will install the composer globally into your machine. 

3. Setting up the Environment:
    - Open the `.env` file in a text editor and update the database credentials (DB_HOST, DB_PORT, DB_DATABASE, DB_USERNAME, DB_PASSWORD) to match your server settings or local environment.


4. Importing the Database:
   - To import the database, you first need to create a new database with the same name as the one in the SQL file ('guacuco.sql').
   - Open the database management tool ( `http://localhost/phpmyadmin`) and create a new database with the same name as the one in the SQL file.
   - Once the database is created, select it from the left sidebar and navigate to the 'Import' tab.
   - Click on 'Choose File' and select the 'guacuco.sql' file from your local computer. 
   - Finally, click on the 'Go' button to import the database.

6. Running the Laravel Project:
   - Once the dependencies are installed, environment variables are set, and database is imported, you can run the Laravel project.
   - Open a terminal or command prompt, navigate to the project directory, and run the following command: `php artisan serve`.
   - This command will start the local server and display a URL (like `http://127.0.0.1:8000`) where you can access the Laravel project.

That's it! Make sure the first two xampp options are up and running smoothly without throwing any error. ie. ##Apache and MySQL 
