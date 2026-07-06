# final_project

# Santa Claus & Rudolph

## Project Members : Julie Miquélajaurégui, Ecaterina Gupca, Noann Manon-Maza
## Project Title : Transaction Fraud Detection
## Project summary : 
Every day, thousands of people fall victim to credit card fraud without even realizing it until it's too late. Behind each fraudulent transaction lies a real person dealing with unexpected charges, stressful disputes, and a shaken sense of financial security. This project aims to tackle this very real problem by building a machine learning system capable of automatically detecting suspicious transactions before they cause harm.
To do so, we will be working with the Credit Card Fraud Detection dataset available on Kaggle, which gathers over 280,000 real transactions made by European cardholders. Each transaction is described by numerical features derived from a PCA transformation — applied to protect users' privacy — along with the transaction amount and a binary label indicating whether it is fraudulent or not. One of the most interesting and challenging aspects of this dataset is its severe class imbalance: fraudulent transactions account for only about 0.17% of all records, which means our models cannot simply "play it safe" by predicting everything as legitimate.
Throughout the project, we will follow a complete data science workflow — from exploratory data analysis and visualization, to handling class imbalance using techniques such as SMOTE or under-sampling, to training and comparing at least three classification models: Logistic Regression, Random Forest, and a third model such as XGBoost or KNN. Given the nature of the problem, we will rely on metrics that go beyond simple accuracy, including precision, recall, F1-score, and AUC-ROC, which better reflect real-world performance in imbalanced settings.
Beyond the technical work, we believe it is essential to reflect on the human and ethical dimensions of such a system. What happens when a legitimate transaction gets flagged as fraud and a customer's card is blocked? What biases might the model carry? These are the kinds of questions we intend to address seriously in our responsible AI discussion, because building a good model is not just about performance — it is also about the people it affects.

