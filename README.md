# **RGUKT E-Store**
RGUKT E-Store is a **web application** built using the **MERN** Stack (MongoDB, Express, React, Node.js). It is designed to allow passed-out candidates or those wishing to sell their educational products (like GATE materials, engineering gadgets, etc.) to junior students. The platform includes both a **user panel** for browsing products and a **admin panel** for managing products.

![Home Page](https://github.com/anandhi3275/E-Store/blob/d5c95cd7a7da6394a6dc4bb961e586dd5341cadf/Home.png)

# Project Overview
The RGUKT E-Store allows users to browse and purchase educational products. The frontend is built with **ReactJs** to provide an interactive and dynamic **user experience**, while the backend is built with **Node.js** and **Express** to handle requests and data management. The data is stored in a **MongoDB database**.

![Store](https://github.com/anandhi3275/E-Store/blob/5c329f5773d225c3113e891ea250121617740353/store.png)

## Features

### Frontend Features
- Browse and search for educational products.
  ![search](https://github.com/anandhi3275/E-Store/blob/5c329f5773d225c3113e891ea250121617740353/search.png)
- Add products to the shopping cart and proceed to checkout.
  ![product](https://github.com/anandhi3275/E-Store/blob/5c329f5773d225c3113e891ea250121617740353/product.png)
- Admin panel for managing products (add, update, delete).
  ![admin panel](https://github.com/anandhi3275/E-Store/blob/5c329f5773d225c3113e891ea250121617740353/admin%20panel.png)

### Backend Features
- Handle user authentication and registration.
- Manage products (CRUD operations).
- Manage users' shopping carts.

## Technologies Used

### Frontend
- **ReactJS**: For building the user interface.
- **React Router**: For handling routing and navigation.
- **Redux**: For state management (cart items, user authentication).
- **Axios**: For making HTTP requests to the backend API.
- **CSS**: For styling the UI.
- **Material-UI**: For pre-styled components in the admin dashboard.

### Backend
- **Node.js**: Runtime environment for the server.
- **Express.js**: Web framework to handle routing and middleware.
- **MongoDB**: Database to store user and product data.
- **JWT (JSON Web Tokens)**: For user authentication and authorization.





### Setup and Installation (Frontend)
Navigate to the frontend directory:
```bash
cd frontend
```
Install the required dependencies:
```bash
npm install
```
Start the development server:
```bash
npm start
```
Open the application in your browser at http://localhost:3000.


### Setup and Installation (Backend)
Navigate to the backend directory:
```bash
  cd backend
```
Install the required dependencies:
```bash
npm install
```
Create a .env file in the root directory with the following content:
```bash
MONGO_URI=<your-mongo-uri>
JWT_SECRET=<your-jwt-secret>
FRONTEND_URL=<your-frontend-url>
```
Start the development server:
```bash
npm run dev
```



