# 💼 Fiverr – Freelance Marketplace

A full-stack **Fiverr-inspired freelance marketplace** where users can discover freelance services, create gigs, place orders, communicate with sellers, and leave reviews.

The project recreates the core experience of a modern freelance marketplace with a clean, responsive interface and a RESTful backend.

---

## 🌐 Overview

This project is a full-stack freelance services marketplace inspired by platforms such as Fiverr.

Users can:

* 🔍 Search and explore freelance services
* 🧑‍💻 Browse different service categories
* 📝 Create and manage freelance gigs
* 👤 Create user and seller profiles
* 🛒 Place orders for services
* 💳 Process payments using Stripe
* 💬 Communicate through conversations and messages
* ⭐ Submit and view reviews
* 🔐 Register and authenticate securely
* 📦 Manage orders and gig information

The UI includes marketplace sections such as:

* Graphics & Design
* Video & Animation
* Writing & Translation
* AI Services
* Digital Marketing
* Music & Audio
* Programming & Tech
* Business
* Lifestyle
* Data
* Photography

---

## ✨ Features

### 🔐 Authentication

* User registration
* User login
* JWT-based authentication
* Password hashing with bcrypt
* Cookie-based authentication support
* Protected API routes

### 👤 User Management

* User profiles
* Seller profile information
* Profile picture support
* Country information
* Seller activation
* Seller description

### 🎯 Gig Marketplace

* Browse freelance services
* Create gigs
* View gig details
* Manage gig information
* Search and discover services
* Service categories

### 🛍️ Orders

* Place service orders
* Track order information
* Order management
* Buyer/seller workflow

### 💳 Payments

* Stripe payment integration
* Secure server-side payment processing
* Payment-related order workflow

> Stripe secret keys must always be stored in environment variables and never committed to GitHub.

### 💬 Messaging

* Conversations between users
* Direct messages
* Buyer-seller communication
* Conversation management

### ⭐ Reviews

* Submit reviews
* Display reviews
* Rating-based feedback
* Seller reputation system

### 🎨 UI/UX

* Fiverr-inspired marketplace design
* Responsive layout
* Category navigation
* Hero search section
* Popular services section
* Marketplace exploration
* Fiverr Business section
* Seller registration interface
* Clean typography and spacing

---

## 🛠️ Tech Stack

### Frontend

* HTML
* CSS
* JavaScript
* Responsive UI

### Backend

* Node.js
* Express.js
* REST API

### Database

* MongoDB
* Mongoose

### Authentication & Security

* JWT
* bcrypt
* HTTP cookies
* CORS

### Payments

* Stripe

### Development Tools

* Nodemon
* dotenv
* Git
* GitHub

The backend uses Express with Mongoose and loads configuration through environment variables.

---

## 🔄 Application Flow

```text
             ┌─────────────────┐
             │     Visitor     │
             └────────┬────────┘
                      │
                      ▼
             ┌─────────────────┐
             │ Explore Gigs    │
             │ & Categories    │
             └────────┬────────┘
                      │
                      ▼
             ┌─────────────────┐
             │ Gig Details     │
             └────────┬────────┘
                      │
                      ▼
             ┌─────────────────┐
             │ Authentication  │
             └────────┬────────┘
                      │
                      ▼
             ┌─────────────────┐
             │ Place Order     │
             └────────┬────────┘
                      │
                      ▼
             ┌─────────────────┐
             │ Stripe Payment  │
             └────────┬────────┘
                      │
                      ▼
             ┌─────────────────┐
             │ Communication   │
             │ & Messaging     │
             └────────┬────────┘
                      │
                      ▼
             ┌─────────────────┐
             │ Review & Rating │
             └─────────────────┘
```

---

### 🏠 Homepage

The homepage contains the main marketplace hero section, search functionality, popular service categories, and trusted-brand section.

### 🔎 Explore Marketplace

Users can explore major freelance categories including design, marketing, programming, data, photography, writing, video, and more.

### 💼 Fiverr Business

A dedicated business-focused section highlights professional freelance services for teams and organizations.

### 🧑‍💻 Seller Registration

The seller registration interface allows users to activate their seller account and provide information such as phone number and seller description.

---

## 📁 Suggested Project Structure

```text
fiverr-clone/
│
├── client/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── ...
│
├── api/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   ├── server.js
│   ├── package.json
│   ├── package-lock.json
│   └── .env
│
├── .gitignore
└── README.md
```

---

## 🔒 Security

This project implements several security-related practices:

* Password hashing with bcrypt
* JWT authentication
* Environment-based secrets
* HTTP cookie handling
* CORS configuration
* Protected API routes
* Server-side payment integration

The backend configures CORS with credentials and parses JSON and cookies before registering its API routes.

---

## 🎯 Learning Objectives

This project demonstrates practical experience with:

* Full-stack web development
* REST API design
* MongoDB database integration
* Authentication and authorization
* JWT-based security
* Payment gateway integration
* Marketplace architecture
* CRUD operations
* User-to-user communication
* Git and GitHub workflow
* Responsive UI development

---
