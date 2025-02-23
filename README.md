<h1 align="center">Agroic - Reforming Agri Living <br /></h1>  
<p align="center">
  <img src="https://user-images.githubusercontent.com/49508237/104348350-a5485a80-5527-11eb-854b-b2477bfeb96d.png?" width="500" >
</p>

## 🌱Agricultural Web Application for University Project Built with Reactjs + Expressjs + Nodejs + MongoDB (MERN)💻

## Features

- ChatBot
- Seller Profile
- Add/Delete Products
- Edit Profile
- Add/Edit Personal & Company Address
- Farmer Profile
- Add/Delete Grains
- Edit Profile
- Add/Edit Address
- Buy Seeds/Pesticides or Rent Machines
- Buy Loan & Credit Card
- Consumer
- Edit Profile
- Add/Edit Address
- Buy Materials From Farmer
- Payapal Gateway
- Cart Page
- Change Quantity
- Remove Product from Cart Page
and much more

## Usage

### ES Modules in Node

Used ECMAScript Modules in the backend in this project. Be sure to have at least Node v14.6+ or you will need to add the "--experimental-modules" flag.

Also, when importing a file (not a package), be sure to add .js at the end or you will get a "module not found" error

You can also install and setup Babel if you would like

### Env Variables

Create a .env file in then root and add the following

```
NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = 'abc123'
PAYPAL_CLIENT_ID = your paypal client id
```
Create a .env file inside frontend and add the following

```
REACT_APP_GOOGLE_KEY = "add google map api key"
```

### Install Dependencies (frontend & backend)

```
npm install
cd frontend
npm install
```

### Run

```
# Run frontend (:3000) & backend (:5000)
npm run dev

# Run backend only
npm run server
```

## Build & Deploy

```
# Create frontend prod build
cd frontend
npm run build
```

### Seed Database

You can use the following commands to seed the database with some sample users and products as well as destroy all data

```
# Import data
npm run data:import

# Destroy data
npm run data:destroy
```



Problem Statement:

Title: Agriculture Based Web Application 

Context:
In the agricultural sector, farmers, consumers, and sellers face numerous challenges due to the fragmented market, lack of information, and absence of a unified platform to trade agricultural products, machinery, and services. Small-scale farmers struggle to reach potential buyers, access quality seeds, fertilizers, and machinery, while consumers find it difficult to source fresh and organic products directly from farms. Moreover, the current methods lack a streamlined communication system between these stakeholders.

Problem:

Farmers often lack access to a comprehensive platform where they can list and sell their products, as well as rent or purchase essential farming machinery.
Sellers face difficulties in showcasing their products and reaching the right audience. They need a platform to manage their inventory efficiently.
Consumers do not have easy access to a trusted platform where they can purchase fresh, organic agricultural produce directly from the farmers, leading to a dependence on middlemen and higher prices.
There is a need for an easy-to-use platform that enables buyers, sellers, and farmers to communicate, buy/sell products, and manage their profiles and addresses efficiently.


Objectives:
Thi application aims to bridge the gap between farmers, consumers, and sellers by providing a unified platform with the following key features:

Farmer Profiles: Farmers can create and manage profiles, list their grains, seeds, and other agricultural products, and update their personal and company addresses.
Seller Profiles: Sellers can manage their profiles, add/edit/delete products, and maintain a company address.
Consumer Profiles: Consumers can manage their profiles, add products to their cart, adjust quantities, and purchase items directly from farmers or sellers.
E-commerce Capabilities: Users can purchase seeds, pesticides, or rent farming machinery. The platform integrates with PayPal for payment processing.
Communication: A chatbot feature (potentially) helps users navigate the platform and solve queries.
Financial Access: Users can explore options to buy loans and credit cards for farming activities.
Cart and Checkout: Consumers can easily manage items in their carts, adjust quantities, and remove products before making a purchase.
Conclusion:
This Application addresses the key challenges of agricultural commerce by creating a marketplace that promotes direct transactions between farmers, sellers, and consumers. This not only empowers farmers by providing them with better market access but also enables consumers to get fresh, organic products while cutting out middlemen. The platform's profile management, and integrated payment gateway simplify the buying and selling process, making it a practical solution for improving agricultural trade efficiency.




- ChatBot
"Seller Profile"
- Add/Delete Products
- Edit Profile
- Add/Edit Personal & Company Address

 "Farmer Profile"
- Add/Delete Grains
- Edit Profile
- Add/Edit Address
- Buy Seeds/Pesticides or Rent Machines
- farmer can check weather on clicking on map

 "Consumer"
- Edit Profile
- Add/Edit Address
- Buy Materials From Farmer
- Cart Page
- Change Quantity
- Remove Product from Cart Page


The purpose of Agri Vision Project is to provide connections between different roles in the agriculture industry. As the farmers are not getting a fair price for their goods because of contractors. This app removes the requirement of contractors for farmers. Farmers can buy their required needs for farming from Sellers and they can also sell their products to the Consumers
