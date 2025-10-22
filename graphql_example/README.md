# GraphQL Example

## 📦 Overview
This project demonstrates a simple GraphQL server implementation using Node.js and Express.

## 🛠️ Features
- **GraphQL Endpoint**: `/graphql` 
- **GraphiQL Interface**: Accessible at `http://localhost:4000/graphql`
- **City Data**: Provides city data from `UScities.json`

## 🚀 Getting Started
1. Clone this repository
2. Install dependencies with `npm install`
3. Run the server with `node graphserver.js`

## 🔧 Docker Usage
To build and run using Docker:
```bash
docker build -t graphql-example .
docker run -p 4000:4000 graphql-example
```

## 📝 Notes
- The server listens on port 4000
- GraphQL queries can be executed via GraphiQL interface
- City data is loaded from `UScities.json` file

## 📚 Resources
- [GraphQL](https://graphql.org/)
- [Express GraphQL](https://www.npmjs.com/package/express-graphql)
- [Node.js](https://nodejs.org/)