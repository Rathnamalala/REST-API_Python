# Flask REST API

A simple REST API built using Python and Flask. This project demonstrates CRUD operations with a SQLite database and Flask extensions like `Flask-SQLAlchemy` and `Flask-RESTful`.

---

## Features

- Perform CRUD operations for managing users.
- SQLite database integration with SQLAlchemy ORM.
- RESTful API endpoints using Flask-RESTful.
- Data marshaling with Flask-RESTful's `marshal_with`.

---

## Table of Contents

- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Project Structure](#project-structure)
- [Contributing](#contributing)


---

## Technologies Used

- **Python**: Programming language.
- **Flask**: Lightweight web framework.
- **Flask-SQLAlchemy**: SQLAlchemy ORM integration with Flask.
- **Flask-RESTful**: Flask extension for building REST APIs.
- **SQLite**: Lightweight database for development.

---

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Create and activate a virtual environment:**

   ```bash
   python -m venv .venv
   source .venv/bin/activate        # On Linux/Mac
   .venv\Scripts\activate           # On Windows
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Initialize the database:**

   Run the database creation script to set up the SQLite database:

   ```bash
   python create_db.py
   ```

---

## Usage

1. **Start the application:**

   ```bash
   python api.py
   ```

2. **Access the application:**

   - Open your browser or an API testing tool like Postman.
   - Use the base URL: `http://127.0.0.1:5000/`.

---

## API Endpoints

| Method | Endpoint           | Description                  |
|--------|--------------------|------------------------------|
| GET    | `/api/user/`       | Retrieve all users.          | 
| POST   | `/api/user/`       | Create a new user.           | 
| DELETE | `/api/user/<id>`   | Delete a user by ID.         |
| GET    | `/api/user/<id>`   | Retrive a user by ID.        |
| PATCH  | `/api/user/<id>`   | Update a user by ID.         | 

---

## Project Structure

```
.
├── api.py            # Main application file
├── create_db.py      # Script to initialize the database
├── requirements.txt  # Python dependencies
├── .venv/            # Virtual environment directory
├── README.md         # Project documentation

```

---

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push the branch: `git push origin feature/your-feature-name`.
5. Open a pull request.

---



## Author

- **Your Name**  
  GitHub: [@RIBKSP RATHNAMALALA](https://github.com/rathnamalala)  
  Email: prabathrathnamalala2k2@gmail.com
