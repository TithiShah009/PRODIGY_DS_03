# 🌸 Customer Purchase Prediction with Decision Trees  

This project focuses on building a **Decision Tree Classifier** that predicts whether a customer will purchase a product or service.  
The dataset used is the **Bank Marketing Dataset** from the UCI Repository.  

---

## 📂 Dataset
Dataset link: [Click Here](https://github.com/Prodigy-InfoTech/data-science-datasets/tree/main/Task%203)  

It contains customer details like:  
- Age, Job, Marital Status, Education  
- Account Balance, Contact Type  
- Past Campaign Interaction  

---

## 🪄 Workflow
1. Imported dataset using **pandas**.  
2. Dropped unneeded features (like `duration`).  
3. Converted categorical variables to numerical using **get_dummies()**.  
4. Split dataset into training (80%) & testing (20%).  
5. Built a **Decision Tree Model** using scikit-learn.  
6. Evaluated with accuracy score.  
7. Visualized correlations with a **heatmap**.  

---

## 📊 Insights
- The Decision Tree was able to predict purchasing decisions fairly well.  
- This approach can help companies improve **marketing campaigns**.  

---

## 🛠 Tools Used
- Python 🐍  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

---

## ✨ Improvements
- Experiment with different depths & criteria.  
- Compare with Random Forest or Logistic Regression.  
- Perform feature importance ranking.  

---

🌼 This project was completed as part of my **Data Science Internship at Prodigy InfoTech**.
