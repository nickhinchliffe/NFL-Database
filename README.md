# NFL-Database
________________________________________________________________________________________________________
Description:
This repository gives the user everything they need to create their own NFL SQL Databse. The Database includes tables for Teams, Record, Head Coach, Player, Staff, Stadium, and Fan. The relationship between the tables can be seen in the following ERD diagram:

![image](https://user-images.githubusercontent.com/56371249/111468958-85d2d700-86fc-11eb-9216-3e6ceff461ff.png)




________________________________________________________________________________________________________
Run: 
1) Must have xampp installed onto your computer (link to install: https://www.apachefriends.org/index.html)
2) Open up XAMPP Control Panel, start both Apache & MySQL
3) Once both servers are started, go to localhost. This will bring you to the XAMPP dashboard
4) In the top right corner of the page, click the "phpMyAdmin" button
5) In the top left column of the next page, click "Databases"
6) From there, you will be able to name and create an empty database. Please name the database "nfldatabase"
7) Once that's complete, go to the SQL tab. In the textarea, all of the SQL code from the CreateTables(DDL) file. Hit 'GO'. This creates the database tables.
8) Next, paste the SQL code in the insertStatements(DDL) to populate the tables. Hit 'GO'.
9) To run SQL queries, past information between labled numbers into the SQL text area. Hit 'GO'. The result of the query/queries will be displayed for you.

________________________________________________________________________________________________________
Demo Video:
https://youtu.be/U1GjXSO5-II

Note: The top score for the leaderboard button are stored in the leaderboard text file. 
________________________________________________________________________________________________________
References:
1. Geeksforgeek: dictionarys, incrementing dictionary values, Python Tnker 
https://www.geeksforgeeks.org/
2. Used to create buttons for the board
https://codereview.stackexchange.com/questions/212699/tic-tac-toe-game-in-python-3-x-using-tkinter-gui-version-2
3. Used for the sytax of the buttons
https://stackoverflow.com/questions/6171493/how-to-set-the-button-sticky-property-properly

________________________________________________________________________________________________________
Team Members:
1) Nick Hinchliffe - Team leader, Network Programmer
2) Justin Alicea - Leaderboard Planner
3) Marcus Kwong - Board and Display Designer
 
