# Heart Disease Prediction 

This project predicts whether a person has heart disease or not based on health features such as age, cholesterol, blood pressure, etc.  

I used two models:  
- **Logistic Regression** → simple and interpretable  
- **Random Forest** → more powerful, can capture non-linear patterns  

---

## Dataset
The dataset contains patient health information with the target variable:  
- `0` → No heart disease  
- `1` → Heart disease present  

---

## Steps
1. Data preprocessing (cleaning + splitting into train/test).  
2. Model training: Logistic Regression and Random Forest.  
3. Evaluation using accuracy, classification report, and ROC curve.  
4. Feature importance visualization from Random Forest.  

---

## Results
- Logistic Regression → decent accuracy, easy to interpret.  
- Random Forest → performed better in accuracy.  
- ROC curve showed Logistic Regression still had a strong AUC.  
- Feature importance gave insights on which health factors matter more.  

---

## Conclusion
Random Forest turned out stronger overall, but Logistic Regression is easier to explain to others. Both models are useful depending on the goal.  

---

## How to Run
1. Clone the repo  
   ```bash
   git clone https://github.com/yogya111/heart-disease-prediction.git
