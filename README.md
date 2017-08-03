README
======
Author : Thien Le
This sample app using Ruby on Rails one page application, Application display course online.

Setup
-----

This app uses PostgreSQL by default. Configuration settings for SQLite
and MySQL are available in config/database.yml, commented out.
To use SQLite or MySQL, edit config/database.yml and use the settings
you prefer.

Then:

    rake db:setup   # Create and migrate the database
    rake data:fake  # Set up fake data. Takes a few minutes.
