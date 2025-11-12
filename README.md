# Medical-Insurance-Cost-Prediction


# 🩺 Medical Insurance Cost Prediction

This project predicts **medical insurance costs** based on various health and lifestyle factors using **Machine Learning (Linear Regression)**.  
It focuses on understanding how features like **age, BMI, smoking habits, and region** affect insurance charges.

---

## 📊 Dataset
The dataset used: `insurance.csv`  
**Features include:**
- `age` – Age of the individual  
- `sex` – Gender of the policyholder  
- `bmi` – Body Mass Index  
- `children` – Number of dependents  
- `smoker` – Whether the individual smokes or not  
- `region` – Residential area  
- `charges` – Medical insurance cost (Target Variable)

---

## ⚙️ Tech Stack
- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**

---

## 🧠 ML Process
1. **Data Preprocessing**
   - Handling categorical variables (sex, smoker, region)
   - Encoding using LabelEncoder / OneHotEncoder  
   - Removing duplicates & checking null values

2. **Exploratory Data Analysis (EDA)**
   - Visualized age vs charges, BMI vs charges  
   - Found strong correlation between **smoking** and **costs**  
   - BMI range analysis (Healthy BMI = 18.5–24.9)

3. **Model Building**
   - Train-test split (80:20)  
   - Applied **Linear Regression** to predict insurance costs  
   - Evaluated with **R² score** and **Mean Absolute Error (MAE)**  

4. **Results**
   - The model accurately predicted insurance costs with a good R² score.  
   - Strong positive impact of **smoking** and **higher BMI** on premium costs.

---

## 🚀 How to Run
```bash
git clone https://github.com/yourusername/Medical_Insurance_Cost_Prediction.git
cd Medical_Insurance_Cost_Prediction
pip install -r requirements.txt
jupyter notebook Medical_Insurance_Cost_Prediction.ipynb
