# Ensaymadas Bake Shop Website - T3A2-A Assignment
Jonas Manalang

[Ensaymadas Website](https://jbm-coder.com/)

[Github Repo](https://https://github.com/jbm-coder/Ensaymadas-Assignment)

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

## 4 - User Stories

## 5 - Wireframes for multiple standard screen sizes, created using industry standard software

## 6 - 	Screenshots of your Trello board throughout the duration of the project

Starting Trello Board, Project Management and Brainstorming
![Trello Board 1](https://github.com/jbm-coder/Ensaymadas-Assignment/blob/553cf1fbf13422022f89741b6f613fc11eb83914/Images/Trello1.PNG)

Breaking down R1 into micro task to better focus and complete the question.
![Trello Board 1.1](https://github.com/jbm-coder/Ensaymadas-Assignment/blob/553cf1fbf13422022f89741b6f613fc11eb83914/Images/Trello2.PNG)

Working on R2 and progress screenshot of Trello Board
![Trello Board 2](https://github.com/jbm-coder/ensaymadasbakeshop/blob/7bebec9bb2b2071cabeb60f8c1d79753797fba4d/images/Trello3.PNG)

