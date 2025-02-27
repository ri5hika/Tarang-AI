Tarang AI: AI-Powered Water Safety Predictor
A dynamic web application that provides AI-based predictions through an intuitive interface.
Overview
This repository contains a dynamic website that leverages AI to generate predictions. The frontend is built with HTML, CSS, and JavaScript, while the backend is powered by Python using Flask.
Key Files

aipred.html - The main frontend interface
app.py - Flask backend that handles the prediction logic
static/ - CSS, JavaScript, and image assets
templates/ - HTML templates (including aipred.html)

Prerequisites
Before running this application, make sure you have the following installed:

Python 3.7+
Flask
Other dependencies (listed in requirements.txt)

Installation
bashCopy# Clone the repository
git clone https://github.com/yourusername/ai-prediction-website.git
cd ai-prediction-website

# Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
Usage

Start the Flask application:
bashCopypython app.py

Open your web browser and navigate to:
Copyhttp://localhost:5000

The aipred.html interface will be served automatically through the Flask application.

Project Structure
Copyai-prediction-website/
├── app.py                  # Main Flask application
├── templates/              
│   └── aipred.html         # Main HTML interface
├── static/
│   ├── css/                # Stylesheets
│   ├── js/                 # JavaScript files
│   └── images/             # Image assets
├── requirements.txt        # Python dependencies
└── README.md               # This file
How It Works
The app.py file serves as the backend for this application. It:

Hosts the web server
Processes prediction requests
Serves the aipred.html file dynamically
Handles any API calls made from the frontend

The aipred.html file provides the user interface where users can:

Input data for predictions
View prediction results
Interact with the AI model
