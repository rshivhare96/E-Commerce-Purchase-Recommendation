# E-Commerce Purchase Recommendation

This project focuses on understanding customer behavior and predicting purchase intent based on user demographics, preferences, and online activity. The goal is to build a robust classification model that can assist in personalized product recommendations and enhance user experience on e-commerce platforms.

---

## 📂 Data

The dataset simulates user profiles and online behavior including:

- **Demographic Information**: Age, Gender, Location, Marital Status, Income
- **Device & Preferences**: Preferred Device, Product Category
- **Behavioral Features**: Previous Purchase, Number of Products Bought, Visit Status
- **Target Variable**: `Purchased` (0 = No, 1 = Yes)

Simulated variables include:
- Visitor type (New/Returning)
- Number of products previously bought
- Purchase status (`purchased`)

This structured dataset helps build an effective recommender system prototype using classification techniques.

---

## 🔍 Analysis Workflow

The project is implemented in Python and follows these steps:

- Data simulation and cleaning  
- Label encoding for categorical variables  
- Exploratory Data Analysis (EDA) using plots and distributions  
- Correlation analysis and feature insights  
- Feature engineering (e.g., `bought_count`, `visitor`)  
- Model building using **Support Vector Machine (SVM)**  
- Model evaluation using classification metrics  

---

## ⚙️ Models Used

The following machine learning model is implemented:

- ✅ **Support Vector Machine (SVM)** (Linear Kernel)

Additional notes:

- Stratified train-test split to maintain class balance  
- Applied `LabelEncoder` for binary and categorical variables  
- Evaluation metrics include accuracy, classification report, and confusion matrix  

---

## 📊 Key Findings

- The model effectively classifies user purchase intent with basic simulated features  
- Visualization revealed insights into:
  - Income-based purchase patterns  
  - Product category preferences by gender  
  - Correlation between visitor type and purchase likelihood  
- Initial accuracy is promising but limited by simulated data variability

Future enhancements:
- Use real-world behavioral and transactional data  
- Explore collaborative filtering and hybrid recommender approaches  
- Add product-level metadata and time-based session data  

---

## 🛠️ Libraries Used

- **Data Manipulation**: `pandas`, `numpy`  
- **Visualization**: `matplotlib`, `seaborn`  
- **Machine Learning**: `scikit-learn`  
- **Feature Engineering**: `LabelEncoder`, `train_test_split`, `SVC`  

---

## 📁 Notebooks & Scripts

- `ecommerce_purchase_recommendation.ipynb`: Includes end-to-end workflow—EDA, feature engineering, model building, and evaluation.

---

## ✅ Usage

To run the analysis:

1. Clone the repository  
2. Open and run the `ecommerce_purchase_recommendation.ipynb` notebook  
3. Review the EDA visualizations and model output  

**Optional Enhancements**:
- Implement other models (e.g., XGBoost, Logistic Regression)  
- Add a collaborative filtering module (e.g., using user-item matrix)  
- Deploy using Streamlit or Flask for real-time demo  

---

## 👤 Author

**Rohit Shivhare**  
[LinkedIn](https://www.linkedin.com/in/rohit-shivhare-a857a4233/)  
*MSc Data Science – Brunel University, London*
