# API CALL

Author: Jofil R. Operaña

## Project Title: API Call

### Description
This project is a simple Laravel API practice application that demonstrates how API calls work using routes and controllers. It includes sample API endpoints for retrieving, inserting, updating and deleting student records from the database.

## Setup

### 1. Clone or download this repository and open the project folder in VS Code.

### 2. Install Laravel Herd and the SQLite Viewer extension in VS Code for viewing the SQLite database.

### 3. Inside the project directory, run this command:

```bash
composer install
```

### 4. Copy the `.env.example` file and rename it to `.env`, then configure the database settings.

### 5. Generate the application key:

```bash
php artisan key:generate
```

### 6. Run the database migration:

```bash
php artisan migrate
```

### 7. Start the Laravel development server:

```bash
php artisan serve
```

### 8. Open the following URL in your browser to display the student API data:

```txt
http://127.0.0.1:8000/api/students
```

---

# Testing with Postman

Open Postman and create a new collection for this project.

### Retrieve all student data:

```http
GET http://127.0.0.1:8000/api/students
```

### Retrieve a specific student record:

```http
GET http://127.0.0.1:8000/api/students/5
```

Replace `5` with the desired student ID based on your video.

---

## Demo Tutorial

[Demo Tutorial Video](#)

The tutorial demonstrates how to test Laravel API endpoints using Postman.
