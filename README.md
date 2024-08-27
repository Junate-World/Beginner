# Beginner

## Overview

This is a minimal Flask application that demonstrates how to set up a basic web server, render an HTML template, and include static assets such as CSS files and an image. It serves a single route that renders the `home.html` template.

## Features

- Basic Flask application setup
- Single route (`/`) that renders an HTML template
- Static assets including CSS and images
- Debug mode enabled for development

## Prerequisites

Ensure you have the following installed:

- Python 3.6 or higher
- pip (Python package installer)

## Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/Junate-World/Beginner.git
    cd simple-flask-app
    ```

2. **Create a virtual environment** (optional but recommended):

    ```bash
    python -m venv venv
    ```

3. **Activate the virtual environment**:

    - On Windows:

      ```bash
      venv\Scripts\activate
      ```

    - On macOS/Linux:

      ```bash
      source venv/bin/activate
      ```

4. **Install Flask**:

    Since this is a basic app, you'll need Flask. You can install it using pip:

    ```bash
    pip install flask
    ```

5. **Create a `requirements.txt` file** (optional but recommended) to list dependencies:

    ```bash
    pip freeze > requirements.txt
    ```

## Running the App

To start the Flask application, use the following command:

```bash
python app.py


##My Project Directory
Beginner/
├── app.py
├── README.md
├── static/
│   ├── css/
│   │   └── styles.css
│   └── images/
│       └── spoky.jpg
└── templates/
    └── home.html



