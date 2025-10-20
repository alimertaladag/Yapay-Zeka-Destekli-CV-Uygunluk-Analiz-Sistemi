AI-Powered CV Suitability Analysis System
This project is a simple, Python-based web application that analyzes a CV's (Curriculum Vitae) suitability for a specific job posting, considering both content and structural organization. The system uses Natural Language Processing (NLP) techniques for keyword matching and incorporates a simple rule-based mechanism to score the CV's overall visual/structural quality (simulating image processing).
🌟 Features
Dynamic Job Posting Analysis: Evaluates the CV against a job description entered by the user.
Content Suitability: Calculates a keyword matching score using TF-IDF and Cosine Similarity.
Structural Quality Simulation: Scores the CV based on criteria like length and the presence of core sections (Experience, Education, Skills, etc.)—a simulation of basic visual analysis.
Simple Frontend: Stable, Flask-based user interface that avoids complex Jinja2 templating.
🚀 Setup and Running
Follow the steps below to get the project running in your local environment.
Prerequisites
Python 3.8+ is required.
Step 1: Create a Virtual Environment
python -m venv venv
source venv/bin/activate   # Linux/macOS
.\venv\Scripts\activate    # Windows


Step 2: Install Dependencies
Install the required Python libraries listed in the requirements.txt file.
pip install -r requirements.txt


Step 3: Download the SpaCy Language Model
Download the essential English base language model for NLP tasks:
python -m spacy download en_core_web_sm


Step 4: Run the Application
Execute the main application file:
python vision_cv_analyzer.py


Once the application starts, open your browser and navigate to:
[http://127.0.0.1:5000](http://127.0.0.1:5000)


