# Shopping Cart E-Commerce Website

An E-Commerce Website built for selling electronics products online, featuring user authentication, product management, cart functionality, and order processing.

## Features

### Customer Features
- User registration and login
- Browse and search products by categories
- Add/remove items to shopping cart
- Adjust product quantities in cart
- Secure checkout process
- Order history and tracking
- Email notifications for:
  - New user registration
  - Order confirmation
  - Order shipping updates
  - Back-in-stock notifications

### Admin Features
- Product management (Add/Update/Remove)
- Inventory management
- Order processing
- Shipment status updates
- Stock monitoring

## Technologies Used

### Frontend
- HTML
- CSS
- JavaScript
- Bootstrap

### Backend
- Java (JDK 8+)
- JDBC
- Servlet
- JSP

### Database
- MySQL

## Prerequisites

- Git
- Java JDK 8+
- Eclipse EE (Enterprise Edition)
- Apache Maven
- Tomcat v8.0+
- MySQL Server
- MySQL Workbench

## Setup Instructions

### 1. Database Setup
1. Open MySQL Command Prompt or MySQL Workbench
2. Login to MySQL: `mysql -u <username> -p`
3. Execute the SQL queries from: `databases/mysql_query.sql`

### 2. Email Configuration Setup
1. Create/login to a Gmail account
2. Enable 2-step verification at https://myaccount.google.com/security
3. Generate app password at https://myaccount.google.com/apppasswords
4. Save the generated 16-digit password for configuration

### 3. Project Setup
1. Clone the repository
2. Import project in Eclipse EE:
   - File > Import > Git > Projects from Git > Clone URI
   - Enter repository URL
   - Select master branch
3. Update `application.properties`:
   - Set database credentials
   - Configure email settings with app password
4. Build project:
   - Right-click project > Run as > Maven Build
   - Goals: `clean install`
5. Configure Tomcat server
6. Run the project on Tomcat

### 4. Access Application
- Application URL: http://localhost:8080/shopping-cart/
- Default Admin Credentials:
  - Email: admin@gmail.com
  - Password: admin
- Default User Credentials:
  - Email: guest@gmail.com
  - Password: guest

## Database Schema
- Products
- Users
- Orders
- Transactions
- User Cart
- User Demand

## Contributing
Suggestions and project improvement ideas are welcomed!

## Note
The payment integration is for demo purposes only and not connected to any payment gateway.
