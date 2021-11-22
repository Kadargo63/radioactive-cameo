
  # Project Title
  E-Commerce Backend
   [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

  # Description
  Reconfiguring a working Express.js API to use Sequelize to interact with a MySQL database.

  # Table of Contents 
  * [Installation](#-Installation)
  * [Usage](#-Usage)
  * [License](#-Installation)
  * [Questions](#-Contact-Information)
      
  # Installation
  To get started clone this repository using 
<br>
```terminal
git clone git@github.com:Kadargo63/radioactive-cameo.git
```
Both Node.js and MySQL must be installed on your computer.

Install dependencies 
```terminal
npm init --y
``` 
```terminal
npm install express sequelize mysql2
```
Open up MySQL shell and input 
```terminal
source db/schema.sql
```
and 
```terminal
use ecommerce_db
```
Then quit MySQL shell and input the following in your terminal
```terminal
npm run seed
```
to start running application simply input 
```terminal
node server.js
```
Open up Insomnia core to GET, POST, PUT and DELETE from different routes.
  
  # Usage
  This application is used to GET data for each route (categories, products, or tags) as well as create, update, and delete data in those routes
  
  # License 
  MIT
  * As this license list was not comprehensive, if you need another license, use the contact  information below to ask for license to be added. 
  
  # Contact Information 
  * GitHub Username: Kadargo63
  * Contact Email: Robertisaacs87@yahoo.com
  
  
