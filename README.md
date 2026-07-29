# Blinkit-Backend
A complete Blinkit/Zepto Backend built using FastAPI, SQLAlchemy, and SQLite. Features include user authentication, product categories, shopping cart, billing with weight-based discounts, payment APIs, order history, stock management, and interactive Swagger UI documentation.
# 🛒 Blinkit / Zepto Backend using FastAPI

A complete grocery delivery backend built using FastAPI and SQLite.

## Features

- User Registration
- User Login
- Categories
- Products
- Product Search
- Product Filter
- Shopping Cart
- Update Cart
- Remove Cart Items
- Bill Generation
- Weight Based Discount
- Need Bag Option
- Payment (Cash/UPI/Card)
- Order History
- Dashboard
- Stock Management
- Swagger Documentation

---

## Technologies Used

- Python
- FastAPI
- SQLAlchemy
- SQLite
- Pydantic
- Uvicorn

---

## Installation

```bash
pip install -r requirements.txt
```

Run

```bash
uvicorn app:app --reload
```

Open

```
http://127.0.0.1:8000/docs
```

---

## API Endpoints

### Authentication

- POST /register
- POST /login

### Products

- GET /categories
- GET /products
- GET /products/search
- GET /products/filter

### Cart

- POST /cart/add
- PUT /cart/update
- DELETE /cart/remove
- GET /cart/{user_id}

### Billing

- POST /bill

### Payment

- POST /payment

### Orders

- GET /orders/{user_id}

### Dashboard

- GET /dashboard

### Stock

- GET /low-stock
- PUT /restock

---

## Database

SQLite

Tables

- Users
- Categories
- Products
- Cart
- Orders

---

## Future Improvements

JWT Authentication

Admin Panel

Image Upload

Wishlist

Coupons

Delivery Tracking

Notifications

Payment Gateway Integration

---

