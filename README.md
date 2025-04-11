#  Django Bookstore Application

A complete e-commerce bookstore built with Django, MySQL, and Bootstrap. Features user authentication, shopping cart, book catalog, and admin dashboard.

##  Screenshots
Home Page
![image](https://github.com/user-attachments/assets/d171bb86-e245-41a4-a21d-36d9109c7d8e)
![image](https://github.com/user-attachments/assets/92618d26-3b7d-4484-9ed9-0955da1fd107)
After Clicking "Veiw Details"
![image](https://github.com/user-attachments/assets/60d7a8a4-6486-49b1-b287-8d3cf48f2a7e)
Cart
![image](https://github.com/user-attachments/assets/0d263a30-59d2-4e91-b358-483fb37da747)






##  Features

- **User Authentication**: Login, logout, and registration system
- **Book Catalog**: Browse books by category/publication
- **Shopping Cart**: Add/remove items, view cart total
- **Admin Dashboard**: Manage books, publications, and orders
- **Responsive Design**: Works on mobile and desktop

##  Technologies Used

- **Backend**: Django 5.2
- **Database**: MySQL
- **Frontend**: Bootstrap 5, HTML5, CSS3
- **Authentication**: Django Auth System
- **Deployment**: (Specify when deployed)

##  Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/premcodeexplorer/bookstore.git
   cd bookstore
   ```
2. Set up virtual environment:
    ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate    # Windows
   ```
3. Install dependencies:
  ```bash
   pip install -r requirements.txt
   ```
4. Configure MySQL:
   ```bash
   CREATE DATABASE bookstore_db;
   CREATE USER 'bookstore_user'@'localhost' IDENTIFIED BY 'yourpassword';
   GRANT ALL PRIVILEGES ON bookstore_db.* TO 'bookstore_user'@'localhost';
   ```
5. Run migrations:
   ```bash
   python manage.py migrate
   ```
6. Create superuser:
    ```bash
   python manage.py createsuperuser
   ```
7. Run development server:
   ```bash
   python manage.py runserver
   ```
## Project Structure
bookstore_project/
├── bookstore/               # Main app
│   ├── migrations/          # Database migrations
│   ├── static/              # CSS, JS, images
│   ├── templates/           # HTML templates
│   ├── admin.py             # Admin config
│   ├── models.py            # Database models
│   └── views.py             # Application logic
├── bookstore_project/       # Project config
└── manage.py                # Django CLI


