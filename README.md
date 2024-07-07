# Django Data Analysis Web Application

This is a Django-based web application that allows users to upload CSV files, perform data analysis using pandas and numpy, and display the results and visualizations on the web interface.

## Features

- **File Upload**: Users can upload CSV files through a web form.
- **Data Analysis**: Basic data analysis is performed, including:
  - Displaying the first few rows of the data.
  - Calculating summary statistics (mean, median, standard deviation) for numerical columns.
  - Identifying and handling missing values.
- **Data Visualization**: Generates basic plots such as histograms for numerical columns using matplotlib and seaborn.
- **User Interface**: A simple and user-friendly interface to display data analysis results and visualizations.

## Setup Instructions

### Prerequisites

- Python 3.x
- Django 3.x
- pandas
- numpy
- matplotlib
- seaborn

### Installation

1. **Clone the repository**:
    ```sh
    git clone <repository-url>
    cd <repository-name>
    ```

2. **Create and activate a virtual environment**:
    ```sh
    python -m venv venv
    source venv/bin/activate
    # On Windows use `venv\Scripts\activate`
    ```

3. **Install dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

4. **Apply migrations**:
    ```sh
    python manage.py migrate
    ```

5. **Run the development server**:
    ```sh
    python manage.py runserver
    ```

### Usage

1. **Access the application**:
    Open a web browser and go to `http://127.0.0.1:8000/upload/`.

2. **Upload a CSV file**:
    Use the web form to upload a CSV file.

3. **View analysis results**:
    The application will display the first few rows of the data, summary statistics, and any missing values.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements.


