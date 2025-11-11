# 🛍️ Community Marketplace Application

A **Community Marketplace Web Application** built to connect local buyers and sellers in a simple, secure, and user-friendly platform.  
This project is part of our collaborative learning unit — where we design, plan, and develop a scalable marketplace app from scratch.

## 📖 Table of Contents
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Tech Stack](#tech-stack)
4. [UI/UX Design (Figma)](#uiux-design-figma)
5. [Folder Structure](#folder-structure)
6. [Installation & Setup](#installation--setup)
7. [Team Roles](#team-roles)
8. [Branching Strategy](#branching-strategy)
9. [Contribution Workflow](#contribution-workflow)
10. [Future Enhancements](#future-enhancements)
11. [License](#license)

## 🧭 Project Overview

The **Community Marketplace Application** allows users to buy and sell items within their local community.  
It promotes sustainability and community engagement by enabling people to exchange goods directly and securely.

**Core objectives:**
- Enable product listing and browsing.
- Provide an intuitive UI for managing products.
- Facilitate chat between buyers and sellers.
- Prepare for integration with Firestore for dynamic data and image handling.

## ✨ Features

| Feature | Description |
|----------|-------------|
| 👤 **User Authentication** | Users can register, log in, and manage profiles securely. |
| 🛒 **Product Listings** | Create, edit, and delete product listings with images and details. |
| 🔍 **Search & Filter** | Easily find products by category, name, or price. |
| 💬 **Chat System** | Direct communication between buyers and sellers. |
| ❤️ **Wishlist/Favorites** | Save interesting items for later. |
| ⭐ **Ratings & Reviews** | Rate sellers and provide feedback. |
| 🧑‍💼 **Admin Panel** | Admins can view and manage listings. |
| 📱 **Responsive UI** | Optimized for both desktop and mobile devices. |

## 🛠️ Tech Stack

**Frontend:**  
- React.js (with TypeScript)  
- Tailwind CSS  
- React Router DOM  

**Backend:**  
- Node.js  
- Express.js  

**Database:**  
- MongoDB (Mongoose ORM)  

**Tools & Deployment:**  
- GitHub for version control  
- Vercel / Netlify (for frontend deployment)  
- Render / Railway (for backend deployment)  

## 🎨 UI/UX Design (Figma)

Figma wireframes and mockups were created to visualize the key screens and navigation flow.

**Includes:**
- Home Screen  
- Product Detail Screen  
- User Flow Diagram  

🖼️ **Figma Link:** (Add your final design link here once created)

## 📂 Folder Structure

```

community-marketplace-application/
│
├── frontend/                  # React frontend code
│   ├── src/
│   │   ├── components/        # Reusable UI components
│   │   ├── pages/             # Screens (Home, ProductDetail, Profile, etc.)
│   │   ├── assets/            # Images and icons
│   │   └── App.tsx            # Main component
│   └── package.json
│
├── backend/                   # Node.js backend code
│   ├── models/                # Mongoose models
│   ├── routes/                # Express routes (auth, products)
│   ├── controllers/           # Request handlers
│   ├── server.js              # Entry point
│   └── package.json
│
└── README.md

````

## ⚙️ Installation & Setup

### Prerequisites
- Node.js (v18+)
- MongoDB instance or MongoDB Atlas account
- Git installed locally

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/phantom-userrr/community-marketplace-application.git
   cd community-marketplace-application

2. **Setup frontend**

   ```bash
   cd frontend
   npm install
   npm start
   ```

3. **Setup backend**

   ```bash
   cd backend
   npm install
   npm run dev
   ```

4. **Access the app**

   * Frontend runs on: `http://localhost:3000`
   * Backend runs on: `http://localhost:5000`

## 👥 Team Roles

| Team Member      | Role                           | Responsibilities                                                                                        |
| ---------------- | ------------------------------ | ------------------------------------------------------------------------------------------------------- |
| **Manaswini N**  | *Frontend & UI Developer*      | Design and develop the user interface using React + Tailwind CSS. Handle navigation and responsiveness. |
| **Sajit Magesh** | *Backend & Database Developer* | Implement REST APIs using Node.js/Express and manage MongoDB schema and authentication.                 |

## 🌿 Branching Strategy

* **main** → Production-ready, stable code
* **dev** → Integration branch for testing new features
* **feature/frontend** → Frontend development updates
* **feature/backend** → Backend API and database logic

**Commit conventions:**

```
feat: add login functionality
fix: resolve image upload issue
refactor: improve product card layout
```

## 🤝 Contribution Workflow

1. Pull the latest code from `dev`
2. Create a new branch:
   `git checkout -b feature/your-feature-name`
3. Commit changes with clear messages
4. Push branch and open a pull request to `dev`
5. Request teammate review before merging

## 🚀 Future Enhancements

* Integrate Firebase/Firestore for real-time data and image storage.
* Implement secure payment gateway.
* Add push notifications for new chat messages and updates.
* Enable location-based product suggestions.

## 📄 License

This project is open-sourced under the [MIT License](LICENSE).

## 🏁 Summary

This repository represents the foundation of our **Community Marketplace Application**, built collaboratively by
**Manaswini N** and **Sajit Magesh** — focusing on clean UI, maintainable code structure, and real-world functionality.
Our goal is to evolve this into a full-featured community-driven e-commerce app.
