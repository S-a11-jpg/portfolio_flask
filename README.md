
# Flask Portfolio Website

A personal portfolio web application built using Python and Flask. This project is designed as a real-world mini web app to showcase personal information and a contact form, demonstrating fundamental concepts of Flask web development.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Key Concepts](#key-concepts)
- [Interview Questions](#interview-questions)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project is part of a Python Developer Internship task to build a personal portfolio website using Flask. The site has a home page displaying basic personal info and a contact form to collect messages.

## Features

- Home page with personal introduction
- Contact form with POST method handling
- Basic styling using CSS
- Flask routing and template rendering
- Separation of static files (CSS) and templates (HTML)

## Technologies Used

- Python 3.x
- Flask micro web framework
- HTML5 & CSS3

## Installation

1. Clone this repository:

   ```
   git clone 
   cd portfolio_flask
   ```

2. Create and activate a virtual environment (optional but recommended):

   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install required packages:

   ```
   pip install flask
   ```

## Usage

1. Run the Flask application:

   ```
   python app.py
   ```

2. Open your browser and visit:

   ```
   http://127.0.0.1:5000/
   ```

3. Use the contact form to send a message. The app will display a thank-you message after submission.

## Project Structure

```
portfolio_flask/
│
├── app.py               # Main Flask application
├── templates/
│   └── index.html       # HTML template for homepage
├── static/
│   └── style.css        # CSS styles
└── README.md            # Project documentation
```

## Key Concepts

- Flask routing with `@app.route`
- Template rendering with Jinja2
- Handling POST requests with Flask
- Serving static files (CSS)
- Using form data in Flask



## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is open source and available under the MIT License.
```

