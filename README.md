# Restaurant Menu App

## Problem Statement
The **Restaurant Menu App** is an interactive web application for managing a restaurant's menu. It allows users to view the menu, select food items, add them to the cart, place an order, and view the current order status. The app features dynamic rendering of food items, a search functionality, user authentication, and a responsive design that adapts to different screen sizes. Additionally, the app includes an **"About Us"** section and integration with **local storage** for cart management.

## Features

### 1. **Landing Page**
- **Responsive Layout**: Built using **CSS Grid** and **Flexbox**, ensuring the page adjusts well on different screen sizes.
- **Hero Section**: Includes a visually appealing banner with navigation to key sections like the **menu**, **registration**, and **order** pages.

### 2. **User Registration (Sign-in/Sign-up)**
- **User Registration**: Users can **sign up** and **sign in** to the system, storing their details securely.
- **Responsive Design**: User registration forms are styled using **CSS**, ensuring compatibility across devices.

### 3. **Menu Page**
- **Category-Wise Display**: Food items are organized into categories (e.g., **Starters**, **Mains**, **Desserts**, **Beverages**).
- **Dynamic Rendering**: Menu items are displayed dynamically using **JSON** data, allowing easy updates and scaling of the menu.
- **Grid Layout**: The menu page uses **CSS Grid** or **Flexbox** to layout food items and categories effectively.

### 4. **Food Item Details Page**
- **Food Description**: Users can view detailed information about each food item, including ingredients, description, and price.
- **Recommendation Section**: Displays recommended items based on user interaction, using **CSS transitions** and **hover effects** for interactivity.

### 5. **Add to Cart Feature & API Integration**
- **Cart Management**: Users can **add items** to the cart, **update quantities**, and **remove items** using **JavaScript**.
- **API Integration**: The app integrates with a mock restaurant API to dynamically fetch menu data.
- **Local Storage**: Cart items are stored in **local storage**, ensuring the cart persists across page reloads.

### 6. **Search Functionality & Place Order**
- **Search Bar**: Users can filter food items by typing keywords, dynamically filtering results 
- **Place Order**: Once users have selected their items, they can click a **"Place Order"** button. A modal prompts the user to enter their **seat number**, and a success message appears after the order is placed.

### 7. **Order History & About Us Section**
- **Current Order Status**: Users can view the status of their current order (e.g., "In Progress", "Out for Delivery").
- **Order History**: Displays past orders and their details.
- **About Us Section**: Includes information about the restaurant, images, and testimonials. A feedback form allows users to leave reviews.

### 8. **Deployment & Cloud Integration**
- **Deployment on Vercel/Netlify**: The app is deployed on cloud platforms like **Vercel** or **Netlify** for live hosting and easy access.
- **GitHub Integration**: The source code is hosted on **GitHub** for version control and collaboration.
- **QR Code Generation**: Generates a **QR code** for easy access to the live website, making it mobile-friendly.

## Technologies Used
- **HTML/CSS**: For building the structure and styling the pages.
- **JavaScript**: For dynamic functionality, such as cart management, user interactions, and API integration.
- **Bootstrap**: For responsive design and layout components.
- **API Integration**: Fetching menu data using **JavaScript Fetch API**.
- **Local Storage**: For persisting cart items and user session data.
- **Nodemailer**: For sending emails (e.g., order confirmation).
- **Vercel/Netlify**: For deploying the app live.

