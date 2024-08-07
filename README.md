# Project Description: Ecomzy

Ecomzy is a dynamic Single Page Application (SPA) built using React and Tailwind CSS, designed to offer a seamless and interactive shopping experience. The application features two primary pages: Home and Cart, which are rendered using Routes and Route.

#### Key Features:
- **Home Page**: 
  - Displays a variety of products retrieved via an API call, each product card showcasing the name, description, price, and image.
  - "Add to Cart" button allows users to add products to their cart, which dynamically updates to "Remove from Cart" once clicked.

- **Cart Page**: 
  - Displays all products added to the cart along with the total amount and the total number of items.
  - Products can be easily removed from the cart, reflecting the changes immediately.

#### Technical Highlights:
- **State Management**: 
  - Implemented using Redux, with a cart slice to manage cart items and functionality for adding/removing items.
  - Utilized hooks such as `useSelector`, `useDispatch`, `useEffect`, and `useState` to enhance interactivity and manage state effectively.

- **API Integration**: 
  - Fetch API is used for seamless data retrieval, ensuring real-time updates.

- **Responsive Design**: 
  - Media queries are employed to ensure the application is fully responsive across all devices.

- **Loader Component**: 
  - A loader is displayed during API calls to improve user experience by indicating loading states.

- **Navbar**: 
  - Features a logo linking to the Home page and a cart icon that displays the number of items in the cart for intuitive navigation.

Technologies used include React, Redux, Tailwind CSS, and CSS. Through this project, I have deepened my proficiency in state management with Redux and the creation of scalable, responsive web applications.
