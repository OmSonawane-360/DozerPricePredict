# 🚜 Bulldozer Price Prediction using Machine Learning  
## 🚜 Project Name = DozerPricePredict

Predicting the sale price of bulldozers using historical data and machine learning techniques.  
This project is based on the **Kaggle Bluebook for Bulldozers Competition**, where the goal is to forecast the auction sale price of bulldozers based on their characteristics and past sales records.  
 
---  

## 📖 Project Overview     
 
In this notebook, we go through an **end-to-end machine learning project** where we:       
- Use bulldozer characteristics (make, model, year, size, drive system, state of sale, etc.)  
- Analyze **historical auction data** to predict **future bulldozer prices**  
- Apply **regression techniques** with a time-series component (forecasting problem)   
- Evaluate model performance using **Root Mean Squared Log Error (RMSLE)**  

👉 This project demonstrates how machine learning can be applied in **real-world predictive modeling** tasks.  

---

## 📊 Dataset  

The dataset comes from the **Kaggle Bluebook for Bulldozers competition**. It contains **sales data of bulldozers** with 50+ attributes.  

- **Train.csv** → ~400,000 sales up to 2011 (with target variable `SalePrice`)  
- **Valid.csv** → ~12,000 sales between Jan 2012 – Apr 2012  
- **Test.csv** → ~12,000 sales between May 2012 – Nov 2012 (no `SalePrice`, used for prediction)  

🔗 [Dataset on Kaggle](https://www.kaggle.com/c/bluebook-for-bulldozers/data)  

---

## ⚙️ Problem Type  

- **Regression Problem** → Predicting continuous numerical values (Sale Price in USD)  
- **Time Series/Forecasting Problem** → Since predictions are based on past sales data with time components  

---

## 🧮 Evaluation Metric  

The evaluation metric for this competition is:  

**📌 Root Mean Squared Log Error (RMSLE)**  

- RMSLE is useful when the target variable (`SalePrice`) has a **wide range of values**.  
- The lower the RMSLE, the better the model performance.  

---

## 🔑 Features  

Some important features include:  

- `YearMade` → Year the bulldozer was manufactured  
- `ModelID` → Unique identifier for the bulldozer model  
- `Enclosure` → Type of cab (e.g., enclosed cab, open cab)  
- `MachineHoursCurrentMeter` → Usage hours logged on the machine  
- `SaleDate` → Date of sale (time-based feature)  
- `SalePrice` → Target variable (only in Train & Valid datasets)  

📌 A full **data dictionary** is provided in the Kaggle competition.  

---

## 🛠️ Tools & Libraries Used  

- **Python** 🐍  
- **Pandas** → Data manipulation  
- **NumPy** → Numerical computations  
- **Matplotlib / Seaborn** → Data visualization  
- **Scikit-Learn** → Machine Learning models & evaluation  
- **Fastai** → Feature engineering & advanced ML techniques  

---

## 🚀 Workflow  

1. **Data Exploration** → Understanding dataset, missing values, distributions  
2. **Feature Engineering** → Handling categorical variables, date-time features, missing data  
3. **Model Building** → Regression models (Random Forest, Gradient Boosting, etc.)  
4. **Evaluation** → Using RMSLE to validate results  
5. **Prediction** → Generating sale price predictions on unseen Test set  

---

## 📌 Results  

- Implemented regression-based ML models  
- Optimized using RMSLE  
- Demonstrated real-world predictive modeling for heavy equipment sales forecasting  

---

## 🔮 Future Improvements  

- Try **deep learning models** (e.g., TabNet, Neural Networks)  
- Perform **hyperparameter tuning** for better accuracy  
- Explore **stacked/ensemble models** for further performance boost  
- Deploy as a **web app/dashboard** for business use  

---

## 🙌 Acknowledgements  

- [Kaggle Bluebook for Bulldozers Competition](https://www.kaggle.com/c/bluebook-for-bulldozers)  
- [Fast.ai Machine Learning Course](https://course.fast.ai/ml) for inspiration and techniques  

---

## 🧑‍💻 Author  

👤 **[Om Sonawane]**  
- 🌐 Passionate about **Machine Learning, Data Science, and AI applications**  
- 💻 Explore more projects on my [GitHub Profile](https://github.com/OmSonawane-360)  

---
