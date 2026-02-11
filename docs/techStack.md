# Tech Stack

Fill out the headings below with your Tech Stack information. List the tools and technology you would like to use for your final project. Explain your reasoning for this as well. For example, how does the proposed tool or technology provide value to your overall portfolio of work? 


## Application Design

What tool(s) will you use to create click-through designs of the application? List any UI kits you would like to utilize as well. 


I will use **Figma** to make click through designs (wireframes first, then a nicer version). This helps me plan the pages before I code, so I don’t waste time rebuilding layouts later.  

I love frontend and CSS so based on my figma design I am reayd to impliment all custom CSS. The goal is for the project to look portfolio ready, not like a default template.



## Front End Framework

List your approach for front end development. For example, React is an often used front-end solution for projects in addition to using moduleCSS, PropTypes, and an ESLint style guide.   


I plan to use **React** for the front end because it makes it easier to build the app as reusable compoonents like:

- Login form  
- Trip cards on the dashboard  
- Flight results list  
- Hotel results list  
- Alert settings panel  


## State Management

What is your proposed solution for managing data? This could mean utilizing a database, local-storage, and in general state management libraries for the application (e.g. Redux).    


For state, I’m keeping it simple and realistic:
- **React state** for basic UI stuff (form inputs, filters, dropdowns)
- **Context** for shared app info like the logged in user and auth status
- Store the login token (or session info) in **localStorage** so users don’t get logged out every refresh
- Use the **database** for the real data: trips, tracked items, price history, and alerts  



## Node

Node is often used to serve both an API and to render a front-end. This includes using best practices, npm, and npx. What do you propose? 


I will use **Node.js** so my whole project stays in JavaScript (front end and back end). I’ll use:
- **npm** scripts for running the project (dev, build, test)
- **dotenv** for environment variables (API keys, database connection)
- A clear folder layout so routes and logic don’t get confusing  



## Express

Express is a popular framework to power an API. Describe your idea for building similar functionality offered by express: e.g. middleware, routes, controllers, sending and receiving JSON data.


I will use **Express** to build the API because it makes it easy to:
- Create routes 
- Send and receive JSON cleanly
- Use middleware for things like login protection (only logged in users can see their trips)
- Handle errors in one consistent way (so the app doesn’t crash randomly)



## SQL/Postgres/Sequelize

A popular solution for relational database work is to utilize Sequelize as an ORM. Are you familiar with migrations, models, and seeding? What tools and solutions do you propose for your application? For example, utilizing an ORM to build out models with full validated CRUD.



I know I said MongoDB on our call the other day, but actually I want to use **PostgreSQL** because I use it as work. why complicate my brain with even more? Keeping PostgreSQL seems simpilar to me.  

I’ll use **Sequelize** to make database work easier, and plan to use:
- **Models** 
- **Migrations** 
- **Seeding** 

