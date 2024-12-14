# Seek and Shop eCommerce

Seek and Shop is an eCommerce platform built with **React** (frontend), **Spring Boot** (backend), and **MySQL** for database management. It allows users to browse products, add to a cart, and make purchases, while admins can manage product listings.

## Technologies Used:
- **Frontend**: React.js
- **Backend**: Spring Boot, Spring Security, RESTful APIs
- **Database**: MySQL
- **Testing**: Postman

## Setup Instructions

### Frontend:
1. Clone the repo: `git clone https://github.com/yourusername/seek-and-shop.git`
2. Navigate to `frontend` folder: `cd seek-and-shop/frontend`
3. Install dependencies: `npm install`
4. Run React app: `npm start`

### Backend:
1. Navigate to `backend` folder: `cd seek-and-shop/backend`
2. Configure `application.properties` for MySQL.
3. Run Spring Boot app: `mvn spring-boot:run`

### Database:
1. Create a database: `CREATE DATABASE seek_and_shop_db;`
2. Spring Boot will auto-create the necessary tables.

## API Endpoints
- `POST /api/auth/register` (Register user)
- `GET /api/products` (View products)
- `POST /api/orders` (Place an order)

## License
MIT License.
