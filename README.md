# CS465-fullstack
CS465 Full Stack Development with MEAN

Brandon Kelfstrom

## Architecture

I used multiple frontend development methods to create this entire web application. 
  These include Express HTML, JavaScript, and Single-Page Application. 
  The client-facing portion of the application utilized Express HTML to build the pages. 
  This allows the pages to be dynamic and editable while maintaining uniformity. 
  Unlike static HTML, Express works with node.js to contain and display items without requiring code changes. 
  JSON files can be used with JavaScript, which allows the program to easily pass database items from the back-end to the front-end. 
  The single-page application is a less fancy way to display information to the site administrators. 
  This is a portal for site changes to be made. 
  In the case of this app, trips were added in an SPA to make the process more efficient than manually accessing the database and adding code for each new trip.
  
The backend used a NoSQL MongoDB database for multiple performance reasons. 
First, NoSQL databases use simple lookup queries with key values which can reduce time spent loading objects. 
This is not a huge benefit when working with a small number of items like what is currently in the project, but it does allow the app to scale without needing additional improvements or optimizations. 
This application could be made to hold hundreds of trips without any necessary changes to hold or access them. 

## Functionality

JSON is a JavaScript Object Notation, which is used by JavaScript programs to store objects. 
JSON can be used to pass objects between the front and back end elements of the application. 
In the case of the Travlr Getaways app, trips are created by administrators, saved to a database, then accessed by the front-end via a JSON file to display on the client. 
  
To improve efficiency, code was changed to be reusable wherever possible. 
  Instead of having every trip contain layout code, a trip-card file was made to hold the layout code, then each trip is called through this code to format it for the website. 

## Testing

In order to test my web application, I used Studio 3T to test the database access on my device. 
  This app visualizes databases and allows the user to make queries to test a database output. 
  To test API endpoints, I used postman. Postman allows you to enter page URLs and check code output by groupings (header, body, etc.). It also allows you to enter values to test page reactions. 


## Reflection

During this course, I learned many valuable things that will help me in my development career. 
  Integration of databases is a very important concept for modern developers, and I had first-hand experience with every step of this. 
  I can now confidently work on any stage of database integration, from initialization to testing. 
  Additionally, I have a much better understanding of how programs work together to enable functions across the internet. 
  This skill can be applied to web design as well as any application that accommodates multiple users on multiple machines either on one network or across multiple around the world. 
