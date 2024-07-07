# Dynamic E-Commerce

Multivendor MERN-Stack is an ecommerce web application

## Tools and Packages

![mongodb](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)&nbsp;
![expressjs](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)&nbsp;
![nodejs](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)&nbsp;
![reactjs](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)&nbsp;
![redux](https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white)&nbsp;
![react-router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)&nbsp;
![mui](https://img.shields.io/badge/Material--UI-0081CB?style=for-the-badge&logo=material-ui&logoColor=white)&nbsp;
![jwt](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white)&nbsp;
<img src="https://velog.velcdn.com/images%2Fjch9537%2Fpost%2F7f031d06-1270-43ed-a097-f177caef37ba%2Fimage.png" height="28px" width="90px" alt="Node Mailer">
![Stripe](https://img.shields.io/badge/Stripe-626CD9?style=for-the-badge&logo=Stripe&logoColor=white)&nbsp;

## Features

-   Login/Signup User Account
-   Update Profile/Password User Account
-   Reset Password Mail using nodemailer
-   Cart Add/Remove Items | Update Quantities
-   Wishlist Add/Remove Items
-   Products Pagination (Default 8 Products Per Page)
-   Product Search
-   Product Filters Based on Category/Ratings/Price
-   Make Payment using Stripe
-   My Orders (With All Filters)
-   Order Details of All Ordered Item
-   Review Products User Account
-   Register as a seller and list your products
-   Admin: Dashboard access to only admin roles
-   Admin: Update Order Status | Delete Order
-   Admin: Add/Update Products
-   Admin: Update User Data | Delete User
-   Admin: List Review of Product | Delete Review
-   Stock Management: Decrease stock of product when shipped

## Run Locally

Clone the project

```bash
  git clone https://github.com/TAbishek22/Dynamic-Ecommerce.git
```

Go to the project directory

```bash
  cd project
```

Install dependencies

```bash
  cd backend
  npm install
```

```bash
  cd frontend/
  yarn
```

```bash
  cd socket/
  npm install
```

## Environment configurations

set your config.env file : use given format

```
PORT=8000
DB_URI='mongodb_uri'
JWT_SECRET='your jwt secret'
JWT_EXPIRE= 1d
COOKIE_EXPIRE = 7
SMPT_SERVICE=gmail
SMPT_MAIL='your email'
SMPT_PASSWORD='email password'
SMPT_HOST=smtp.gmail.com
SMPT_PORT=587
STRIPE_API_KEY='stripe key'
STRIPE_SECRET_KEY='stripe secret'
```

## Deploying Locally

Start the server

```bash
  cd socket
  npm start
```

```bash
  cd backend
  npm run dev
```

Start the frontend

```bash
  cd frontend
  npm start
```

## UI Screenshot

-   Home UI
    ![alt text](image-1.png)
