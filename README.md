# Transaction Fraud Detection
## Final Project - Santa Claus & Rudolph & the Dwarf

---

### 1. Group Information
* **Group Number:** [À compléter : Ex. Group 4]
* **Project Members:**
  * Julie Miquélajaurégui
  * Ecaterina Gupca
  * Noann Manon-Maza

---

### 2. Dataset Source & Description
* **Dataset Source URL:** https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
* **Description:** Every day, thousands of people fall victim to credit card fraud without even realizing it until it's too late. Behind each fraudulent transaction lies a real person dealing with unexpected charges, stressful disputes, and a shaken sense of financial security. This project aims to tackle this very real problem by building a machine learning system capable of automatically detecting suspicious transactions before they cause harm.

To do so, we will be working with the Credit Card Fraud Detection dataset available on Kaggle, which gathers over 280,000 real transactions made by European cardholders. Each transaction is described by numerical features derived from a PCA transformation — applied to protect users' privacy — along with the transaction amount and a binary label indicating whether it is fraudulent or not. One of the most interesting and challenging aspects of this dataset is its severe class imbalance: fraudulent transactions account for only about 0.17% of all records, which means our models cannot simply "play it safe" by predicting everything as legitimate.

---

### 3. Instructions for Running the Notebook
1. Clone the repository:
   ```bash
   git clone https://github.com/JulieMiquela/final_project.git
   cd final_project
   jupyter notebook Projet.ipynb
