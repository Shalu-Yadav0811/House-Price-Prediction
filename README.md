# House-Price-Prediction
Overview

This project aims to analyze the California housing dataset and build a predictive model for estimating house prices based on various features. The dataset is sourced from Scikit-Learn and contains information such as median income, house age, and location-based features.

Dataset

The California housing dataset contains the following features:

MedInc: Median income in the block.

HouseAge: Median age of houses in the block.

AveRooms: Average number of rooms per household.

AveBedrms: Average number of bedrooms per household.

Population: Block population.

AveOccup: Average number of household members.

Latitude: Block latitude.

Longitude: Block longitude.

Project Structure

California-Housing-Price-Prediction/
│-- data/
│   ├── california_housing.csv  # Dataset
│-- notebooks/
│   ├── data_analysis.ipynb      # Exploratory Data Analysis
│   ├── model_training.ipynb     # Model Training
│-- src/
│   ├── preprocess.py            # Data preprocessing functions
│   ├── train.py                 # Model training script
│   ├── evaluate.py              # Model evaluation script
│-- README.md
│-- requirements.txt

Installation

To set up the project locally, follow these steps:

Clone the repository:

git clone https://github.com/yourusername/California-Housing-Price-Prediction.git

Navigate to the project directory:

cd California-Housing-Price-Prediction

Create a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows

Install dependencies:

pip install -r requirements.txt

Usage

Exploratory Data Analysis (EDA)

Run the data_analysis.ipynb notebook to explore the dataset, visualize correlations, and gain insights.

Model Training

Use train.py or model_training.ipynb to train a machine learning model such as Random Forest or XGBoost.

Evaluation

After training, evaluate the model using evaluate.py or directly in the Jupyter notebook.

Results

The trained model predicts house prices based on features, with evaluation metrics such as RMSE, MAE, and R² score.

Technologies Used

Python

Pandas

NumPy

Scikit-Learn

Matplotlib & Seaborn

XGBoost (Optional for advanced modeling)

Contributing

Feel free to fork this repository and contribute improvements. Pull requests are welcome!

Author

Shalu yadav
