


1.Project Title:    
                E-commerce React Application
2.Description:   
This E-commerce application is a fully functional, scalable, and modern web application built using React.js. The app aims to provide a seamless shopping experience with features such as user registration, product listing, search functionality, product filtering, sorting, and a complete checkout process. This project utilizes Redux Toolkit for state management, React Router for client-side routing, and Tailwind CSS for styling. The backend used json-server.  

  This is a React-based e-commerce application with the following features:
- User registration
- Product listing with categories
- Search bar results
- Filtering options (size, color, brand, etc.)
- Sorting options (price, popularity, ascending/descending)
- Lazy loading for categories
- Product detail page
- Checkout page

Features
Registration
Users can register with a username, email, and password. The registration form includes validation for required fields.

Product Listing
Products are fetched from the backend and displayed with categories.
The search bar search product by name and display results.
Products can be filtered by size, color, brand, etc.
Sorting options are available for price, popularity, ascending/descending.

Product Detail
Detailed information about a selected product is displayed on a separate page.

Checkout
Users can review their cart items, enter shipping and payment information, and place an order.

State Management
State management is handled using Redux Toolkit. The store configuration and products are located in the src directory.

Styling
The application uses Tailwind CSS for styling. 

Tailwind CSS Setup
Tailwind CSS is already set up in the project. To customize it, you can modify the tailwind.config.js and postcss.config.js files.

Technologies Used
- React.js
- Redux Toolkit
- React Router
- Tailwind CSS 
- json-server


3.Table of Contents:
```
└── 📁src
    └── 📁app
        └── store.js
    └── App.css
    └── App.js
    └── App.test.js
    └── 📁features
        └── 📁cart
            └── Cart.jsx
            └── cartSlice.js
        └── 📁checkout
            └── Checkout.jsx
            └── OrderConfirmation.jsx
        └── 📁products
            └── ProductDetail.jsx
            └── ProductList.jsx
            └── ProductListPage.jsx
            └── productSlice.js
            └── SearchBar.jsx
        └── 📁user
            └── Register.jsx
            └── userSlice.js
    └── index.css
    └── index.js
    └── 📁Layout
        └── Footer.jsx
        └── Header.jsx
    └── logo.svg
    └── 📁registration
        └── Register.jsx
    └── reportWebVitals.js
    └── setupTests.js
```


4:Installation:
npm install @reduxjs/toolkit react-redux axios react-router-dom tailwindcss
npx tailwindcss init
Install Frontend Dependencies
npm install
Running the Frontend
npm start

This will start the development server and open the application in your default browser at http://localhost:3000.

Running the Backend
You can use JSON server for the backend. Below are instructions:
1.	Install JSON server globally (if not already installed):
npm install -g json-server

2.	Start JSON server with the provided db.json file:
npx json-server db.json    


5.Usage:
Register a New User
1.	Navigate to the registration page.
2.	Fill in the registration form with your details (e.g., name, email, password).
3.	Submit the form to create a new user account.
Browse Products
1.	Visit the homepage (http://localhost:3000).
2.	Browse the product listings by category
3.	Use the search bar to find specific products. 
4.	Apply filters (size, color, brand, etc.) and sorting options (price/popularity) to refine the        product list.
View Product Details
1.	Click on a product from the product listing to view its details.
2.	The product detail page will display detailed information about the product, including images, description, price, and other details .
Add Product to Cart
1.	On the product detail page, select the product.
2.	Click the "Add to Cart" button to add the product to your shopping cart.
Checkout
1.	Click on the cart icon to view your shopping cart.
2.	Review the items in your cart and proceed to checkout.
3.	Fill in the checkout form with your shipping and payment information.
4.	Submit the form to complete your purchase.



Testing
Test Case for Purchasing a Product
1.	Navigate to a product detail page.
2.	Click on the "Add to Cart" button.
3.	Navigate to the checkout page.
4.	Fill in the required checkout information.
5.	Submit the checkout form.
6.	Verify that the purchase is completed successfully.








# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
