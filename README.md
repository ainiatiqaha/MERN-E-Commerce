# MERN E-Commerce Application

## Overview

This project is a full-stack e-commerce application built with the MERN stack. It provides two main functionalities:

1. **Buyer Features**: Buyers can register, browse the marketplace, and interact with products across various categories.
2. **Admin Features**: Admins can manage products, categories, and customer accounts.

## Getting Started

### Prerequisites

- **Node.js**: JavaScript runtime environment for server-side development.
- **React.js**: A JavaScript library for building user interfaces.
- **MongoDB**: NoSQL database for data storage.
- **Express.js**: Web framework for handling routing and requests.
- **Mongoose**: Object Data Modeling (ODM) library for MongoDB and Node.js.

### Installation

To get started, clone the repository to your local machine. Before running the application, you need to set up a database and collection, and configure the database URI.

#### Clone the Repository

Clone the repository using the following command:

```bash
git clone https://github.com/ainiatiqaha/MERN-E-Commerce.git
cd MERN-E-Commerce
```

#### Setup Steps

1. **Create a MongoDB Database**:
   - Go to the [MongoDB website](https://www.mongodb.com/).
   - Create a new database and a collection named `Items`.
   - Insert sample data from the `server/ItemsCollection.js` file as a document in the `Items` collection.

2. **Create an `.env` File**:
   - In the `server` folder, create a new `.env` file.
   - Add the following environment variables to the `.env` file:

   ```plaintext
   NODE_ENV=development
   PORT=5005
   MONGO_URI=mongodb+srv://<your-mongodb-uri>
   ```

### Running the Application

To run the application locally, follow these steps:

1. **Start the Frontend**:
   - Navigate to the `client` directory:
     ```bash
     cd client
     ```
   - Start the React development server:
     ```bash
     npm start
     ```

2. **Start the Backend**:
   - Navigate to the `server` directory:
     ```bash
     cd server
     ```
   - Start the backend server using Nodemon:
     ```bash
     npm run dev
     ```

   **Tip**: Use a split terminal setup to run both the frontend and backend servers simultaneously, allowing you to monitor both processes easily.

## Technologies Used

- [Node.js](https://nodejs.org)
- [React.js](https://reactjs.org/)
- [Express.js](https://expressjs.com/)
- [Mongoose](https://mongoosejs.com/)
- [Material-UI](https://mui.com/)

