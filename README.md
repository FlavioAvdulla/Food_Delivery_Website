# Tomato - Full Stack Food Delivery Web Application

Welcome to the **Tomato** food delivery web application! This project is a full-stack web application designed for online food ordering and delivery. It features an intuitive menu, easy ordering system, and payment integration. Users can browse the menu, add items to their cart, and checkout for a seamless food delivery experience.

![food_delivery1](https://github.com/user-attachments/assets/e5259e65-58f2-44f1-ac1b-9421a7dc3e96)
![food_delivery](https://github.com/user-attachments/assets/672d57c1-4ada-44f2-812f-d5cd88a2d546)
![food_delivery_2](https://github.com/user-attachments/assets/85207ea1-7b46-46a7-a448-7a065c4eded6)
![food_delivery_3](https://github.com/user-attachments/assets/322a922e-a4ad-41db-9659-f7f20e89ea4a)


---

## Features

- **Menu Listing**: Displays a variety of food items including salads, rolls, desserts, sandwiches, and pasta.
- **Order Management**: Users can add items to their cart, view the cart, and proceed to checkout.
- **Product Management (Admin)**: Admin users can add, list, and update menu items with product details such as name, description, price, and category.
- **Mobile App Integration**: Users can order food from the mobile app.
- **Image Upload**: Admins can upload images for menu items.
- **Cart Management**: Users can view the total price, modify item quantities, and remove items from the cart.

---

## Tech Stack

### Frontend
- **HTML5, CSS3, JavaScript**
- **React.js**: For dynamic user interface

### Backend
- **Node.js**: JavaScript runtime for server-side logic
- **Express.js**: Web framework for Node.js
- **MongoDB**: Database for storing user and menu data
- **Mongoose**: MongoDB object modeling tool

### Additional Tools & Libraries
- **Axios**: For making HTTP requests to the backend
- **Cloudinary**: For image uploads
- **Stripe**: For payment processing (if implemented)
- **JWT**: For user authentication (optional, if applicable)

---

## Getting Started

### Prerequisites

Ensure that you have the following installed on your machine:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [MongoDB](https://www.mongodb.com/) (or use a cloud database like MongoDB Atlas)

### Installation

**1. Clone the repository:**
git clone https://github.com/FlavioAvdulla/Food_Delivery_React_Website.git

**2. Install backend dependencies:**
Navigate to the backend folder and install required packages:

`
cd backend
`
`
npm install
`

**3. Install frontend dependencies:**
Navigate to the frontend folder and install required packages:

`
cd ../frontend
`
`
npm install
`

**4. Configure environment variables:**
Create a `.env` file in the root of the backend directory with the following values (modify based on your setup):
`
MONGO_URI=your_mongodb_connection_string
CLOUDINARY_URL=your_cloudinary_url
JWT_SECRET=your_jwt_secret_key
STRIPE_KEY=your_stripe_key (if payment is integrated)
`

**5. Run the application:**
- Start the backend server:

`
cd BackEnd
`
`
npm run server
`
- Start the frontend development server:

`
cd FrontEnd
`
`
npm run dev
`

## Usage
- **Browse Menu:** Visit the home page to explore the food menu with various categories.
- **Add Items to Cart:** Add your favorite dishes to the cart by clicking the "Add" button next to each item.
- **View Cart:** Click on the cart icon to see the added items, total price, and checkout option.
Checkout: Enter delivery details, apply promo codes (if applicable), and proceed with payment.
**Admin Features:** Admins can manage the menu items (add, remove, or update products) and view orders.

## Future Enhancements
- Add user authentication and account management (login/signup).
- Implement user reviews and ratings for menu items.
- Integrate geolocation to improve delivery experience.
- Add an admin dashboard for better management of orders, menu items, and users.

## Contributing
We welcome contributions to the Tomato food delivery app! If you'd like to contribute, follow these steps:
- Fork the repository.
- Create a new branch for your feature or fix.
- Make your changes and commit them.
- Push your changes to your fork.
- Create a pull request with a description of your changes.

## Contact
For any inquiries or issues, feel free to reach out to me:

- Email: **a.flavio4366@gmail.com**
- Phone: **+355 67 63 11 918**


This `README.md` file provides a comprehensive overview of your web application's features, tech stack, installation steps, usage instructions, and guidelines for contributing. You can adjust the details as needed for your project.

