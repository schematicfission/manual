Manual
======

A user guide of how to use the tool:

Table of Content

1. Introdution
2. Login
3. Importing Data
4. The Query Browser
4. Wrangling Data
5. Inferring Functional Dependencies
6. Normalizing Data
7. SQL Export
8. References

The following is the manual:

Introduction
-----
1. Schematic Fission lets you turn CSV data into realtional data, which you can choose to keep in database or export to your own database.
2. You can use schematic fission on our servers, or on your own deploy using Maven

Login
----
1. To login, type your login credentials in the main screen.
2. If you are a new user, type in a new username and password in the boxes. If the user exists, this will not be allowed. 
3. Upon registration, you will be given an empty database on the server.

Importing Data
----
1. Use the import function to bring CSV data into the database. Do not use this function if your data is still messy - the "wrangle data" function is made just for this.
2. Once you have selected your file, click "import" to bring all the data into the database.
3. Your imported data should appear on the list on the left.
4. Settle bug to note - uploading a messy CSV file here will quitely fail - use the Wrangle Spreadsheet Data feature to do this.

The Query Browser
----
The main window of Schematic Fission is a query browser - letting you explore your database.
1. In the left part of thw window you will see all your tables.
2. Click on a table to show its content on the right, in the query window.
3. Under where your data is displayed you are able to type a query. Click run to run the query and see the result in the query browser.

Wrangling Data
----
In order to wrangle data, click on the "Wrangle Spreadsheet Data" option in the menu, which will let you upload a messy CSV file.

For the use of Wrangler - refer to [Data Wrangler](http://vis.stanford.edu/wrangler/).





