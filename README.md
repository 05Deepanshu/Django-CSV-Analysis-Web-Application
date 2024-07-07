# Django CSV Analysis Web Application

## Setup Instructions

1. Clone the repository.
2. Navigate to the project directory.
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
Django Data Analysis Web Application
This is a Django-based web application that allows users to upload CSV files, perform data analysis using pandas and numpy, and display the results and visualizations on the web interface.

Features
File Upload: Users can upload CSV files through a web form.
Data Analysis: Basic data analysis is performed, including:
Displaying the first few rows of the data.
Calculating summary statistics (mean, median, standard deviation) for numerical columns.
Identifying and handling missing values.
Data Visualization: Generates basic plots such as histograms for numerical columns using matplotlib and seaborn.
User Interface: A simple and user-friendly interface to display data analysis results and visualizations.
Setup Instructions
Prerequisites
Python 3.x
Django 3.x
pandas
numpy
matplotlib
seaborn
Installation
Clone the repository:
git clone <repository-url>
cd <repository-name>
Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate
# On Windows use `venv\Scripts\activate`
Install dependencies:
pip install -r requirements.txt.
Apply migrations:
python manage.py migrate
Run the development server:
python manage.py runserver