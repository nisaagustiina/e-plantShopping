# e-PlantShopping : GreenNest

## Description
**e-PlantShopping** is a front-end web application built with React.  
This project was created as a graduation requirement for the **Developing Front-End Apps with React** module.
The application simulates an online plant shopping experience, allowing users to browse plants, view details, and manage items in a shopping cart.

## Features
- A landing page with a button linking to the product listing page
- A navigation bar with links to the landing page, product listing page, and shopping cart page
- A plant card for each product displaying:
  - Plant image
  - Name
  - Description
  - Cost
  - **Add to Cart** button
- At least two plant sections, such as:
  - Aromatic Plants
  - Medicinal Plants
- A shopping cart page that displays all products added to the cart
- A cart card for each plant type in the cart, including:
  - Plant thumbnail
  - Unit cost
  - Total cost per plant type
  - Buttons to increase and decrease quantity
  - Delete button
- **Continue Shopping** and **Checkout** buttons on the cart page

## Technologies Used
- React
- JavaScript (ES6+)
- HTML5
- CSS3

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/nisaagustiina/e-plantShopping.git
2. Navigate to the project directory:
    ```bash
    cd e-plantShopping
3. Install dependencies
    ```bash
    npm install
4. Start the development server:
    ```bash
    npm run dev

## Usage
Open your browser and go to:
    ```bash
    https::localhost:5173/shoppingreact

## Project Structure
    src/
    ├── assets/
    ├── AboutUs.css/
    ├── AboutUs.jsx/
    ├── App.css/
    ├── App.jsx/
    ├── CartItem.css/
    ├── CartItem.jsx/
    ├── CartSlice.jsx/
    └── index.css/
    ├── main.jsx/
    └── ProductList.css/
    ├── ProductList.jsx/
    └── store.js/

## Purpose
This project demonstrates the use of React components, state management with Hooks, Redux Integration, Rendering Dynamic Data, Handling Events and Conditional Rendering.

## Author
Nisa Agustina

## License
This project is intended for educational purposes only.