

> Online Market web-application built with the React Redux&MongoDB

HomePage:


![screenshot](https://github.com/MemeBelarusGuy/TechShop/blob/master/HomePage.png)

FullItem:


![screenshot](https://github.com/MemeBelarusGuy/TechShop/blob/master/FullItem.png)

UsersInfo:


![screenshot](https://github.com/MemeBelarusGuy/TechShop/blob/master/UsersInfo.png)

Updating Users:


![screenshot](https://github.com/MemeBelarusGuy/TechShop/blob/master/UpdatingUser.png)

## Features

- Full featured shopping cart

- Product reviews and ratings

- Top products carousel

- Product pagination

- Product search feature

- User profile with orders

- Admin product management

- Admin user management

- Admin Order details page

- Mark orders as delivered option

- Checkout process (shipping, payment method, etc)

- PayPal / credit card integration

- Database seeder (products & users)

### ENV

Create .env file at the same as on the image. There u have to put your mongodb url and paypal id(optional).


![screenshot](https://github.com/MemeBelarusGuy/TechShop/blob/master/env.png)

```

NODE_ENV = development

PORT = 5000

MONGO_URI = your mongodb uri

JWT_SECRET = 'abc123'

PAYPAL_CLIENT_ID = your paypal client id
```
###This is how you mongoDB will look like:

![screenshot](https://github.com/MemeBelarusGuy/TechShop/blob/master/mongo.png)


### Install Dependencies (frontend & backend)

```

npm install

cd ./frontend

npm install

```
### Run project:

```

# Run backend (:5000) & frontend (:3000):

npm run dev //starts backend and frontend


# To run backend and check if your connection working:

npm run server

```
