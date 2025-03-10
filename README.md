#  House Price Prediction  

## 📌 Overview  
This project aims to analyze the **California Housing Dataset** and build a predictive model for estimating house prices based on various features. The dataset, sourced from **Scikit-Learn**, includes details like median income, house age, and location-based attributes.  

## 🗂️ Dataset Features  
The dataset consists of the following features:  
- **MedInc**: Median income in the block  
- **HouseAge**: Median age of houses in the block  
- **AveRooms**: Average number of rooms per household  
- **AveBedrms**: Average number of bedrooms per household  
- **Population**: Block population  
- **AveOccup**: Average number of household members  
- **Latitude**: Block latitude  
- **Longitude**: Block longitude  

## 📂 Project Structure 

House-Price-Prediction/ │-- data/ │ ├── california_housing.csv # Dataset

│-- notebooks/ │ ├── data_analysis.ipynb # Exploratory Data Analysis

│ ├── model_training.ipynb # Model Training

│-- src/ │ ├── preprocess.py # Data preprocessing functions

│ ├── train.py # Model training script

│ ├── evaluate.py # Model evaluation script

│-- README.md

│-- requirements.txt


## ⚙️  Installation  
To set up the project locally, follow these steps:  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/yourusername/House-Price-Prediction.git  
cd House-Price-Prediction
```

### 2️⃣ Create a Virtual Environment (Optional but Recommended)
``` bash
python -m venv venv  
# Activate the virtual environment  
source venv/bin/activate  # macOS/Linux  
venv\Scripts\activate     # Windows
```
 
### 3️⃣ Install Dependencies
``` bash
pip install -r requirements.txt
```
## 🚀 Usage
- Exploratory Data Analysis (EDA)
Run the data_analysis.ipynb notebook to explore the dataset, visualize correlations, and gain insights.

## 🤖 Model Training
Use train.py or model_training.ipynb to train a Machine Learning model like Random Forest or XGBoost.

## 📈 Evaluation
After training, evaluate the model using evaluate.py or analyze performance metrics in the Jupyter notebook.

## 🎯 Results
The trained model predicts house prices based on given features, evaluated using metrics such as:

RMSE (Root Mean Squared Error)
MAE (Mean Absolute Error)
R² Score

## 🛠️ Technologies Used
- **Python**
- **Pandas**
- **NumPy**
- **Scikit-Learn**
- **Matplotlib & Seaborn**
- **XGBoost** 

## 🤝 Contributing
Contributions are welcome! Feel free to fork this repository and submit pull requests.

## 👤 Author
**Shalu Yadav**
