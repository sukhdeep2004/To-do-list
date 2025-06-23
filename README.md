# To-Do List Application
  
*A simple Flask-based web application for managing your daily tasks.*

## Features

- ✅ **Add tasks** - Quickly create new to-do items  
- ✏️ **Edit tasks** - Update existing tasks with ease  
- 🗑️ **Delete tasks** - Remove completed or unwanted items  
- 📅 **Date tracking** - Automatically records when tasks were created  
- 📱 **Responsive design** - Works on both desktop and mobile devices  

## Technologies

- **Backend**: Python, Flask  
- **Database**: SQLite with SQLAlchemy ORM  
- **Frontend**: HTML5, CSS3  
- **Templating**: Jinja2  

## Installation

### Prerequisites

- Python 3.6+  
- pip package manager  

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/todo-list-app.git
   cd todo-list-app
   ```

2. Create and activate a virtual environment:

   ```bash
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```

3. Install dependencies:

   ```bash
   pip install flask flask-sqlalchemy
   ```

4. Initialize the database:

   ```bash
   python
   >>> from app import db, app
   >>> with app.app_context():
   ...     db.create_all()
   ...     exit()
   ```

### Running the Application

Start the development server:

```bash
python app.py
```

The application will be available at:  
http://localhost:5000

## Usage Guide

### Adding a Task

- Type your task in the input field  
- Click "Add Task" button  

### Updating a Task

- Click the "Update" link next to the task  
- Edit the task content in the form  
- Click "Update Task" button  

### Deleting a Task

- Click the "Delete" link next to the task  
- The task will be immediately removed  

## Project Structure

```
todo-list-app/
├── app.py               # Main Flask application
├── static/
│   └── css/
│       └── main.css     # Stylesheet
├── templates/
│   ├── base.html        # Base template
│   ├── index.html       # Main page
│   └── update.html      # Update task page
├── test.db              # Database file
└── README.md            # This file
```



## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository  
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)  
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)  
4. Push to the branch (`git push origin feature/AmazingFeature`)  
5. Open a Pull Request  



## Contact

Sukhdeep Singh - sukh.d0609@gmail.com 

```
Flask==2.0.1
Flask-SQLAlchemy==2.5.1
```