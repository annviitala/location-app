# Location-app
An application that adds and deletes coordinates and map it out on google map

# Description
1. This app uses angular2+ front-end technology.
2. The user enters values on the input field for latitude and longitude.
3. When add button is clicked, the values are showed on the table and map out to the google map with a marker.
4. Each row corresponding to the latitude and longitude values has a delete button also.
5. When delete button is clicked for a certain row, the entire row is remove from the table and the marker is also remove from the map.


# Direction

1. Install angular 2+ if you don't have yet in you computer.
2. Before installing angular make sure you have node and npm installed already also in your computer.  
3. Open command prompt (cmd) and enter this command:
   
   npm install -g @angular/cli
4. My project file is huge that I only uploaded here my src file. So still in command prompt create a new project directory by entering this command:
   
   ng new my-app
   
   Note: "my-app" is the project name.  You can name whatever you want.
5. The go inside the file folder, in command prompt enter this command:

   cd my-app
 
6. Delete the src file of your newly created project.
7. Download the src file of this app and save it to your project.
8. Open app.module.ts file and change the apiKey with your own google api key which you can get from google.      
   "https://developers.google.com/maps/documentation/javascript/get-api-key"
9. Download the location-api.jar file and save it to your project.
10. In your command prompt enter this command to start your app:

   ng serve –open
   
11. Open your api:
  
    java -jar location-api.jar
    
    Note: Location api can be accessed at "http://localhost:8080/api/locations/"
12. Project can be accessed at "http://localhost:4200/LocationApp".

# License
LICENSE This program is a free software. Redistribution and/or modification is permitted under GNU General Public License v3.0 or any subsequent version.

This program is mainly for educational purposes and does not warrant its fitness for commercial game production capabilities.

# App screenshot
![Alt text](https://github.com/annviitala/location-app/blob/master/app_screenhot.png?raw=true "Optional Title")



