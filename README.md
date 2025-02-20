
# Backend Challenge - Inventory Management Application

## Introduction

The "Inventory Management Application" challenge is designed to build a RESTful API that allows management of products, categories, orders, and potentially user accounts.

### Objectives

- Set up a web server capable of handling API requests.
- Implement endpoints for CRUD operations on products, categories, and orders.
- Handle inventory management (e.g., stock tracking, order fulfillment).
- Understand HTTP methods (GET, POST, PUT, DELETE) and status codes.

### Instructions

1. **Objective**: Develop a side-application that provides functionality for an advanced inventory management platform.

2. **Environment Setup**:
   - NodeJS (latest stable version) (https://nodejs.org/en/download)
   - Use TypeScript language (https://www.typescriptlang.org/)
   - Use NestJS framework for building RESTful API (https://nestjs.com/)
   - Use Postman to create mocks / test your service (https://www.postman.com/downloads/)
3. **Implementation Details**: 
   - Define endpoints for products (`/products`), categories (`/categories`), and orders (`/orders`):
     - `GET /products`: Retrieve all products.
     - `POST /products`: Create a new product.
     - `GET /products/{productId}`: Retrieve details about a specific product.
     - `PUT /products/{productId}`: Update an existing product.
     - `DELETE /products/{productId}`: Delete a product.
     - `GET /categories`: Retrieve all categories.
     - `POST /categories`: Create a new category.
     - `GET /categories/{categoryId}`: Retrieve details about a specific category.
     - `PUT /categories/{categoryId}`: Update an existing category.
     - `DELETE /categories/{categoryId}`: Delete a category.
     - `GET /orders`: Retrieve all orders.
     - `POST /orders`: Create a new order.
     - `GET /orders/{orderId}`: Retrieve details about a specific order.
     - `PUT /orders/{orderId}`: Update an existing order (e.g., change order status).
     - `DELETE /orders/{orderId}`: Cancel an order.
   - Implement logic to interact with product, category, and order data (e.g., store in database, manage stock levels).
   - Include fields such as product name, description, price, category associations, and order details.
   - Utilize database operations (e.g., CRUD operations) to store and retrieve data related to products, caregories, and orders.

4. **Testing**: Test your API using a HTTP client (e.g., Postman, curl).
   - Create, update, and delete products.
   - Add products to the shopping cart, place orders, and verify order status updates.
   - Test payment initiation and confirmation workflows.
   - Ensure API responses include appropriate status codes and error handling for edge cases.

### Possible Improvements

- **Endpoint definitions**: Build OpenAPI specifications to define and describe endpoints.
  - Use **Orval** to generate TypeScript models off specifications and utilise them in the solution to perform your API requests and responses - https://orval.dev/
- Implement unit testing for your service via https://docs.nestjs.com/fundamentals/testing
- **Performance Optimization**: Optimize API performance with caching strategies, database indexing, and asynchronous processing for heavy operations.
**Authentication**: Secure API endpoints, especially those involving sensitive operations like creating, updating, or deleting products, categories, or orders.
- **Error Handling**: Enhance error messages and responses for invalid requests or when data is not found.

## Conclusion

By completing this challenge, you will gain practical experience in developing an Advanced Inventory Management API and learn essential practices for backend development in the context of inventory platforms. Explore additional improvements and challenges to further enhance your skills.

Happy coding!
