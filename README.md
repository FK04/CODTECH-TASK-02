# CODTECH-TASK-02
- **Name :** SYED ABDUL QADER FAIZAN KHUNDMIRY
- **Company :** CODTECH IT SOLUTIONS
- **ID :** CT6WDS1928
- **Domain :** Python Programming
- **Duration:** September to November 2024
- **Mentor :** Neela Santhosh Kumar

## Overview Of The Project

### Project : Online Market Place

### Overview 
This project is a Django-based e-commerce platform named ShopSphere. The application facilitates online shopping by allowing users to browse, review, and purchase products. It features a user-friendly interface and provides functionalities such as user profiles, product reviews, shopping carts, and order management.

### Features
- User Profiles: Allows users to register and manage their profiles, distinguishing between buyers and sellers.
- Product Management: Sellers can list products with details including images, descriptions, and pricing.
- Shopping Cart: Users can add products to a customizable shopping cart.
- Order System: Facilitates the purchasing process and tracks order status from placement to delivery.
- Reviews: Users can post reviews on products, which also support a dynamic rating system.
- Responsive Design: The front-end utilizes Bootstrap for a responsive layout, ensuring compatibility across various devices and screen sizes.
### Technologies Used
- Backend: The application is built on the Django framework, leveraging Django REST Framework for the API.
- Frontend: Bootstrap for responsive design, with additional custom CSS for styling.
- Database: Uses Django's default SQLite in development with the option to scale to PostgreSQL or another database system for production environments.
- - Deployment: Prepared for deployment on platforms like Heroku or AWS.

## How to Run Locally
- Clone the repository:
 git clone https://github.com/yourusername/shop-sphere.git
cd shop-sphere

- Set up a virtual environment:
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

- Migrate the database:
  python manage.py migrate

  ### Project Structure
- models.py: Defines the data models including Product, Category, Review, UserProfile, Cart, and Order.
- views.py: Handles the request/response logic for the application.
- urls.py: Manages the URL declarations for the Django project.
- serializers.py: Used for converting complex data types such as querysets and model instances to native Python datatypes.
- templates/: Contains HTML files for the user interface.
- static/: Stores static files like CSS, JavaScript, and images.
### Future Enhancements
- Integration of a payment gateway such as Stripe or PayPal.
- Advanced product search and filtering capabilities.
- Email notifications for order updates and user registration.
