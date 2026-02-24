# AI-Driven Drug Discovery: Non-Sedating Antihistamines
This project uses Machine Learning to identify potent H1-antihistamines with low Blood-Brain Barrier (BBB) permeability to minimize sedation.

## 🚀 Overview
- **Objective:** Screen compounds for high pIC50 and optimal TPSA/LogP values.
- **Data Source:** ChEMBL Database.
- **Key Tools:** Python, RDKit, Scikit-learn.

## 🛠️ Methodology
1. **Data Acquisition:** Extracted 400+ compounds from ChEMBL.
2. **Feature Engineering:** Calculated LogP, TPSA, and Molecular Weight.
3. **Modeling:** Trained a Random Forest Classifier (Accuracy: 100% on test set).
4. **Virtual Screening:** Identified top candidates passing Lipinski's Rule of Five.

## 📊 Results
- Successfully classified 1st and 2nd generation antihistamines.
- Identified several lead compounds as potential candidates for further research.

## 🧪 How to Run
Open the `.ipynb` file in Google Colab and upload the raw ChEMBL CSV file.

