# Imizallah ECommerce Website

This is a fully-functional e-commerce website exactly like amazon. I built an e-commerce website using MERN stack (MongoDB, ExpressJS, React and Node.JS).


## Technologies used

- HTML5 and CSS3: Semantic Elements, CSS Grid, Flexbox
- React: Components, Props, Events, Hooks, Router, Axios
- Redux: Store, Reducers, Actions
- Node & Express: Web API, Body Parser, File Upload, JWT
- MongoDB: Mongoose, Aggregation
- Development: ESLint, Babel, Git, Github
- Payment with Paypal and Stripe

## Run Locally

### 1. Clone repo

```
$ git clone git@github.com:imizallah/MERN-Stack-E-commerce-System.git
```

### 2. Setup MongoDB

- Local MongoDB
  - Install it from [here](https://www.mongodb.com/try/download/community)
  - Create .env file in root folder
  - Set MONGODB_URL=mongodb://localhost/imizallahamazon  ***
- Atlas Cloud MongoDB
  - Create database at [https://cloud.mongodb.com](https://cloud.mongodb.com)
  - Create .env file in root folder
  - Set MONGODB_URL=mongodb+srv://your-db-connection  ***

### 3. Run Backend

```
$ npm install
$ npm start
```

### 4. Run Frontend

```
# open new terminal
$ cd frontend
$ npm install
$ npm start
```

### 5. Seed Users and Products

- Run this on chrome: http://localhost:5000/api/users/seed
- It returns admin email and password

- Run this on chrome: http://localhost:5000/api/products/seed
- It creates 6 sample products


### 6. User Login
- Run http://localhost:3000/signin
- Enter admin email and password and click signin
- User can view all products
- User can view single products
- User can Add products to cart
- User can Checkout products
- User make create Orders and make payment with `Paypal` or `Stripe` payment gateways
- User can also track Orders until item is delivered


### 7. Admin Login

- Run http://localhost:3000/signin
- Enter admin email and password and click signin
- View all Orders
- View all User
- Admin can Create Products
- Mark any order as Delivered
- Admin can Edit any Prooduct
- Admin can Delete Products

## Support

- Contact Me: [Sunday, Ishaya](ishayasunday@gmail.com)

## May the source codes be with you::: +-_-+

git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/imizallah/MERN-Stack-E-commerce-System.git
git push -u origin main