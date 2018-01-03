# How to create a Line chart from database using  ASP.NET
Line and area charts are used to show trends and performance over a period of time. 
    
    Here I had made only a single Line in the graph using the database values based on facebook followers.
    You can make multi lines in the same graph.
    
    
    
 The database creation using sql is given below,
  ----Create a Table named as Follwers----
  CREATE TABLE followers (userid int(11) NOT NULL, facebook int(11) NOT NULL);
  
  ----Insert the values into the Table----
  
INSERT INTO  followers  ( userid ,  facebook ) VALUES
(1, 100),
(2, 60),
(3, 50),
(4, 200),
(5, 89);

After created the database the database access sql is programed in followersdata.php

Js files are use to grap the data and display it.

I have referd some websites and make this Line chart...
