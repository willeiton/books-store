# Public Library System API

This project is a **Public Library System API** built with Laravel, designed to provide public access to book data using the **Open Library API**. The application allows users to search for books, retrieve details, explore authors, and browse books by subject.

---

## Features

This project leverages the **Open Library API** to fetch book and author data seamlessly.

- **Search Books**: Search for books by title, author, or subject.
- **Get Book Details**: Retrieve detailed information about a specific book, including title, author, and publication date.
- **List Books by Subject**: Explore books categorized by subjects such as "fantasy," "history," etc.
- **Author Information**: Retrieve details about authors and their works.
- **Purchase (demo)**

---

## Tech Stack

- **Backend**: Laravel 11
- **API Integration**: Open Library API
- **HTTP Client**: Laravel HTTP Client (or Guzzle)

---

## Prerequisites

- **PHP**: Version 8.1 or higher.
- **Composer**: Dependency manager for PHP.
- **Laravel**: Installed globally or use `composer create-project`.
- **Open Library API**: No authentication required.

---

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/public-library-api.git
   cd public-library-api
   ```

2. Install dependencies:

   ```bash
   composer install
   ```

3. Set up the environment:

   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

4. Configure the `.env` file as needed for your local environment.

5. Run the development server:

   ```bash
   php artisan serve
   ```

6. Access the API at `http://127.0.0.1:8000`.

---

## Endpoints

In process

---

## Contributing

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature name"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## License

This project is open-source and available under the [MIT License](LICENSE).

