# 🌶️ FlavorSense – Interpreting XGBoost with SHAP

This mini-project explores the **interpretability** of an **XGBoost** model using the **SHAP (SHapley Additive exPlanations)** algorithm.  
We use the [FlavorSense dataset](https://www.kaggle.com/datasets/milapgohil/flavorsense-tastes-predicted-by-life-and-climate), which predicts food taste preferences based on lifestyle and environmental factors.  

---

## 📊 About the Dataset
**FlavorSense** is a unique synthetic dataset designed to predict an individual's taste preference (**🍛 Spicy, 🍬 Sweet, 🍋 Sour, or 🧂 Salty**) based on:  
- 🏃 Lifestyle habits  
- 🛌 Sleep cycle  
- 🏋️ Exercise level  
- 🌍 Climate zone  
- 🍽️ Cultural cuisine exposure  

---

## 🛠️ Project Workflow
1. 🔎 **Exploratory Data Analysis (EDA)**  
   - 📈 Data inspection, distribution plots, and correlation analysis  
   - 🎨 Visualization of class balance and feature trends  

2. 🧹 **Data Preprocessing**  
   - ❌ Handling missing values  
   - 🔤 Encoding categorical variables  
   - 📏 Scaling numerical features  

3. 🤖 **Model Building with XGBoost**  
   - 🎯 Multi-class classification  
   - ⚙️ Hyperparameter tuning to improve accuracy & reduce overfitting  

4. 🧠 **Model Interpretation with SHAP**  
   - 🌍 **Global interpretation:** SHAP summary plots, feature importance  
   - 🔍 **Local interpretation:** Dependence plots, force plots for single predictions  

---

## 📥 Dataset Access

You can use the dataset directly from Kaggle by following these steps:

### 📝 Step 1: Get Your Kaggle API Key
1. 🔗 Go to your [Kaggle account settings](https://www.kaggle.com/settings)  
2. 🖱️ Scroll to the **API** section and click **Create New Token**  
3. 💾 This will download a `kaggle.json` file to your computer  

![Kaggle API Download](https://github.com/user-attachments/assets/e084dfa0-889e-43bd-8702-cc914a89c947)

---

### 📤 Step 2: Upload API Key to Your Notebook
Run this cell in your notebook and select the downloaded `kaggle.json` file:

![Upload kaggle.json](https://github.com/user-attachments/assets/35596a94-42cb-4cc2-96ca-9e085449c14b)

---

### ⬇️ Step 3: Download the Dataset
Use the Kaggle API command to download and unzip the dataset:

![Kaggle download example](https://github.com/user-attachments/assets/d5199934-5b36-43d2-824b-0457070b9266)
