# SignalR-Push-Notification

The Repository is a Demo Project for the features SignalR and Push Notification of C# and Angular. 

# How to Execute all the 3 Projects 

# Versions to be Followed for all 3 Projects 

1) Node Version 14.18.1
2) NPM Version 6.14.15
3) Angular Version 7.3.9

# Project 1: Version 1.0.0 Sugnal R.zip

This is the first version of Repo. It having only one feature of Signal R. 
Signal R is used for Sending Notification or messages from one server to multiple clients at a same time. 

Step 1) Open the folder or clone the folder in visual studio 2022 

Step 2) Double click on SignalRApp.sln 

Step 3) Once SignalRApp.sln is opened go to Build option and buld the solution 

Step 4) Alternative for step 3. Once SignalRApp.sln is opened use short cut key Ctrl + Shift + B

Step 5) Once you got Build Successful Message. You can run the solution. 

Step 6) On Browser https://localhost:7181/ will be open. This is a Server 

Step 7) Go to Version 1.0.0 Sugnal R -> WPFClient -> bin -> Debug -> net6.0-windows folder 

Step 8) In this location you will find the WPFClient file which is of application type. 

Step 9) Open that file by double clicking 

Step 10) Now the connection is establish between server and client 

Step 11) You can perform the chatting from server to client or client to server 

Step 12) For Group Chat ( chat with Multiple Client ) open WPFClient application file for multiple times. 


# Project 2: Version_1.0.1_Signal_R_and_Push_Notification.zip

Step 1) Open the backend folder in Visual Studio 2022

Step 2) Open SignalRNotificationR.sln file 

Step 3) Build the solution and run the same. 

Step 4) Open Front End folder in Visual Studio Code 

Step 5) This is an Angular code for frontend 

Step 6) Use below commands for execution 

            npm install 
            ng serve --open 
            
Step 7) Now the connection is establish between server and client 


# Project 3: Version 1.0.2 Signal R and Push Notification to Specific Person.zip 

Step 1) Open the folder in Visual Studio 2022 

Step 2) Double click on SignalRDemo.sln file 

Step 3) Use Short cut key Ctrl + Shift + B for build solution operation 

Step 4) Run the Solution 

Step 5) Go to the bellow links only for correct execution 

             http://localhost:65123/Home/User   (This is for clients )

             http://localhost:65123/Admin/SendToSpecificUser   (This is for Server )

Step 6) Provide details in server side and execution is completed. 

# Project 4: Version 1.0.3 Signal R Group Message and Push Notification.zip 

Step 1) Open the project in Visual Studio 2022 

Step 2) Double click on  chat app.sln

Step 3) Use Short cut key Ctrl + Shift + B for build solution operation 

Step 4) Run the Solution 

Step 5) In browser https://localhost:44341/ will be opened 

Step 6) Open the same localhost in multiple browser and you can execute Group chat for public and Private. 

Step 7) Also, you can observe the chat are displayed as an notification. 

# Test.zip 

1) This folder is for testing all the SignalR and Push Notification projects 

2) Platform used for Testing is K6 

3) To execute perform the foloowing Command 

4) Go the Folder 

k6 run --vus 10 --duration 30s file_name.js 

In this command you can edit the number of virtual uses and duration as well. 
