# connect-a-web-app-to-database

 # What is Amazon Aurora?
 Amazon Aurora is an relational database service.This means data is stored in rows and
 columns and Aurora specifically is great at handling performance and handling of
 data.
 # How I used Amazon Aurora in this project
 we used Amazon Aurora to connect our web app! This mean we could enter our data
 through browser(loading the web app) and see updates in the backend Aurora
 database.
 One thing I didn't expect in this project was...
 we didnt expect that updating the database manually in the backend would still update
 the table in the frontend(i.e the table that our web app was displaying )

creating a web App

<img width="2090" height="621" alt="Screenshot 2025-08-17 135752" src="https://github.com/user-attachments/assets/842b3a9a-7a4f-4f8a-9082-09cff83447b4" />

 To connect to my EC2 instance, I used a keypair downloaded in my local computer
 and use the key pair details to ssh into the EC2 instance from my local computer
 terminal
 To help me to create web app I first installed PHP mariadb Apache web server php
 mysql. These tools installed helped me to set up web serveer and the ability to my
 webapp and my Ec2 instance to interact with the database

 Connecting my Web App to Aurora
 I setup my Ec2 connection details to my database by creating a new file called
 dbinfo.inc and storing our databse details e.g username ,endpoint,password,database
 name etc.The ec2 instance can refer to this file for connection details.
 
 <img width="1410" height="903" alt="Screenshot 2025-08-17 140427" src="https://github.com/user-attachments/assets/7d464147-3072-4490-8715-1acfe2b06470" />

 My Web App Upgrade
 Next we upgraded our webapp by creating a new PHP file that includes connection to
 a database and light frontened framework that involves that involves submission form
 and a table.
 
<img width="1949" height="1038" alt="Screenshot 2025-08-17 140630" src="https://github.com/user-attachments/assets/cd92321c-92ec-4bbf-be3a-abe9ee045b36" />


























 
