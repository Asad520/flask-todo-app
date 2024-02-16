# Flask CRUD Todo App

## Setup Instructions

1. Clone the repository.

2. Navigate to the project directory.

3. Create a virtual environment: `virtualenv venv`

4. Activate the virtual environment:

- On macOS/Linux:
  ```
  source venv/bin/activate
  ```
- On Windows:
  ```
  .\venv\Scripts\activate
  ```

5. Install dependencies: `pip3 install -r requirements.txt`

6. Create an sqlite db instance using the following steps:
   Start flask shell by entering: `flask shell` in terminal

Enter: `db.create_all()`

A file named `test.db` will be created in instance folder

Enter `exit()` to exit the flask terminal

8. Enter `python3 app.py` to run the project. It runs on `localhost:5000` by default
