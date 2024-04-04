# Group-2-MIST-4610-Project-1
# Team name 
29704 Group 2
# Team Members 
Enzo Vasallo [@enzovasallo](https://www.github.com/enzovasallo)  <br>
Parker Kane  [@parkerkane5](https://www.github.com/parkerkane5) <br>
Kaylie Chin [@kayliechin](https://www.github.com/kayliechin)  <br>
Clint Kitchens  [@clintkitchens](https://www.github.com/clintkitchens) <br> 
Ore Pratt [@nathanp2020](https://github.com/nathanp2020) <br> 
Jazlyn Piedra  [@mjp44773](https://github.com/mjp44773) <br> 
# Problem Description:
The task at hand is to create a relational database for a football club's operations. The central entity in the model is the Team entity, representing the football club itself. The club's operations include player, match, Tickets, and more. We aim to accurately model these relationships, generate sample data, and populate the entities and their attributes with this sample data. Furthermore, we are interested in performing functional queries on this data to gain valuable insights into the club's activities and operations.
# Data Model 
Our data model is structured around the framework of a fictional football club. The central entity in our model is the 'Team' entity, which represents the football club itself. Inside the club, we have various components, including 'Player,' 'Employee,' 'Match,' 'Sponsor,' 'Ticket,' 'Merchandise,' 'Orders,' 'Injury,' 'Payments,' 'Stadium,' and 'Results,' each with its own set of attributes.

We establish relationships between these entities to manage the club's operations effectively. For example, there is a one-to-many relationship between 'Team' and 'Player' to account for the numerous players associated with the club.

Similarly, the 'Coach' and 'Match' entities have their attributes and relationships. The 'Team' entity helps categorize different teams. 'Fan' represents the club's fan base, while 'Sponsor' keeps track of organizations or businesses supporting the club.

'Merchandise' includes details of the club's products, and 'Orders' handles financial transactions like revenue from ticket sales. 'Injury' tracks player injuries, and 'Employee' represents those responsible for evaluating new talent and coaching the team. The 'Stadium' entity provides information about the club's home stadium, and 'Ticket' manages ticketing for matches.

Incorporating these entities and relationships, our data model comprehensively captures the diverse aspects of the football club's operations, allowing for efficient management and analysis, tracking departments, employees, and services for smooth operation. <br>

![image](https://github.com/enzovasallo/Group-2-MIST-4610-Project-1/assets/148125982/36d4ff53-256c-4dbf-a719-597a284b6866)

# Data Dictionary 

![image](https://github.com/enzovasallo/Group-2-MIST-4610-Project-1/assets/148125982/a65a0997-0b9a-43b1-bb44-e6412fef25a0)
![image](https://github.com/enzovasallo/Group-2-MIST-4610-Project-1/assets/148125982/d7f88c72-5bdf-4722-9cbe-41ab11de778b)
![image](https://github.com/enzovasallo/Group-2-MIST-4610-Project-1/assets/148125982/7545ae7a-0383-4ce0-a0db-4ac11b1c1479)
![image](https://github.com/enzovasallo/Group-2-MIST-4610-Project-1/assets/148125982/a484f1a3-b18b-406c-8ba5-6732cfc676e8)
![image](https://github.com/enzovasallo/Group-2-MIST-4610-Project-1/assets/148125982/38547c30-aac2-4753-b429-41f51cf222d5)

![image](https://github.com/enzovasallo/Group-2-MIST-4610-Project-1/assets/148125982/fdc3bdc6-135f-427d-a2b0-cd8603335ad9)

![image](https://github.com/enzovasallo/Group-2-MIST-4610-Project-1/assets/148125982/08540986-7fc1-473a-b467-ece21e3211d4)

![image](https://github.com/enzovasallo/Group-2-MIST-4610-Project-1/assets/148125982/147c6981-435e-4c89-a204-86107e82553d)

![image](https://github.com/enzovasallo/Group-2-MIST-4610-Project-1/assets/148125982/4cf98aa6-e9a8-4831-8a05-a6e1ae44442c)

![image](https://github.com/enzovasallo/Group-2-MIST-4610-Project-1/assets/148125982/77e3d001-5aa8-4a5e-b45a-5a9a05cd63c3)

![image](https://github.com/enzovasallo/Group-2-MIST-4610-Project-1/assets/148125982/8a7afbcf-8f1e-4751-8e59-457fbc7129d4)

![image](https://github.com/enzovasallo/Group-2-MIST-4610-Project-1/assets/148125982/760c58c1-7615-4f5b-add8-b42024dcf91b)

![image](https://github.com/enzovasallo/Group-2-MIST-4610-Project-1/assets/148125982/7d54c920-1a5c-4dcd-8c85-90d0e6814bae)

![image](https://github.com/enzovasallo/Group-2-MIST-4610-Project-1/assets/148125982/e7a03d52-73d4-4403-b949-b7b14acc46d2)

# Queries 

![image](https://github.com/enzovasallo/Group-2-MIST-4610-Project-1/assets/148125982/e8624379-cadd-47f6-acf5-df3c53992e51)

1. List the coach’s name and the names of the players they coach. Order by name (descending).

![image](https://github.com/enzovasallo/Group-2-MIST-4610-Project-1/assets/148125982/edb78d24-e761-4590-bdaf-ae97dd7ef563)

The SQL query to list the coach's name and the names of the players they coach is useful for various reasons, especially in the context of sports management or team organization. It provides valuable insights into the coaching relationships within a sports team or organization. Listing by descending employee name allows a manager to quickly view coaches in alphabetical order and the players under them.

2. List the maximum order amount and the customer who ordered it

![image](https://github.com/enzovasallo/Group-2-MIST-4610-Project-1/assets/148125982/cf5325d5-0bb7-40e4-b5c3-21efca1e8ee0)

This SQL query finds the customer who made the largest purchase (maximum order amount) and provides their name. A manager can use this information to identify their highest-spending customer, tailor marketing efforts, and assess the impact of top customers on their business.

3. List out the number of injuries by type for Atlanta United. Order by number of injuries.

![image](https://github.com/enzovasallo/Group-2-MIST-4610-Project-1/assets/148125982/81494a9d-e070-49c2-9aa7-c58576b75f1d)

This SQL query counts the number of injuries by injury type for Atlanta United. The query provides a breakdown of injury counts by type. It helps a manager analyze injury trends and understand which types of injuries are affecting Atlanta United. This information can be used to develop injury prevention strategies and allocate resources effectively to support Atlanta United with higher injury occurrences.

4. Find the total number of matches played by each team

![image](https://github.com/enzovasallo/Group-2-MIST-4610-Project-1/assets/148125982/cc3c217b-0952-4050-8d74-3a721c647be3)

This SQL query counts the number of matches played by each team and associates the count with the respective team's name. It assists a manager in assessing workload by revealing the number of matches played by each team. This information is valuable for managing team schedules and evaluating team performance over time.

5. List the number of scouts for each team as a percentage of the total number of employees.

![image](https://github.com/enzovasallo/Group-2-MIST-4610-Project-1/assets/148125982/2639015e-3c4b-4b3f-9877-d420651e906e)

This SQL code calculates the percentage of scouts out of the total number of employees. Managers can use this query to gain insights into the composition of their teams, particularly in sports organizations. The scout percentage offers a key metric for assessing the focus on talent scouting within each team. Managers can use this information to ensure that the scouting department is adequately staffed and to compare the scouting efforts across different teams for effective talent acquisition and development.

6. List the teams who are in 1st or 2nd Tier and have at least 95 sponsors. Order by team name alphabetically.

![image](https://github.com/enzovasallo/Group-2-MIST-4610-Project-1/assets/148125982/20da7181-f7e5-454b-9b11-3c9989d8bab9)

This SQL query retrieves a list of teams receiving support from at least 95 sponsors. It provides a clear view of which teams have attracted substantial sponsor support.This information is valuable for recognizing and nurturing key sponsor relationships. Managers can use these insights to develop targeted strategies for engaging and retaining high-value sponsors, contributing to the financial health and success of their teams or organization.

7. List the sponsors who have made donations over $1000 and the teams they are sponsors for, sort by descending amount.

![image](https://github.com/enzovasallo/Group-2-MIST-4610-Project-1/assets/148125982/3ec4d6e0-ef06-497b-9dd1-44ec4b6a0647)

This SQL query retrieves a list of sponsors, their associated teams, and the sponsorship payment amounts. It provides a clear view of sponsors contributing significant amounts (exceeding $1000) to specific teams. This information is valuable for recognizing and nurturing key sponsor relationships, evaluating the financial impact of sponsorships, and determining which teams have attracted substantial sponsor support. Managers can use these insights to develop targeted strategies for engaging and retaining high-value sponsors, contributing to the financial health and success of their teams or organization.


8. List the top 3 most popular merchandise items based on the number of purchases

![image](https://github.com/enzovasallo/Group-2-MIST-4610-Project-1/assets/148125982/4d85711f-16e1-4e18-a455-c7e44edbd788)

This SQL query identifies the top 3 most popular merchandise items by counting the number of purchases for each item and sorting them in descending order. A manager can use this data to optimize inventory, sales strategies, and marketing efforts, ensuring they meet customer demand and enhance overall sales and customer satisfaction.

9. List the Customers that have bought more than 500 dollars worth of merchandise  in addition to having ordered 3 or more times. Order by customer name alphabetically.

![image](https://github.com/enzovasallo/Group-2-MIST-4610-Project-1/assets/148125982/bf220e7d-3170-4d9d-bec8-fc40343521e4)

This SQL query identifies the customers that are big fans and have bought at least 500 dollars worth of merch and 3 or more merch items. A manager can use this data to send these customers a thank you, or send them a discount/coupon for being loyal customers.


10. List the names of players who have never been injured, along with their team names and positions. Only include players that play either “Striker” or “Winger”.

![image](https://github.com/enzovasallo/Group-2-MIST-4610-Project-1/assets/148125982/9fc4737b-8e0c-46d4-aed6-9fca630f1074)

This SQL query compiles a list of players who have never experienced injuries, including their player names, team names, and player positions. This query only includes strikers or wingers, which are mainly attacking positions. Managers can use this information to assess player reliability, optimize resource allocation, and make strategic decisions, ultimately contributing to team performance and player well-being by ensuring a more stable and consistent lineup in terms of team attack.






















