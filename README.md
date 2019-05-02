**WILDLIFE TRACKER**

Java app that helps you record and keep track of endangered species of animals.

**CREATED BY**

Mark Mwago

**DESCRIPTION**

This app allows the user to track and record endangered animals once they are sighted. Rangers can use it to identify areas that endangered animals reside or are spotted.

**SETUP/INSTALLATION REQUIREMENTS**

1. Clone the repository.
2. Navigate to the file.
3. Open with the text editor of your choice
4.  Run "gradle run" to open the application on your browser.

**FOLLOW THESE INSTRUCTIONS TO RECREATE DATABASE**

1. Open terminal/command line on your computer.
2. Type psql to run the postgress database server, then type;
3. CREATE DATABASE wildlifetracker; to create database.
4. then \c wildlifetracker; to connect your project to your database
5. Type CREATE TABLE animals (id serial PRIMARY KEY, name varchar); to create a table of sighted animals in your DB
6. Type CREATE TABLE endangered(id serial PRIMARY KEY, name varchar, health varchar, age varchar); to create a table of endangered animals
7. Type CREATE TABLE sightings (id serial PRIMARY KEY, animal_id int, location varchar, ranger_name varchar); to create a table that enables locations of sightings to be updated
8. CREATE DATABASE wildlifetracker_test WITH TEMPLATE wildlifetracker; to create a test DB.

**TECHNOLOGIES USED**
1. Java
2. Postgres SQL
3. Spark

**SCREENSHOTS**

file:///home/mark/Pictures/Screenshot%20from%202019-05-02%2012-39-27.png

**SUPPORT & CONTACT DETAILS**

For additions on the project or to work with me you can reach me at markmwago@gmail.com

**LICENSE**

MIT