# Aquaculture-Machine-Learning-Practice

## Comparison & Reflection

Both datasets—Kaggle’s Fish Market and the synthetic aquaculture data—aim to predict fish characteristics but differ in scale and variability.  
In this work, I trained two classifiers (Logistic Regression and Random Forest) and two regressors (Linear Regression and Random Forest Regressor).  
Across both tasks, **Random Forest consistently outperformed linear models**, achieving higher accuracy and R² because it captures nonlinear relations between features such as length, height, and feeding rate.  
Linear models remained useful as interpretable baselines but could not model complex feature interactions.

For the **synthetic dataset**, results were stable and noise-free, while a real dataset would introduce imbalance and natural variation—important for testing generalization.  
Feature-importance analysis showed that morphometrics and feed rate dominate weight prediction, confirming realistic biological relationships.

In summary, Random Forest models are the best compromise between accuracy and interpretability for aquaculture prediction tasks, while linear models provide transparency and quick benchmarking.
