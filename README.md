# Student Exam Performance Predictor

## Project Overview
The Student Exam Performance Predictor is a machine learning-based web application that predicts a student's math exam score using demographic information, test preparation status, and reading/writing scores. The project combines data processing, model training with multiple regression algorithms, and a Flask web frontend to provide an easy-to-use prediction tool.

---

## Motivation
This tool helps educators and students identify potential areas of improvement by predicting math scores from accessible student data, supporting targeted interventions and improved academic planning.

---

## Features
- Predict math exam scores based on student demographics and educational background.
- Multiple regression models are trained and evaluated for optimal prediction performance.
- Web interface built with Flask enables users to input data and get real-time predictions.
- Data preprocessing includes handling missing values, encoding categorical data, and feature scaling.
- Visualization notebooks and detailed model evaluation included.

---

## Tech Stack
- Python 3.x
- Flask (Web framework)
- Scikit-learn, CatBoost, XGBoost (Machine Learning libraries)
- Pandas, NumPy (Data handling)
- Bootstrap, HTML (Frontend interface)
- Git for version control

---

## Project Structure
├── artifacts/ # Data splits, trained models, and preprocessor objects
├── notebook/ # Jupyter notebooks for EDA and model training
├── src/ # Source code (data ingestion, transformation, training)
├── templates/ # HTML templates for the Flask app
├── requirements.txt # Python dependencies
├── README.md # Project documentation (this file)
├── app.py or run.py # Flask application entry point


---

## Installation

### Prerequisites
- Python 3.8 or higher
- `pip` package manager

### Steps
1. Clone the repository:
git clone [<repository-url>](https://github.com/atharvakanchan25/Student-Performance-Predictor)
cd Student-Performance-Predictor

2. (Optional) Create and activate a virtual environment:
- Linux/macOS:
  ```
  python3 -m venv venv
  source venv/bin/activate
  ```
- Windows:
  ```
  python -m venv venv
  venv\Scripts\activate
  ```

3. Install dependencies:
pip install -r requirements.txt

4. Run the Flask app:
or

5. Open a web browser and go to:
http://127.0.0.1:5000/

---

## Usage
- Enter student details including gender, ethnicity, parental education, lunch type, test preparation course, and their reading and writing scores.
- Submit the form to get a predicted math score.
- Use the prediction to assess academic performance and guide interventions.

---

## Model Training
- The dataset is split into training and testing sets.
- Features are preprocessed using pipelines for encoding and scaling.
- Multiple regression models (Linear Regression, Ridge, Random Forest, XGBoost, CatBoost, etc.) are trained with hyperparameter tuning.
- Model evaluation uses metrics like R², RMSE, and MAE.
- The best model is saved for use in the prediction web application.

---

## Contribution
Contributions are welcome! Fork the repository, create a branch, and submit pull requests with improvements or features.

---

## License
This project is licensed under the MIT License.

---

## Contact
- Author: [Your Name]
- Email: your.email@example.com
- GitHub: https://github.com/atharvakanchan25

---

This README provides an end-to-end summary covering setup, usage, and project details for the Student Exam Performance Predictor.
