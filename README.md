# Library Management System

A library management system built with Flask that allows users to manage books, authors, and users.

## Local Development Setup

1. Create and activate a virtual environment:
```bash
# Windows
python -m venv venv
venv\Scripts\activate

# Linux/Mac
python3 -m venv venv
source venv/bin/activate
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Set up the admin user and database:
```bash
python create_admin.py
```

This script will:
- Initialize the database
- Create necessary tables
- Set up an admin user with the following credentials:
  - Email: admin@example.com
  - Password: admin123

## Running Locally

1. Start the development server:
```bash
python wsgi.py
```

2. Open your browser and navigate to:
```
http://localhost:5001
```

3. Log in with the admin credentials created above.


## Features

- User authentication and authorization
- Course creation and management
- Secure user authentication with password hashing
- Role-based access control (RBAC) for authorization
- Student enrollment system
- Course content management
- Notes taking system
- Discussion forum
- Admin dashboard
- File upload support
- User profiles


