# React-Admin-Dashboard
The application is built using React and utilizes Vite as the development tool. It includes various features such as dark mode/light mode, adding new products and users, viewing user details, transactions, product list and stock, revenue progress bar for the last month, and a revenue graph for the last 6 months. 

## Table of Contents
- [Getting Started](#getting-started)
- [Features](#features)
  - [Dark Mode / Light Mode](#dark-mode--light-mode)
  - [Adding New Products](#adding-new-products)
  - [Adding New Users](#adding-new-users)
  - [Viewing Single User](#viewing-single-user)
  - [Viewing Product List and Stock](#viewing-product-list-and-stock)
  - [Last Month Revenue Progress Bar](#last-month-revenue-progress-bar)
  - [Last 6 Months Revenue Graph](#last-6-months-revenue-graph)
  - [Search](#search)
  - [Notifications](#notifications)
 

## Technologies Used
Admin Dashboard is built using the following technologies:

* React
* HTML (structuring)
* Pure Sass or Scss (styling)
* MaterialUI (Icons and Table)


## Features

### Dark Mode / Light Mode

- **Description**: The application provides a toggle switch to switch between dark mode and light mode themes.
- **Usage**: Click on the toggle switch to switch between the themes.

### Adding New Products 

- **Description**: This feature allows users to add new products to the system.
- **Usage**:
  1. Click on the "Add Product" button.
  2. Fill in the necessary details such as product name, description, price, etc.
  3. Click on the "Save" button to add the product to the system.

### Adding New Users 

- **Description**: This feature allows administrators to add new users to the system.
- **Usage**:
  1. Click on the "Add User" button.
  2. Fill in the required user information such as name, email, role, etc.
  3. Click on the "Save" button to add the user to the system.

### Viewing Single User 

- **Description**: This feature allows administrators to view details of a specific user.
- **Usage**:
  1. Click on the "View User" button associated with the desired user.
  2. The user's details, including name, email, role, etc., will be displayed.


### Viewing Product List and Stock 

- **Description**: This feature allows users to view the list of products and their respective stock levels.
- **Usage**:
  1. Click on the "Product List" button.
  2. A table displaying the products, including product name, description, price, and stock level, will be shown.

### Last Month Revenue Progress Bar 

- **Description**: This feature provides a progress bar representing the revenue progress for the last month.

### Last 6 Months Revenue Graph 

- **Description**: This feature displays a graph


## Screenshots
#### DarkMode Screenshot
![App Screenshot](https://i.ibb.co/Mg6h0C8/admin-Black.png)

#### LightMode Screenshot
![App Screenshot](https://i.ibb.co/f0KDW5N/admin-Light.png)


## Prerequisites
Before starting with the application, the following technologies need to be installed on your system:

* Node.js (version 14 or later)
* NPM (Node Package Manager)


## Installation

1. Clone the repository:

    ```bash
   git@github.com:AJOYSR/ShareMe-Platform-React.git
    ```
#### react app is made by Vite so,

2. Navigate to the project directory:

    ```bash
    cd admidashboard
    ```

3. Install dependencies:

    ```bash
    npm install
    ```
4. run the project:

    ```bash
    npm run dev
    ```

5. Navigate to `http://localhost:5173` in your web browser to view the app.

## Dependencies

This app uses the following dependencies:

    ```
    {
      "name": "admindashboard",
      "version": "0.0.0",
      "dependencies": {
        "@emotion/react": "^11.11.0",
        "@emotion/styled": "^11.11.0",
        "@mui/icons-material": "^5.11.16",
        "@mui/material": "^5.13.0",
        "@mui/x-data-grid": "^6.4.0",
        "react": "^18.2.0",
        "react-circular-progressbar": "^2.1.0",
        "react-dom": "^18.2.0",
        "recharts": "^2.6.2"
      },
      "devDependencies": {
        "@types/react": "^18.0.28",
        "@types/react-dom": "^18.0.11",
        "@vitejs/plugin-react": "^4.0.0",
        "eslint": "^8.38.0",
        "eslint-plugin-react": "^7.32.2",
        "eslint-plugin-react-hooks": "^4.6.0",
        "eslint-plugin-react-refresh": "^0.3.4",
        "vite": "^4.3.2"
      }
    ```
