# 📚 Munna's Bookstore
![lara2](https://github.com/user-attachments/assets/90af4d7e-a147-4077-8d81-0f223bef6dac)

https://youtu.be/3bmyEBV0czA?si=4C-iKLBnZoepwut8
Made By Md Munjurul Alom 
ID:0322320105101020
A full-featured **Laravel CRUD application** for managing books in a bookstore. Users can search, view, update, and delete books in a clean and responsive UI.
---

## 🔧 Features

- 📖 Book listing with pagination
- 🔍 Live search
- ➕ Add new books
- 📝 Update existing books
- ❌ Delete books with confirmation
- 🔎 View book details
- Responsive design using Bootstrap
- Clean MVC structure with Eloquent ORM

---

## 🚀 Tech Stack

- **Laravel 10+**
- **PHP 8.1+**
- **MySQL**
- **Bootstrap 5**
- **Blade Templating**
- **Eloquent ORM**

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/bookstore.git

cd bookstore

# Install PHP dependencies
composer install

# Copy environment file
cp .env.example .env

# Generate application key
php artisan key:generate

# Set your database credentials in the .env file

# Run migrations
php artisan migrate

# (Optional) Seed the database
php artisan db:seed

# Serve the application
php artisan serve

📁 Folder Structure
├── app/
├── bootstrap/
├── config/
├── database/
│   ├── migrations/
│   ├── seeders/
├── public/
├── resources/
│   ├── views/
│   │   ├── books/
│   │   │   ├── index.blade.php
│   │   │   ├── create.blade.php
│   │   │   ├── edit.blade.php
│   │   │   ├── show.blade.php
├── routes/
│   └── web.php
├── .env

📚 Book Fields
Title

Author

ISBN

Stock

Price

✍️ Author
Made ❤️ by [MUNJURUL-20]
