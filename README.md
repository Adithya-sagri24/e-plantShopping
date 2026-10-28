# Paradise Nursery Shopping Application

Welcome to **Paradise Nursery** — an e-commerce web application for plant enthusiasts where green meets serenity! This project was built using React and Redux Toolkit as part of the Coursera / IBM Front-End Web Development curriculum.

---

## 🌿 Project Overview

Paradise Nursery is an intuitive, responsive online plant store designed to help users explore, select, and purchase a variety of houseplants. The application features a clean landing page, categorized plant collections, dynamic cart updates with real-time total calculations, and seamless navigation.

---

## ✨ Features

- **Landing Page**:
  - Welcoming hero section with company branding and tagline *"Where Green Meets Serenity"*.
  - An **About Us** section introducing the mission, expertise, and plant offerings of Paradise Nursery.
  - A prominent **Get Started** button transitioning users directly to the plant catalog.

- **Product Catalog (ProductList)**:
  - Houseplants thoughtfully organized into multiple categories:
    - *Air Purifying Plants*
    - *Aromatic Fragrant Plants*
    - *Insect Repellent Plants*
    - *Medicinal Plants*
    - *Low Maintenance Plants*
  - Each plant item displays a high-quality thumbnail image, plant name, description, and unit price.
  - Interactive **Add to Cart** buttons that add items to the cart, disable themselves upon being added, and update button state to *"Added to Cart"*.
  - Sticky navigation bar present on both catalog and cart views with direct links to **Home**, **Plants**, and the shopping **Cart**.
  - Cart icon with a dynamic badge reflecting the total quantity of items currently selected.

- **Shopping Cart Management (CartItem & CartSlice)**:
  - Centralized global state management using **Redux Toolkit** (`CartSlice.jsx`).
  - Itemized cart listing displaying thumbnail, plant name, unit price, and subtotal per plant.
  - Increment (`+`) and decrement (`-`) quantity controls with dynamic price and count updates.
  - Automatic removal of item if quantity decrements below 1, or explicit removal via the **Delete** button.
  - Dynamic **Total Cart Amount** calculation across all items.
  - **Continue Shopping** button returning users to the plant catalog without losing state.
  - **Checkout** button alerting users with *"Coming Soon"*.

---

## 🛠️ Tech Stack

- **React 18** (Functional Components, Hooks)
- **Redux Toolkit & React-Redux** (Global State Management)
- **Vite** (Next-generation front-end tooling)
- **HTML5 & CSS3** (Responsive design, CSS Flexbox & Grid)

---

## 🚀 Getting Started

### Prerequisites

Ensure you have [Node.js](https://nodejs.org/) installed (version 16 or later recommended).

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/e-plantShopping.git
   cd e-plantShopping
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the local development server:
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to the local server URL (typically `http://localhost:5173/shoppingreact` or `http://localhost:5173/`).

---

## 📁 Project Structure

```text
├── public/
│   └── vite.svg
├── src/
│   ├── assets/
│   ├── AboutUs.css
│   ├── AboutUs.jsx
│   ├── App.css
│   ├── App.jsx
│   ├── CartItem.css
│   ├── CartItem.jsx
│   ├── CartSlice.jsx
│   ├── index.css
│   ├── main.jsx
│   ├── ProductList.css
│   ├── ProductList.jsx
│   └── store.js
├── index.html
├── package.json
├── README.md
└── vite.config.js
```

---

## 📄 License

This project is licensed under the MIT License.
