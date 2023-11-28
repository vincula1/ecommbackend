# E-Commerce Back End

## Overview
This application provides a back-end solution for e-commerce sites, using Express.js API and Sequelize for interacting with a MySQL database. It is designed to meet the needs of internet retail companies seeking to manage their products, categories, and tags efficiently.

## Features
- **Database Models**: Includes models for categories, products, tags, and product tags with defined relationships.
- **CRUD Operations**: Supports create, read, update, and delete operations for each model.
- **RESTful API Routes**: API routes for categories, products, and tags, allowing for data manipulation and retrieval in JSON format.
- **Sequelize Integration**: Uses Sequelize to sync JavaScript objects with a MySQL database.
- **Environment Variable Support**: Implements dotenv for managing sensitive data.

## Installation
1. **Clone the Repository**: 
git clone [https://github.com/vincula1/ecommbackend]
2. **Install Dependencies**: 
npm install
3. **Database Setup**: 
- Use the `schema.sql` in the `db` folder to create your database.
- Set your MySQL username, password, and database name in an environment variable file.
4. **Seed the Database**: 
npm run seed
5. **Start the Server**: 
node server.js

## Usage
- **Database Interaction**: Use Sequelize to interact with your MySQL database.
- **Test API Routes**: Use tools like Insomnia to test API GET, POST, PUT, and DELETE routes.
- **Manage Data**: Easily manage categories, products, and tags data through the API.

## Demonstrations
- **GET Routes**: ![GET Routes Demo](./Assets/13-orm-homework-demo-01.gif)
- **Single Item GET Routes**: ![Single Item GET Routes](./Assets/13-orm-homework-demo-02.gif)
- **POST, PUT, DELETE Routes**: ![POST, PUT, DELETE Routes](./Assets/13-orm-homework-demo-03.gif)

## Walkthrough Video

https://watch.screencastify.com/v/ZvZenmPNEvh4VgCei2Zc