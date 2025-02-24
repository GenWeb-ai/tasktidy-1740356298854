```markdown
# Simple Todo Web App

This is a simple Todo web application with a frontend built using vanilla JavaScript, HTML, and CSS, and a backend built using Flask.

## Project Structure

- `frontend/`: Contains the frontend code.
  - `src/`: Source files for the frontend.
    - `index.html`: Main HTML file.
    - `styles.css`: CSS styles.
    - `app.js`: JavaScript logic.
- `backend/`: Contains the backend code.
  - `app.py`: Flask application.

## Setup & Installation Guide

### Prerequisites

- Python 3.x
- Flask

### Backend Setup

1. Navigate to the `backend` directory:
   ```bash
   cd backend
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   ```

3. Activate the virtual environment:

   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS and Linux:
     ```bash
     source venv/bin/activate
     ```

4. Install Flask:
   ```bash
   pip install flask
   ```

5. Run the Flask application:
   ```bash
   python app.py
   ```

### Frontend Setup

1. Open the `frontend/src/index.html` file in your web browser.

### Usage

- Add a new todo by typing in the input box and clicking "Add".
- Delete a todo by clicking the "Delete" button next to it.

### Note

This application is a simple demonstration and does not persist data between sessions.
```

