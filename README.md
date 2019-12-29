# The Deadly Sins
**Introduction**
This project aims to create a Cloud-based social media analysis platform to collect tweets using Twitter API and using natural language process methods find the Seven Deadly Sins behind the tweets and explore the association of these deadly sins with real-world scenarios. The main focus of the Seven Deadly Sins in this project are Gluttony and Lust and we will compare these sins with the obesity rates among adults (ages over 18) in Australia national range and the domestic violence incidents in New South Wales. The social media data has been harvested via Twitter API and the scenarios related data have been collected from the Australian Urban Research Infrastructure Network (AURIN).

**User Guide**
After the user opens the webpage, there are two buttons in the middle of the webpage, corresponding to two scenarios, one of which is related to lust and the other is related to gluttony. When the user clicks the button, the webpage will jump to Google Maps. The map will automatically load the data we downloaded from AURIN and the data we got after analyzing Twitter. When the user stops the mouse in a certain area on the map, the relevant data of the area is displayed. There is a checkbox at the bottom of the map. When the user selects an item, the user can see the comparison between the data among all the areas from the map. The user can select up to two items, and the relationship between the two items can be seen on the map.

**Technical Part**
This project is based on academic cloud platform, NeCTAR. The introduction and user guide are on Github (https://github.com/BUBUBIUBIU/Cloud_work). In this project:
*	Responsible for applying ansible to create production environment, including selection of Openstack image, creation of security group, volume and server instances, configuring proxy parameters and tools needed for each instance, building CouchDB cluster and triggering production.
*	Applied docker (including docker swarm, docker compose) to simulate runtime environment for each running python process, monitored the production by visualizer tools.
*	Configured nginx for reverse proxy and load balance.
