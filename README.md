# Dating App
A simple, secure, and scalable dating website built using Angular and Dot Net. Requires DotNet v3.0.x and Angular 9.

# Key Features
* Real Time Messaging
* Like Users
* Last Seen
* Multiple Photo Uploads
* AI Photo To Face Focus
* Add Interests, Looking For, Personal Details, Etc.
* Great Filters To Find Your Ideal Match

# Setup
Download and Install DotNet v3.0, Angular v9, & SQLite. Then fork & clone this repository onto your computer.

To run in production mode, go to the DatingApp-SPA folder in command prompt/terminal and use the command: *ng build --prod*. Then, go to the DatingApp.API folder and use the command: *dotnet ef database update*. This creates the database. Once that is done, run the command: *dotnet run*. Now, if you go to localhost:5000 on your computer, you should see the DatingApp.

To run in development mode, go to the DatingApp.API folder and run the command *dotnet ef database update* and then *dotnet run*. Then, go to the DatingApp-SPA folder and run the command: *ng serve*. Now, if you go to localhost:4200 on your computer, you should see the DatingApp.