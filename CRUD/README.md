# Microservices Serverless Project - CRUD API

## 📋 Overview
This project demonstrates a simple CRUD (Create, Read, Update, Delete) API using Flask and Python. It's designed to be a foundational example of how to build microservices with serverless architecture patterns.

## 🛠️ Features
- **RESTful API** with Flask
- **CORS support** for cross-origin requests
- **JSON data handling**
- **CRUD operations** for products

## 📦 Dependencies
- Flask
- Flask-CORS
- Python 3.13+

## 🚀 Getting Started
1. Clone the repository
2. Install dependencies using `pip install flask flask-cors`
3. Run the server with `python products.py`

## 🔧 API Endpoints

### GET `/products`
Retrieves all products.

### GET `/products/<id>`
Retrieves a specific product by ID.

### POST `/products`
Adds a new product to the collection.

### PUT `/products/<id>`
Updates an existing product by ID.

### DELETE `/products/<id>`
Deletes a product by ID.

## 📝 Example Usage
```bash
# Get all products
curl http://localhost:5000/products

# Get specific product
curl http://localhost:5000/products/144

# Add new product
curl -X POST -H "Content-Type: application/json" -d '{"name": "Pen", "price": 2.99}' http://localhost:5000/products

# Update product
curl -X PUT -H "Content-Type: application/json" -d '{"name": "Updated Pen", "price": 3.99}' http://localhost:5000/products/144

# Delete product
curl -X DELETE http://localhost:5000/products/144
```

## 📊 Project Structure
```
.
├── products.py
└── README.md
```

## 📈 Version History
- **v1.0.0** - Initial version with basic CRUD functionality
- **v1.1.0** - Added CORS support and improved error handling

## 🛡️ Security Notes
- This project is intended for educational purposes
- It does not implement authentication or authorization
- For production use, consider adding security measures like JWT tokens, input validation, etc.

## 🔗 Resources
- [Flask Documentation](https://flask.palletsprojects.com/)
- [Serverless Computing](https://aws.amazon.com/serverless/)
- [Microservices Architecture](https://microservices.io/)

---

## 🧪 Testing
- [x] Test CRUD operations
- [x] Validate API endpoints
- [x] Verify CORS support

## 📚 Resources
- [Python Flask](https://flask.palletsprojects.com/)
- [Microservices Documentation](https://microservices.io/)
- [Serverless Functions](https://aws.amazon.com/serverless/)