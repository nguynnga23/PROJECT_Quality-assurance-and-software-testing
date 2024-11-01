# Todo App

This is a simple Todo application built using Python and SQLite. The application allows users to add, view, update and delete tasks. The data is stored in a SQLite database and the front-end is rendered using the Jinja2 template engine.

## Requirements
- Python 3.x
- Flask
- SQLite3

## Installation
1. Clone the repository git clone 

    `https://github.com/nguynnga23/PROJECT_Quality-assurance-and-software-testing.git`

2. Install the required packages
    
    `pip install -r requirements.txt`

3. Create the database
    
    `python db_create.py`

## Usage
1. Start the development server
    python app.py

2. Open `http://localhost:5000` in your web browser

"# PROJECT_Quality-assurance-and-software-testing" 


## Test selenium trên visual studio code
B1. Thêm extention selenium trên chrome

B2. Mở terminal

    pip install selenium pytest
    
    pytest tests/test_addTask.py
