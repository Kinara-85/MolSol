# MolSol

# Solubility Prediction Using Machine Learning

## Overview
This project predicts the solubility (logS) of molecules using machine learning models, specifically **Linear Regression** and **Random Forest Regressor**. Solubility is crucial for biologists and chemists to determine whether a molecule can dissolve in water or a solvent, which is important for drug discovery.

## Dataset
The dataset used in this project contains molecular descriptors and their corresponding solubility values (**logS**). It is obtained from **Data Professor**:
[Delaney Solubility Dataset](https://github.com/dataprofessor/data/blob/master/delaney_solubility_with_descriptors.csv).

## Project Workflow
1. **Load Dataset**: Read the CSV file into a Pandas DataFrame.
2. **Data Preprocessing**: Split the dataset into input features (**X**) and the target variable (**y**).
3. **Train-Test Split**: Split the data into training (80%) and testing (20%) sets.
4. **Model Training**: Train both **Linear Regression** and **Random Forest** models on the training data.
5. **Model Evaluation**: Compare model performance using metrics like Mean Squared Error (MSE) and R² score.
6. **Data Visualization**: Plot predicted vs. actual solubility values.

## Dependencies
Ensure you have the following Python libraries installed:
```bash
pip install pandas numpy scikit-learn matplotlib
```

---
### Author
**Kinara-85**  
For questions or improvements, feel free to contribute! 🚀

