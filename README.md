# Breast Cancer Prediction Tool

An AI-powered web application that helps medical professionals predict whether a breast mass is benign or malignant using machine learning.

## Features

- **Comprehensive Analysis**: Analyzes 30 different cell nucleus features to make accurate predictions
- **PDF Reports**: Generate detailed PDF reports with patient information and prediction results
- **Email Reports**: Send prediction reports directly to patients via email for convenient sharing
- **User Authentication**: Secure login system for medical professionals
- **Data Privacy**: Patient data is processed securely and not stored permanently

## How It Works

1. **Input Patient Data**: Enter basic patient information and cell nucleus measurements from the sample
2. **AI Analysis**: Our machine learning model analyzes the data using patterns learned from thousands of samples
3. **Get Results**: Receive instant prediction results indicating benign or malignant with confidence level
4. **Generate Report**: Create a professional PDF report for medical records and patient information
5. **Share Results**: Email the report directly to patients securely with detailed diagnosis information

## Technical Stack

- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite
- **Machine Learning**: Scikit-learn
- **Authentication**: Werkzeug Security

## Installation

1. Clone the repository
   ```
   git clone https://github.com/your-username/breast-cancer-predictor.git
   cd breast-cancer-predictor
   ```

2. Install dependencies
   ```
   pip install -r requirements.txt
   ```

3. Run the application
   ```
   python app.py
   ```

4. Access the application in your browser at `http://localhost:5000`

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Disclaimer

This tool is designed to assist medical professionals and should not replace professional medical advice, diagnosis, or treatment.
