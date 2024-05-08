# Boston House Price Prediction

## Overview
This project aims to predict house prices in Boston using machine learning techniques. The predictive model is built using various algorithms including Gradient Boosting, Random Forest, Linear Regression, XGBoost, K-Nearest Neighbors, and Decision Trees. The dataset is stored in MySQL, tracked using DVC, and experimentations are monitored through MLflow via Dagshub. The backend is developed using Flask, and the frontend interface is created with HTML.

## Setup Instructions
1. Clone the repository: 
```
git clone https://github.com/SankritaPatelBostonHousePricePrediction.git
```
2. Make virtual environment and activate it.
3. Install dependencies:
```
pip install -r requirements.txt
```
4. Setup MySQL database and import the dataset.
5. Start the Flask server: 
```
python app.py
```
6. Access the frontend interface through a web browser.

## File Structure
- `data/`: Contains dataset files.
- `models/`: Stores trained machine learning models.
- `src/`: Source code for data preprocessing, model training, and Flask app.
- `templates/`: HTML files for frontend interface.
- `app.py`: Flask application script.
- `requirements.txt`: List of dependencies.

## Usage
- Navigate to the frontend interface to input features and get predictions.
- Experiment with different machine learning algorithms and hyperparameters for model tuning.

## Contributions
Contributions are welcome! Feel free to submit issues or pull requests for enhancements or bug fixes.

## License
This project is licensed under the MIT License.

![Alt Text](Image URL)
