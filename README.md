SEC 10-K Filings Analysis and Visualization-

Overview:

This project aims to analyze SEC 10-K filings of public firms using text analysis techniques and generate insightful visualizations. The project is split into two main tasks: downloading 10-K filings using Python and conducting text analysis using the LLM API. 

Additionally, a simple web app is constructed to visualize the analysis results.

Tech Stack -
Backend: Python, FlaskText Analysis API: LLM API (free version)
Frontend: HTML, CSS, JavaScript
Deployment: Heroku

Rationale for Tech Stack
Flask: 
Chosen for its simplicity and ease of use in creating web applications with Python.

LLM API: Utilized for text analysis due to its free credits and capability to generate meaningful insights from textual data.

Heroku: Selected for deployment as it provides a convenient platform for hosting Flask apps with easy scalability options.

App Functionality-
The web app allows users to input a company ticker and view visualizations generated from the text analysis of their SEC 10-K filings.

Tech Stack Choice Rationale:

Flask: It's a lightweight and easy-to-use web framework in Python, suitable for small-scale web applications like this.

HTML/CSS/JavaScript: For the frontend, these technologies provide the necessary structure, styling, and interactivity.

Heroku: A platform-as-a-service (PaaS) provider that allows easy deployment of Flask apps.

myapp/
│
├── static/
│   ├── style.css
│   └── script.js
│
├── templates/
│   └── index.html
│
├── app.py
├── README.md
└── requirements.txt
app.py: Flask application logic.templates/index.html: HTML template for the app.

static/style.css: CSS styles for the app.

static/script.js: JavaScript for frontend interactions.
