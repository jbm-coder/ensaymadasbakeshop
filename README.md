# Ensaymadas Bake Shop Website - T3A2-A Assignment
## Jonas Manalang

[Github Repo](https://github.com/jbm-coder/ensaymadasbakeshop)

[Trello Board](https://trello.com/invite/b/ifqhF8wT/ATTIc0db67468b19970c8c07652be3803cc95AA9308B/ensaymadas)

## 1 - Description of your website, including:
- Purpose - Ensaymadas is a home-based bakery specializing in contemporary versions of traditional Filipino breads and cakes. A feat that has earned them considerable recognition. Fueled by positive word-of-mouth endorsements alone, the business has managed to establish steady growth since its inception a year ago. In an attempt to further solidify its success, Ensaymadas has recently taken the plunge into the world of social media platforms utilizing Facebook, Instagram and TikTok. Ensaymadas revenues have already increased as a result of this new web presence. The establishment of a professional e-commerce website for Ensaymadas is the next crucial step in order to consolidate these efforts and maximize Ensaymadas growth potential. With Ensaymadas new e-commerce website, customers will enjoy browsing through Ensaymadas' delightful offerings, place orders seamlessly and make secure payments. Through enabling enhanced customer convenience and expanding brand visibility, the upcoming e-commerce platform is primed to become a vital catalyst in propelling Ensyamada's forward growth and continued success.

- Functionality / Features - The functionality and features of Ensaymadas new e-commerce website are the following:
    - Home Page - The website's home page serves as an enticing introduction to Ensaymadas' products. Through visually appealing cards format that feature the four major products, their descriptions, prices, and a "Add to Cart" button are displayed. The home page creates an immediate visual impact and encourages users to explore further.
    - Products Page - Users are taken to the relevant product page when they click on a certain product card. The product name, description, nutritional information, and extra product photos are all included in this page. Additionally, it has a "Add to Cart" button that enables customers to quickly add the items they want to their shopping basket.
    - Cart Page - The cart page is an important step in the online shopping process. The pricing, quantity, and selected products are displayed along with a summary of the user's order. On this screen, customers can examine their selections, make modifications, and proceed to the checkout process. A calendar with pick-up and drop-off timings is also included. Customers can select the day they want the ordered breads and pastries picked up or delivered. The flexibility and ease of use offered by this functionality enhances the user experience.
    - About Page - There is a about page on the website. The website's "about" page provides a history of Ensaymadas, highlighting its distinctive features and points of differentiation. It emphasises the bakery's dedication to excellence and enthusiasm for creating outstanding Filipino breads and pastries. This page aids in creating a connection with potential customers, trust, and brand identification.
    - User Accounts and Profiles - By enabling the creation of user accounts, people may establish unique profiles for themselves. This feature allows customers to save their order histories, delivery information, and preferred payment methods, simplifying subsequent transactions and enhancing customer convenience.
    - Customer Reviews and Ratings - Customers can leave feedback and ratings for the products they have purchased on the website's reviews page. This encourages trust, provides social proof, and influences potential customers' purchasing decisions.
    - Mobile Responsiveness - The website is totally mobile-friendly, allowing visitors to simply and intuitively explore it on a range of screen sizes. Mobile responsiveness is crucial as more and more consumers browse and make purchases on smartphones and tablets.

- Target Audience - Ensaymadas' primary target market consists of three distinct customer segments:
    - Filipino-Australians - A sizable component of Ensaymadas' target market consists of people with Filipino origin who were born in Australia. They are eager in discovering modern adaptations of traditional Filipino breads because they are interested in learning about and re-connecting with their cultural roots. These patrons value the unique flavour combinations and the way Ensaymadas' menu items honour their Australian background while also paying homage to their Filipino ancestry. The majority of this target audience is technologically aware, thus creating a website will unquestionably help in attracting them and assisting them in finding Ensaymadas.
    - Filipino Immigrant Community in Australia - Ensaymadas understands the value of serving the Australian Filipino immigrant community. Despite having left their homeland, these people nevertheless long for the aromas and memories connected to the country's traditional breads. Ensaymadas wants to generate a sense of nostalgia and provide these clients a flavour of home by providing both genuine, traditional breads and contemporary, high-quality goods. Filipino immigrants typically communicate with one another through word of mouth, so by creating a website, it will be easier for each of them to recommend Ensaymadas to one another. In addition, because they may be new to the country and have no friends, they may turn to online searches when they need something, so by introducing a website, Ensaymadas will help draw in Filipino immigrants seeking a taste of home.
    - Culinary Enthusiasts with an Adventurous Palate - Ensaymadas' delicious selection of modern Filipino breads will sure appeals to customers beyond the Filipino-Australian community. Culinary enthusiasts with an adventurous palate actively seek out unique and authentic food experiences. Ensaymadas provides them with an opportunity to indulge in the rich culinary traditions of the Philippines, offering a captivating journey of flavours and textures. These target customers are typically present online and active on social media. Ensaymadas is in a position to capitalise on any curious audience eager to try something new, broaden their horizons, and experience new things thanks to its present social media channels and the launch of the new Ensaymadas website.

- Tech Stack - The website for Ensaymadas will be developed utilising the MERN tech stack (MongoDB, Express.js, React, Node.js), and it will make use of each component for a certain functionality. The following list breaks down each element's contribution to the creation of the website:
    - React - React is a well-liked JavaScript user interface construction library. The front-end of Ensaymadas' website will be built using it, allowing for the dynamic rendering of web pages. React enables the design of reusable user interface components. In addition to handling user sessions and integrating with JWT for authentication, it will take care of the display of product pages, the ability to utilise a shopping cart, and the front-end user interface, which includes the login and registration pages for user accounts.
    - JWT (JSON Web Tokens) - To enable secure user account authentication and authorization, JWT will be employed. JWT will generate and validate tokens for user sessions to ensure authenticated access to protected routes. JWT will manage user authentication state and permissions throughout the website.
    - Paypal Payment API - Secure online transactions will be made possible through the PayPal payment API. The payment APIs for PayPal will manage transaction verification, ensure the accuracy and security of payment data, and manage payment flows for processing user orders.
    - MongoDB - The data from Ensaymadas' website will be maintained and stored using the NoSQL database MongoDB. This comprises data on products, customers, orders, and other pertinent information. MongoDB's flexibility and scalability enable easy interaction with the rest of the tech stack's elements.
    - Node.js - Node.js will run Ensaymadas' back-end logic of user account creation, authentication and authorization of Ensaymadas' website. Node.js communicates with MondoDB to handle user account data and transactions. Additionally, Node.js integrates seamlessly with Express.js and enables efficient handling of requests, database interactions, and other server-side operations.
    - Express.js - Express.js will manage the server-side logic and serve as a conduit between the database and front end. Express.js will manage routing, take care of HTTP requests and responses, make it easier to get and store data from the MongoDB database. Additionally, Express.js will let the client and server to communicate securely.
    - Heroku (Hosting Platform) - Heroku is a cloud-based platform that makes it simple to deploy and host web applications. Ensaymadas website will be deployed on Heroku, making it accessible to users over the internet. Heroku offers scalability, dependability, and easier hosting infrastructure maintenance.

## 2 - Dataflow Diagram for Ensaymadas Bake Shop.
![Dataflow Diagram](https://github.com/jbm-coder/ensaymadasbakeshop/blob/7bebec9bb2b2071cabeb60f8c1d79753797fba4d/images/Dataflow.png)

## 3 - Application Architecture Diagram
Ensaymadas application architecture follows a client-server model, where the web client communicates with the server through RESTful API calls.The Express back end processes the requests, interacts with the MongoDB database to store and retrieve data, integrates with the Payment Gateway to process secure payments, and makes use of JWT for authentication and authorisation.

![App Architecture Diagram](https://github.com/jbm-coder/ensaymadasbakeshop/blob/91b05f9aa8a1a496564fecdb587ccaf72f8f0702/images/AppArchitecture.png)
#### In the illustration of the architecture:
- The Web Browser represents the client-side interface where users interact with the Ensaymadas website.
- The Web Client manages user interface rendering, user interactions, and sends HTTP requests to the server. It does this by utilising React, HTML, CSS, and JavaScript. Through RESTful API calls, it interfaces with the back end.
- On the back end, routing, middleware operations, and request/response handling are handled using the Express framework, which is powered by Node.js. It links the data layer, payment gateway, and authentication system with the web client. JWT (JSON Web Tokens) is employed for user authentication and authorization. The back end generates and verifies JWT tokens to ensure secure user sessions and controlled access to protected resources.
- Data about users, products, and orders is stored in and retrieved using MongoDB, a NoSQL database. It offers the Ensaymadas application dependable and scalable data persistence.
- The payment gateway is shown as a separate component that communicates directly with the back end. Secure transactions are ensured by the payment gateway, which also handles authorisation and payment processing.Through the Payment API, the back end interfaces with the payment gateway, enabling the necessary data to be transferred between the application and the payment gateway. The back end, implemented using Node.js and Express, interacts with the user database (MongoDB) for data access and performs additional processing as needed. The payment process is started by the web client (front end) by making a request to the back end. The back end, in turn, communicates with the payment gateway, handles the payment-related operations, and sends the response back to the web client.  By maintaining the payment gateway integration on the back end, sensitive payment information is safeguarded and security is preserved.

## 4 - User Stories
As a first-time visitor I want to easily navigate through the website to quickly find and learn about the various kinds of Filipino bread and cakes offered at Ensaymadas. Once I have found what I want, I should be able to make an easy purchase.

Features:
- The website must be modern, with simple and intuitive navigation so that first-time visitors can easily explore and find the various types of Filipino bread and cakes available at Ensaymadas.
- The website should feature a prominent "Sign Up" or "Create Account" button in the header or navigation so that new users can quickly sign up.
- To make it simple for a new visitor to find and browse various sorts of Filipino bread and cakes, the navigation should have product categories or sections with clear labelling.
- Every product should have a thorough product page with images, descriptions, pricing, and nutritional information, giving the first-time visitor all the information they need to make an informed selection.
- The website should include an prominent "Add to Cart" button on every product to make purchase simpler. This will make it simple for a new visitor to add items to their cart.
- The website will also need a prominent "Checkout" button/page, which will direct the first-time visitor to a simple and streamlined checkout process with few steps for a quick and easy purchase.
- After making a purchase, the website should display a clear confirmation message with order details and an option to track the order status.

As a returning customer I'd want a personalized user account where I can store my delivery preferences, manage my payment details, track my order history and save my favourite orders.

Features:
- The website will allow users to create user accounts with personalised profiles in order to securely save delivery preferences and payment information.
- Within the user account, the website will have an order history feature, allowing customers to conveniently track and examine previous transactions.
- Returning customers will be able to save their favourite or often ordered items for faster reordering using the ensaymads user function.
- Within the user account, customers will be able to manage and update their saved payment details within their user accounts.

## 5 - Wireframes for multiple standard screen sizes, created using industry standard software

## 6 - 	Screenshots of your Trello board throughout the duration of the project

Starting Trello Board, Project Management and Brainstorming
![Trello Board 1](https://github.com/jbm-coder/Ensaymadas-Assignment/blob/553cf1fbf13422022f89741b6f613fc11eb83914/Images/Trello1.PNG)

Breaking down R1 into micro task to better focus and complete the question.
![Trello Board 1.1](https://github.com/jbm-coder/Ensaymadas-Assignment/blob/553cf1fbf13422022f89741b6f613fc11eb83914/Images/Trello2.PNG)

Working on R2 and progress screenshot of Trello Board
![Trello Board 2](https://github.com/jbm-coder/ensaymadasbakeshop/blob/7bebec9bb2b2071cabeb60f8c1d79753797fba4d/images/Trello3.PNG)

