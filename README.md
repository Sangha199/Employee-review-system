# 📦 Ecommerce Product Management API
![GitHub license](https://img.shields.io/badge/license-MIT-green)
![Node.js](https://img.shields.io/badge/Node.js-18.x-brightgreen)
![MongoDB](https://img.shields.io/badge/MongoDB-%2347A248?logo=mongodb&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?logo=express&logoColor=white)
![Postman](https://img.shields.io/badge/Tested%20with-Postman-orange)


A simple RESTful API for an eCommerce platform’s admin panel to manage product inventory. Built using Node.js, Express.js, and MongoDB.

## ✨ Features
* ➕ Add new products to the database

* ✏️ Update existing product details

* ❌ Delete products from the inventory

* 📄 JSON-based request and response structure

## 🛠️ Tech Stack
* Node.js

* Express.js

* MongoDB

* VS Code

* Postman

## 🚀 Getting Started
### Prerequisites
* Node.js and npm installed

* MongoDB installed and running locally or use MongoDB Atlas

### Installation
1. Clone the repository:<br>
git clone https://github.com/your-username/ecommerce-api.git<br>
cd ecommerce-api
2. Install dependencies:<br>
   npm install
3. Set up your MongoDB URI in a .env file:<br>
  MONGO_URI=your_mongo_connection_string
4. Start the server:<br>
  npm start

#### The API will be running on http://localhost:5000

## 📬 API Endpoints
| Method | Endpoint           | Description          |
| :----- | :----------------- | :------------------- |
| POST   | /api/products      | Add a new product    |
| GET    | /api/products      | Get all products     |
| GET    | /api/products/\:id | Get product by ID    |
| PUT    | /api/products/\:id | Update product by ID |
| DELETE | /api/products/\:id | Delete product by ID |

## 📖 API Testing
* Use Postman to test all API routes.

* Send JSON data in request bodies for POST and PUT requests.

## 📌 Future Improvements
* User authentication and authorization

* Product image upload support

* Search and filtering functionality

* Pagination for product listings

## 📄 License
This project is open source and available under the MIT License.






  
   


