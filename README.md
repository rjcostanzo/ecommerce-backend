## Object-Relational Mapping (ORM): E-Commerce Back End

<p align="left">
    <img src="https://img.shields.io/github/repo-size/rjcostanzo/ecommerce-backend" />
    <img src="https://img.shields.io/github/languages/top/rjcostanzo/ecommerce-backend"  />
</p>


This is the backend for an E-Commerce website built using MySQL2, Express, Sequelize, and dotenv.

### Installation

1. Install necessary dependencies (`npm install; npm install mysql2; npm install express; npm install sequelize; npm install dotenv;`)
2. Enter the MySQL shell (`mysql -u root -p`) and sourcing the schema (`source db/schema.sql; quit`).
3. Seed the database by running `npm run seed` in the root directory.
4. Start the database by running `npm start`.

Database Seeding and Initialization
![Database Seeding and Initialization](./demos/db.gif)

Routes Demonstration
![Routes Demonstration](./demos/routes.gif)

