# Secure Crime Sight

## Overview
Secure Crime Sight is an innovative web application designed to enhance crime prediction and analysis. By leveraging machine learning algorithms and data encryption techniques, this system provides valuable insights into crime patterns, arrest probabilities, and zone classifications. Additionally, a comprehensive Power BI dashboard offers detailed crime analysis for better decision-making.

## Features
- **User Authentication:** Secure login and access control.
- **News-Based Prediction:** Predicts crime trends based on news data.
- **Arrest Probability:** Estimates the likelihood of arrests.
- **Zone Classification:** Classifies regions into different crime zones using machine learning.
- **RSA Encrypted Data:** Ensures the security of sensitive data.
- **Power BI Dashboard:** Visualizes detailed crime analysis.

## Tools and Technologies
- **Backend:** Python, Django
- **Machine Learning:** Random Forest, SVM
- **Data Visualization:** Power BI
- **Deployment:** AWS
- **Encryption:** RSA

## Installation

### Prerequisites
- Python 3.x
- Django
- Power BI
- AWS account

### Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/secure-crime-sight.git
    ```
2. Navigate to the project directory:
    ```bash
    cd secure-crime-sight
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Start the Django development server:
    ```bash
    python manage.py runserver
    ```
2. Open your web browser and go to `http://127.0.0.1:8000/` to access the application.
3. Log in with your credentials to explore the features.

## Project Structure
```
secure-crime-sight/
│
├── backend/
│   ├── manage.py
│   ├── mysite/
│   ├── app/
│   ├── templates/
│   └── static/
│
├── models/
│   ├── prediction_model.py
│   ├── arrest_probability_model.py
│   └── zone_classification_model.py
│
├── research/
│   └── rsa_encryption_performance.md
│
├── dashboard/
│   └── crime_analysis_dashboard.pbix
│
├── deployment/
│   ├── aws_setup.md
│   └── deploy.sh
│
├── requirements.txt
└── README.md
```

## How It Works
### News-Based Prediction
The application uses machine learning algorithms to analyze news data and predict crime trends.

### Arrest Probability
Utilizes Random Forest and SVM models to estimate the likelihood of arrests based on historical data.

### Zone Classification
Classifies different regions into crime zones to help authorities focus on high-risk areas.

### RSA Encrypted Data
Sensitive data is encrypted using RSA to ensure privacy and security during transmission and storage.

### Power BI Dashboard
A detailed and interactive dashboard provides visual insights into crime patterns, arrest probabilities, and zone classifications.


## Contributing
Contributions are welcome! Please fork the repository and submit pull requests.


## Acknowledgements
- Inspired by the need for improved crime prediction and analysis.
- Special thanks to the open-source community for providing the tools and libraries.
