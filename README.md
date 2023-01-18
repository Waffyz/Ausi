# Ausi
### Actually Useful Sales &amp; Inventory

This is a for fun / for learning project that will attempt to implement a web based inventory and sales management product using Docker.

There are no plans currently to integrate it into any kind of platform; the minimum viable product will be a web based tool that a home or craft business could use to account for inventory (or input) costs, product, and invoicing. 



##### Project Roadmap / Tasks 
Immediate needs:

1. Need a database
    * Postgres database
    * PostgresSQL Studio web management (?)


2. Need to write a web app to input data into the database. 

    * App features:
        * Web form for entering data into the database:
            * Static site, simple HTML page with a form. First page will simply link to feature pages (described below).
              -One page per DB table? Per function? EG: Enter Inventory, Create Invoice, etc.
              -Form action will submit the form data to a script that will input into the database. Should have a simple sanity check to assure the data is suitable. EG: All required fields are filled, data types are correct, return the result from the DB (write ok, error?)
        
        * A button to read and display data from each table in the database.
        
        * No filtering at first, just raw data dump to confirm entries.
              -One button per table
              
        
        * Language and web server are undecided. 
            * Caddy and PHP is likely easiest for me, as I have prior experience. Seems like this would be better for prototyping.
            * Python / Flask seems to be a better long term choice but would involve learning Flask. Seems like replicating the site features like this would be a good way to learn. 
            * No consideration at the moment for site design. Ideally it would be something where the CSS and graphics were usable in both. 

##### Todo List:
    * Left blank until next update.
