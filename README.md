# 💎 Diamond Price Prediction (Machine Learning Project)

This project predicts the **price of a diamond (or cubic zirconia)** using Machine Learning based on important features such as **carat, cut, color, clarity, depth, table, x, y, z**.

The project is built using a complete ML pipeline approach including:

✅ Data Ingestion  
✅ Data Transformation  
✅ Model Training  
✅ Model Evaluation  
✅ Saving Best Model  

---

## 📌 Dataset Information

The dataset used in this project is:

📄 **cubic_zirconia.csv**

### Columns Used
| Feature Name | Description |
|------------|-------------|
| carat | Weight of the diamond |
| cut | Quality of the cut (Fair, Good, Very Good, Premium, Ideal) |
| color | Diamond color grade (D to J) |
| clarity | Diamond clarity grade |
| depth | Total depth percentage |
| table | Width of the top of the diamond |
| x | Length in mm |
| y | Width in mm |
| z | Depth in mm |
| price | Target variable (Diamond Price) |

---

## 🎯 Project Goal

To build a machine learning model that can accurately predict the **diamond price** based on given features.

---

## 🏗️ Project Workflow

### 1️⃣ Data Ingestion
- Reads the dataset from `cubic_zirconia.csv`
- Splits it into **train and test datasets**
- Saves the split data into the artifacts folder

### 2️⃣ Data Transformation
- Handles missing values (if any)
- Encodes categorical columns (`cut`, `color`, `clarity`)
- Scales numerical features (`carat`, `depth`, `table`, `x`, `y`, `z`)
- Saves the preprocessing pipeline as a `.pkl` file

### 3️⃣ Model Training
- Trains multiple regress
🧠 Machine Learning Models Used

This project trains and compares multiple regression models such as:

Linear Regression

Ridge / Lasso Regression

ElasticNet

The best performing model is selected automatically.

🚀 Future Improvements

Add Flask / Streamlit UI for live predictions

Hyperparameter tuning using GridSearchCV

Add CI/CD pipeline for deployment

Deploy on AWS / Render / HuggingFace Spaces

