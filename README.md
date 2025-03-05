# 💰 Predicting Insurance Costs  

## 📌 Overview  
This project focuses on building a **predictive model for insurance costs** based on demographic and health-related factors such as **age, BMI, smoking habits, and region**. By applying **machine learning regression techniques**, the goal is to help **insurance providers estimate policyholder expenses** more accurately, leading to better pricing strategies and risk assessment.

## 📂 Files in This Repository  
- **📄 Predicting_Insurance_Costs.pdf** – Project report detailing methodology, model evaluation, and findings.  
- **📜 Predicting_Insurance_Costs_NB.ipynb** – Jupyter Notebook containing **data preprocessing, feature engineering, model training, and evaluation**.  
- **📁 final_models_data.pkl** – Serialized trained models for making predictions on new data.  
- **📜 README.md** – Project documentation providing an overview.  

## 🛠️ Key Steps Taken  

### 1️⃣ Data Collection & Preprocessing  
- ✅ Used a dataset containing **features like age, BMI, number of dependents, smoking status, and region**.  
- ✅ Handled missing values, normalized numerical features, and encoded categorical variables.  
- ✅ Performed exploratory data analysis (EDA) to understand **correlations between features and insurance costs**.  

### 2️⃣ Model Selection & Training  
- ✅ Implemented **Linear Regression, Decision Trees, and Random Forest Regressors** for predicting insurance charges.  
- ✅ Fine-tuned hyperparameters using **GridSearchCV** to optimize model performance.  
- ✅ Evaluated models using **Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² score**.  

### 3️⃣ Model Evaluation & Insights  
- 📌 **Smoking status has the highest impact on insurance costs**, with smokers paying significantly higher premiums.  
- 📌 **Age and BMI are strong predictors**, indicating that older individuals and those with higher BMI incur higher expenses.  
- 📌 **Random Forest Regression outperformed other models** in predicting insurance costs accurately.  

### 💡 Business Impact  
- 📊 **Personalized Pricing** – Helps insurance companies adjust premiums based on risk factors.  
- 🔍 **Better Risk Assessment** – Allows insurers to identify high-risk policyholders.  
- 💰 **Improved Customer Segmentation** – Enables offering tailored insurance plans for different customer groups.  

