# SaleSquare E-Commerce Platform

## Overview

SaleSquare is a comprehensive e-commerce platform developed as a course project for Design Practices (COP290) under the guidance of Prof. Abhilash Jindal at IIT Delhi. The project aims to create a versatile online marketplace that enables users to both buy and sell products across various categories.

Hosted at IITD Intranet.

## Tech Stack

- **Frontend**: HTML, CSS, JS
- **Backend**: Flask (Python)
- **Database**: MySQL
- **Authentication**: Flask-Login
- **Form Handling**: Flask-WTF
- **Security**: Werkzeug password hashing

## Key Features

- User authentication (signup, login, logout)
- Product management across multiple categories
- Shopping cart functionality
- Order processing
- Address management
- Product image uploads
- Multilingual product description translation

## Core Functionality

- Supports product categories: Electronics, Beauty, Fashion, Home & Kitchen, Sports, Books
- Users can add, view, and delete products
- Provides complete e-commerce workflow from product browsing to order placement
- Implements secure user authentication and session management
- Allows users to manage personal profiles and addresses
- Includes a search functionality across products

## Database Structure

- Multiple databases for different purposes:
  - `salesquaredb`: Main product and user information
  - `cart`: User-specific shopping cart
  - `orders`: User order tracking
  - `supplies`: Seller order management
  - `address`: User address storage
  - `orderinfo`: Detailed order information

## Notable Technical Implementations

- Dynamic table creation for each user
- Secure password hashing
- Microsoft Translator API integration for product description translation
- Comprehensive error handling and user feedback
- Modular route handling for different e-commerce operations
