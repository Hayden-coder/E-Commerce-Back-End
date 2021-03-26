# E-Commerce-Back-End

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```
## Insatll 
```md
Npm insatll 
Create a env. file and add this code
DB_USER=''
DB_PW=''
DB_NAME='ecommerce_db'

add you're username and password

create a database in MQL with the code from the schema 
now seed the database in the command with this

npm run seed

then 

npm start

Use Insomnia core to GET, POST, PUT or DELETE the data
```
## Link to video
https://drive.google.com/file/d/1s9CoWsKSrY0U5A2NEOnqn32oZkPkWYOe/view

<img width="724" alt="Screenshot 2021-03-25 174909" src="https://user-images.githubusercontent.com/74078719/112561452-7d306f80-8d92-11eb-9691-c27eb1004f18.png">
