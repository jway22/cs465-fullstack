# cs465-fullstack
CS465 Full Stack Development with MEAN


Architecture

1. Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).
   The frontend development of this project were different in many ways. They were programmed differently and using different frameworks. The customer side (website) of the application was made using Express which allowed for HTML and JavaScript to display information from the database and files in a layout using Handlebars to make the site layout easier to work with. The frontend of the SPA was more involved and required more work from the controller to pass information along as it also included authentication and authorization using JSON Web Tokens to validate user roles. While the SPA still used HTML to create the admin web app, it needed much more organizing with TypeScript to give the app more functionality.
   
2. Why did the backend use a NoSQL MongoDB database?
  NoSQL allows for high scalability so it's easy to add more and more data to the database as needed. It also works well with JSON which allows for information to be passed between quickly.


Functionality

3. How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?
     JSON is able to help pass information. JavaScript is a language that is used in web development to give webpages functionality. JavaScript uses JSON to help pass information between frontend and backend.
   
4. Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.
     In the travel.hbs the code was refactored from listing each available trip to create a loop to display all the available trips. Making code reusable for UI components makes creating pages much more efficient as you can copy/paste lines of code and adjust the names of different elements to fit the new UI as needed, saving time and possibly errors from typos.


Testing

5. Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.
   Methods for HTML include GET, POST, PUT, and DELETE, which match up with the functionality of CRUD, allowing for the creation, reading, updating, and deletion of items within the database. These methods within HTML allow for the passing of information from various endpoints such as the trips endpoints and the login endpoints. This allows for better security as it can help filter where actors are able to go when interacting with the application based on what authorizations they have.


Reflection

6. How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?
   This course has helped give me a better understanding of what's involved with building a full statck application. It helped introduce me to the usage of JSON within a web application as well as frameworks that I haven't used before. I certainly wouldn't say I mastered any skills, as I feel completing my first fullstack application only opens the door to the broader field of software development and there are many areas of improvement. I do think that I've improved my debuggin slightly while creating this project. While I ran into many problems and needed assitance to fix them, I was able to find and solve issues several times on my own by following paths of execution as the app ran to pinpoint what was causing issues.
