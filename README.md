# Django Product Catalog

A simple e-commerce product catalog built with Django.  
This project demonstrates how to manage products, display them on a frontend, and handle images.

## Features
- Add, edit, and delete products via Django Admin
- Product list and detail pages
- Image upload and display
- Price stored with precise decimal values
- Automatic timestamps for product creation and updates

## Project Structure
- `models.py` → Defines the Product model (name, description, price, image, timestamps)
- `views.py` → Handles product list and detail logic
- `templates/` → HTML templates for product pages
- `static/` → Static files (CSS, JS, sample images)
- `media/` → Uploaded product images

## Setup
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run migrations: `python manage.py migrate`
4. Create a superuser: `python manage.py createsuperuser`
5. Start the server: `python manage.py runserver`
6. Access the admin panel at `http://localhost:8000/admin/`

## Testing
- Add sample products via the admin panel
- Browse product list at `/products/`
- View product details at `/products/<id>/`

## Future Enhancements
- Add categories and filters
- Implement shopping cart and checkout
- Improve frontend design with CSS/Bootstrap
