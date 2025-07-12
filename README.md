#✈️ Flight Price Prediction using Machine Learning

This project aims to **predict the price of flight tickets** based on various input features like airline, source, destination, departure time, duration, etc. The dataset used is stored in `Flight_Booking.csv` and the modeling is done in the Jupyter Notebook `FlightPricePrediction.ipynb`.

---

### 📁 Project Structure

FlightPriceProject/
├── FlightPricePrediction.ipynb # Jupyter notebook for EDA and ML modeling
├── Flight_Booking.csv # Raw dataset containing flight details
└── README.md # Project documentation


---

### 📊 Dataset: `Flight_Booking.csv`

The dataset contains flight booking details including:

- **Airline**
- **Source and Destination cities**
- **Departure and Arrival times**
- **Duration**
- **Total stops**
- **Price**

> 📌 Note: The dataset may need preprocessing like date-time conversion, handling missing values, and encoding categorical features.

---

### ⚙️ Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (Linear Regression, Random Forest, Decision Tree)
- Jupyter Notebook


### 📈 Key Steps in Notebook

1. **Data Cleaning**: Converted dates and times, handled null values  
2. **Feature Engineering**: Extracted useful info from timestamps, created new variables  
3. **Encoding**: One-Hot Encoding for categorical columns  
4. **Model Building**: Trained Linear Regression, Random Forest, etc.  
5. **Model Evaluation**: Checked accuracy, RMSE, R² Score


### 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/sahithimeneni06/FlightPricePrediction.git
   cd FlightPricePrediction



### 📊 Dataset: `Flight_Booking.csv`

The dataset contains flight booking details including:

- **Airline**
- **Source and Destination cities**
- **Departure and Arrival times**
- **Duration**
- **Total stops**
- **Price**

> 📌 Note: The dataset may need preprocessing like date-time conversion, handling missing values, and encoding categorical features.


### ⚙️ Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (Linear Regression, Random Forest, etc.)
- Jupyter Notebook


### 📈 Key Steps in Notebook

1. **Data Cleaning**: Converted dates and times, handled null values  
2. **Feature Engineering**: Extracted useful info from timestamps, created new variables  
3. **Encoding**: One-Hot Encoding for categorical columns  
4. **Model Building**: Trained Linear Regression, Random Forest, etc.  
5. **Model Evaluation**: Checked accuracy, RMSE, R² Score


### 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/sahithimeneni06/FlightPricePrediction.git
   cd FlightPricePrediction
2. Open FlightPricePrediction.ipynb in Jupyter Notebook

3. Run all the cells step by step to see data cleaning, analysis, model training, and prediction
