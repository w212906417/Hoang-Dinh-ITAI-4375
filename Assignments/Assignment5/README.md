# Assignment 5: Critiquing a Prognostic Model

## 📌 Overview
This assignment focuses on critically evaluating a prognostic model designed to predict in-hospital mortality within 28 days in neonates with heart failure.

The project examines how the model was developed, its statistical performance, and its real-world clinical usefulness. It also highlights key challenges such as bias, overfitting, confounding variables, and generalizability—important considerations in both healthcare and AI model deployment.

## 🎯 Objectives
- Understand how prognostic models are developed and evaluated  
- Analyze model performance using metrics such as AUC (Area Under the Curve)  
- Identify strengths and weaknesses in clinical prediction models  
- Evaluate real-world applicability and limitations  

## 🧠 Learning Process
In this assignment, I analyzed a published prognostic model and evaluated both its methodology and practical implications.

The learning process involved:
- Understanding **neonatal heart failure** and its clinical risks  
- Studying statistical techniques such as:
  - Least Absolute Shrinkage and Selection Operator (LASSO) regression  
  - Multivariable logistic regression  
- Interpreting performance metrics like:
  - AUC (Area Under the Receiver Operating Characteristic Curve)  
  - Negative predictive value  
- Identifying issues such as:
  - Confounding by treatment variables  
  - Retrospective study bias  
  - Limited generalizability  

This helped me develop a deeper understanding of how models perform beyond just numbers.

## ⚙️ Technologies & Concepts
- Prognostic Modeling  
- Logistic Regression  
- LASSO Regression  
- Model Validation (Internal & External)  
- AUC (Area Under the Curve)  
- Calibration and Discrimination  
- Bias and Overfitting  

## 🚀 Implementation (Model Evaluation)
The assignment evaluates a prognostic model with the following characteristics:

### 🔹 Prediction Goal
- Predict 28-day in-hospital mortality in neonates with heart failure  

### 🔹 Model Features
- Based on 7 key predictors including:
  - Clinical indicators (e.g., oliguria, postnatal response)  
  - Laboratory values (e.g., fibrinogen levels)  
  - Treatment variables (e.g., medications)  

### 🔹 Model Performance
- Training AUC: 0.87  
- Internal validation AUC: 0.83  
- External validation AUC: 0.85  

These values indicate **good discrimination ability**.

## 📊 Results & Outcomes
- The model demonstrates strong ability to identify **high-risk patients**  
- External validation increases confidence in model reliability  
- However, limitations were identified:
  - Low negative predictive value (weak at identifying low-risk patients)  
  - Potential confounding due to treatment-related variables  
  - Limited generalizability (data from specific regions only)  

## ⚖️ Strengths vs Limitations

### ✅ Strengths
- Multicenter dataset  
- External validation included  
- Systematic feature selection (LASSO)  
- Simple and interpretable scoring system  

### ⚠️ Limitations
- Retrospective study design (risk of bias)  
- Confounding by indication (treatment variables)  
- Limited applicability across different populations  
- No prospective validation  

## 💡 Key Takeaways
- High model accuracy does not guarantee real-world effectiveness  
- External validation is critical but not sufficient alone  
- Simpler models (e.g., logistic regression) are often preferred in healthcare due to interpretability  
- Clinical models must always be used alongside human judgment  

## 🔮 Future Improvements
- Conduct prospective validation studies  
- Test model across diverse populations and healthcare systems  
- Remove or adjust treatment-related confounders  
- Explore machine learning approaches for improved predictive performance  
- Integrate model into EHR systems for real-time decision support  

## 📚 References
See original assignment document for full reference list and sources.
