# 🏀 NBA Points Prediction using K-Nearest Neighbors (KNN)

This project uses the K-Nearest Neighbors (KNN) algorithm to predict the total number of points scored by NBA players in the 2013–2014 season. It involves preprocessing player statistics, applying machine learning, and evaluating model performance using regression metrics.

---

## 📁 Dataset

- **Source**: `nba_2013 (1).csv`
- **Description**: Contains statistical data of NBA players from the 2013 season including:
  - Field goals (`fg`), Assists (`ast`), Rebounds (`trb`), 3-pointers (`x3p`), Free throws (`ft`), etc.
  - Target variable: `pts` — total points scored in the season.

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Libraries: 
  - `pandas`, `numpy` for data handling
  - `scikit-learn` for machine learning (KNN)
  - `matplotlib`, `seaborn` for data visualization

---

## 📊 Steps Involved

1. **Data Loading**  
   Load and inspect the NBA dataset.

2. **Data Cleaning**  
   - Handle missing values.
   - Drop non-numeric or irrelevant columns if necessary.

3. **Feature Selection**  
   - Input features: All numeric stats except `pts`
   - Target variable: `pts`

4. **Model Training**  
   - Train-test split (80-20)
   - KNN Regressor with `k=5`

5. **Evaluation**  
   - Metrics: Mean Squared Error (MSE), R² Score
   - Visualization: Scatter plot of actual vs predicted points

---

## 📈 Sample Output

Mean Squared Error: 38934.21
R² Score: 0.72


![Prediction Plot](#) *(insert actual plot image if desired)*

---

## 📂 Folder Structure

nba_knn_project/
│
├── nba_2013 (1).csv # Dataset file
├── NBA_KNN.ipynb # Jupyter Notebook with code
└── README.md # Project documentation


---

## 🚀 Future Improvements

- Try other regression algorithms (e.g., Linear Regression, Random Forest)
- Perform feature scaling for better KNN performance
- Tune `k` using cross-validation

---

## 📬 Contact

Created by **Sarthak**  
For academic or learning purposes.
