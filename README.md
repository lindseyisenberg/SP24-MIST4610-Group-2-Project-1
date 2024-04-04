# Group-2-MIST-4610-Project-1
# Team name 
21482 Group 2
# Team Members 
Rohan Patel [@rohpat](https://github.com/rohpat)  <br>
Grace Okpurukre  [@graceokpurukre](https://github.com/graceokpurukre) <br>
Lindsey Isenberg [@lindseyisenberg](https://github.com/lindseyisenber)  <br>
Catherine Repke  [yourGitHubNameHere](yourGitHub URL Here) <br> 
Ore Pratt [@nathanp2020](https://github.com/nathanp2020) <br> 
# Problem Description:
Our aim is to build a database for a soccer club through multiple entities with relationships such as many-to-many, recursive, and one to many. The club entity is the heart of our operations as it holds many of the relationships between players, coaches, teams, equipment, etc. Our project displays the relationships between the different entities along with a database that holds information about our operations. Finally, we have written queries that are useful in finding important information about the club.

# Data Model 
Our model displays a database for a Soccer Club. The heart of the operations is the club, which holds information about the name, 
coaches, email, and location. Connected to the club through a one to many relationship is the players table, 
which holds the playerID as the primary key and attributes such as their name and team. 

Next, parents are connected to the players entity through a one to many relationship since parents can have many players 
but a player only belongs to one parent. The soccer club needs information about parents such as their name and 
contact information. Parents also pay the club for their students to participate, which is shown by the one to many 
relationship between parents and financial transactions. Information about transactions needs to be stored such as the fees and amount.

The club also takes donations, so it needs to keep track of the amount and sponsorID. A sponsor can make many donations, 
but a donation can only belong to one sponsor. Also connected to the players table is the Age Division table where one 
age division can have multiple players, and a player can belong to one age division. This entity includes the divisionID, team type,
and location. Also connected to the club entity is the coaches entity, which holds information about coachID, name, and the team they manage. 


<img width="838" alt="image" src="https://github.com/nathanp2020/SP24-MIST4610-Group-2-Project-1/assets/163202597/6ec17357-d417-485b-91fc-1edb1aa46bad">



# Data Dictionary ssets/148125982/760c58c1-7615-4f5b-add8-b42024dcf91b)
![image] 
(images go here)
# Queries 










