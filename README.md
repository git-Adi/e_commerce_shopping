# Flickart - MERN eCommerce Project (Flipkart Clone)

Flickart is a feature-rich eCommerce platform inspired by Flipkart. Built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js), it showcases the functionality and features of a modern online shopping platform.

---

## Table of Contents

- [Test Users](#test-users)
- [Features](#features)
- [Requirements](#requirements)
- [Setup](#setup)
- [Environment Variables](#environment-variables)
- [Contributing](#contributing)

---

## Test Users

### User
- **Email**: `test@test.com`  
- **Password**: `test123`

### Admin
- **Email**: `store@flipkart.com`  
- **Password**: `admin123`

---

## Features

- **User Authentication and Authorization**  
  Secure user registration, login, and JWT-based access control.

- **Product Catalog**  
  Categorized product display and search functionality.

- **Shopping Cart Management**  
  Add/remove products, view/save cart, and proceed to checkout.

- **Secure Payment Processing**  
  Integration with **Stripe** for seamless and secure transactions.

- **User Order History and Management**  
  Order tracking and status updates for user purchases.

- **Admin Panel**  
  Accessible at `/dashboard/admin` for managing products, categories, and orders.

- **Responsive Design**  
  Built with **Tailwind CSS** and **Material UI** for an adaptive user interface.

- **Password Encryption**  
  Uses **bcrypt** for securely hashing passwords.

- **Image Storage**  
  Manages product images with **Cloudinary** for efficient handling.

---

## Requirements

Ensure you have the following installed and ready:

- **Node.js** and **npm**  
- **MongoDB** (local or remote instance)  
- **Stripe API key** (for payment integration)  
- **Cloudinary account** with API credentials  

---

## Setup

### Clone the Repository

```sh
git clone https://github.com/aashish-dhiman/E-Commerce.git
cd E-Commerce
