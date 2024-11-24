# 📚 Drf-BookApi

A Django REST Framework (DRF) project designed to manage a collection of books, providing a simple yet effective API for CRUD operations.

## 🚀 Features

- 📝 **CRUD Operations:** Create, read, update, and delete book records seamlessly.
- 🔍 **Filtering and Searching:** Efficiently filter and search through the book collection.
- 📊 **Pagination:** Handle large datasets with built-in pagination support.
- 
## 🛠️ Installation

Follow these steps to set up the project locally:

1. **Clone the Repository** 📂

   ```bash
   git clone https://github.com/Sarizeybekk/Drf-BookApi.git


2. **Navigate to the Project Directory ** 📂

   ```bash
   cd Drf-BookApi




3. **Create a Virtual Environment** 🌐
    ```bash

     python -m venv venv
4. ***Activate the Virtual Environment** ⚙️
    ```bash
On Windows:

    venv\Scripts\activate


On macOS and Linux:


    source venv/bin/activate
5. ***Install Dependencies ** 📦
      ```bash

      pip install -r requirements.txt
6. ***Apply Migrations** 🗄️


    python manage.py migrate
7. ***Create a Superuser** 👤


       python manage.py createsuperuser
   8. ***Run the Development Server** 🚀

       ```bash
       python manage.py runserver
The API will be accessible at http://127.0.0.1:8000/.

# 📋 API Endpoints

The following endpoints are available for managing books:

- **List Books**  
  ```http
  GET /api/books/
Create Book

   POST /api/books/
Retrieve Book Details

   GET /api/books/{id}/
Update Book

PUT /api/books/{id}/
Delete Book

DELETE /api/books/{id}/
For detailed information on request and response formats, refer to the API Documentation.
