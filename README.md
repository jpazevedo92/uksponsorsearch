

# Simple Flask Template

This is a basic template for a Flask web application. It includes a single route for a homepage, a simple HTML template, and basic CSS styling.

## Project Structure

The project structure is as follows:
```bash
my_flask_app/    
├── app.py          - Main application file    
├── templates/  
│   └── index.htm   - HTML template for the homepage  
└── static/  
    └── style.css   - CSS styling for the page  
```
- **app.py**: The main file to start the Flask application.
- **templates/index.html**: HTML file with a basic structure /for the homepage, using Jinja2 template syntax.
- **static/style.css**: Basic CSS file to style the page.

## Prerequisites

- Python 3.x
- Flask (installable via pip)

## Setup Instructions

1. **Clone the repository** (if needed) and navigate into the project folder:
    ```bash
    git clone <repository-url>
    cd my_flask_app
    ```

2. **Create a virtual environment** (recommended):
    ```bash
    python3 -m venv venv
    source venv/bin/activate   # On Windows, use venv\Scripts\activate
    ```

3. **Install Flask**:
    ```bash
    pip install Flask
    ```

## Running the Application

1. Start the Flask development server:
    ```bash
    python app.py
    ```

2. Open your web browser and navigate to `http://127.0.0.1:5000` to view the homepage.

## File Descriptions

- **app.py**: Contains the main route (`/`) that renders the `index.html` template.
- **index.html**: Basic HTML page with a heading and a paragraph.
- **style.css**: Contains simple CSS to style the text on the homepage.

## Customization

- **HTML Content**: Modify `templates/index.html` to change the structure or content of the homepage.
- **CSS Styling**: Modify `static/style.css` to adjust the styling as needed.

## License

This project is licensed under the MIT License.
