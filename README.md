# CS-465 Module Eight Journal

Architecture

Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).
Why did the backend use a NoSQL MongoDB database?

A.) For starters, Express is a NodeJS framework that is mainly used for server-side web applications by using RESTful APIs. It was used for buildiong the customer sided HTML web pages for the Travlr Getaways webpage. This would function by having the customer navigate the application, the customer would alter something selectable and due to this an input would be read, and the pages would update the server before displaying the changes to the customer.

We then moved onto Angular Framework related modules which would shift us to single-page applications, or SPAs, where by definition tbe HTML is cached on the client-side and only uses the RESTful API for data updates.

The Express HTML showed us bit by bit what the expected look of the webpage would be, and then later more parts were added to the modules, letting the webpage become a fully functioning website capable of dynamically displaying data to the users. This was done through the use of Javascript on both front end and back end for the code, as Javascript is a scripting language that also helps reduce the load on the server.

The SPA was used as the admin site that could authorize users to add, edit, and view trips and would display the associated windows. This is where the SPA excels since it doesn't need the entire page to load, just the parts of data that change. That is why its use is considered a seemless experience.

The backend uses a NoSQL MongoDB database because of its ability to be scaled up, its overall flexibility, and performance compared to its SQL counterparts. Since the website was set up with the SPA in mind to be able to dynamically add more changes to a wesbite, its a perfect fit for a website that continuously makes dynamic changes to its pages such as one where customers alter vacation trips.


Functionality

How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?
Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.

A.) Between JSON and JavaScript, Javascipt is a popular programming language that is used for web development, while JSON is
a data interchange format used for transferring data between front end and back end that derives directly from JavaScript itself (JavaScript Object Notation). JavaScript can essentially read JSON files under its own JS object.

Looking into the build history (since i couldn't get my project to fully function) , the easiest example of this was when the instructions had us finally move from Express to an SPA with Angular. This caused the data issued to be moved from the server over to the client side, which would result in hypothetically faster webpage loading speeds.

Testing

Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.

A.) From my understanding, the launching of the webpage via localhost:3000 for API endpoints would count.

For our project as the example, examples of methods would include GET, POST, and PUT, and DELETE where when used, gather or modify data from the database/backend. This leads to backend functions like .findOne, .find, and .create.

Endpoints are by definition, a specific location within an API that accepts requests and sends back responses. This was tested within our project by using the program Postman which simplifies each step of the API lifecycle so you can create better APIs.

Security was added to the project by adding User Authentication during module 7, where there were restricitons to accessing and modifying the trip details.

Reflection

How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?

A.) Honestly, this course has helped a lot. I was nervous from the beginning and even until now about the contents of the course. Mainly since I never intended to continue coding in my professional career, but instead would appreciate a basic understanding of web and full stack development, which is something I mentioned my first week into this course. I do wish I could've applied myself more as something mid way into the class really capsized at least the visual progress of the Travlr Getaways webpage for me on my end. But that didn't stop me from continuing to do progress via the instructions. I do think I reached my overall goal though, I do think I have a better, if not generic understanding of how webpages are made and how they function, both front end and backend. 

I was able to learn about Angular, SPAs, and how various coding language entangle all that together to manage to spit out a functioning website. Also, the casual web visualization of how Visual Studio Code divides all the features of a webpage was always something I was curious about, like where and how is all that webpage data stored?

I do not think I mastered this course, but I do think that it shed a positive light onto the gap of knowledge I was initially missing.
