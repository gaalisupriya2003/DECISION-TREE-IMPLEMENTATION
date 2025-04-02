# DECISION-TREE-IMPLEMENTATION

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: GALI SUPRIYA

**INTERN ID**:CT12WJVC

**DOMAIN**: MACHINE LEARNING

**BATCH DURATION**:JANUARY 5TH TO APRIL 5TH,2025

**MENTOR NAME**:NEELA SANTHOSH 

# Wine Classification Using Decision Trees  

Decision trees are powerful supervised learning algorithms used for classification and regression tasks. They provide clear decision-making structures, making them highly interpretable and useful for real-world applications. This project implements a **Decision Tree Classifier** on the **Wine dataset** to classify wine types based on chemical composition. The goal is to build a **decision tree model**, evaluate its performance, and visualize the decision rules to understand classification behavior.  

## Tools and Technologies Used  
- **Programming Language:** Python  
- **Machine Learning Library:** Scikit-learn  
- **Data Handling:** Pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn  
- **Decision Tree Visualization:** `plot_tree()` from Scikit-learn  

## Dataset and Preprocessing  
The **Wine dataset**, available in Scikit-learn, consists of:  
- **178 wine samples** categorized into three distinct wine varieties.  
- **13 chemical attributes** including alcohol, acidity, and phenol content.  

Preprocessing steps included:  
1. **Loading the dataset** and inspecting its structure.  
2. **Splitting the data** into **80% training (142 samples)** and **20% testing (36 samples)** for evaluation.  
3. **Feature Scaling (if necessary):** Though decision trees handle raw data well, ensuring a balanced feature distribution aids better decision-making.  

## Model Building and Training  
We implemented a **DecisionTreeClassifier** using Scikit-learn with these settings:  
- **Criterion:** Gini impurity to measure node purity.  
- **Maximum Depth:** Set to **4** for interpretability and balanced accuracy.  
- **Splitting Strategy:** Automatically selects optimal features at each split.  

The model was trained on the **training set**, learning key patterns that distinguish different wine types based on chemical properties.  

## Performance Evaluation  
The trained model was evaluated on the **test set**, yielding the following results:  
1. **Model Accuracy:** **94% (0.94)**, indicating strong classification performance.  
2. **Classification Report:**  
   - High **precision, recall, and F1-scores** across all three wine types.  
   - Well-balanced performance, effectively distinguishing different varieties.  
3. **Confusion Matrix:**  
   - Few misclassifications, proving good generalization capabilities.  

## Decision Tree Visualization and Insights  
Using **plot_tree()**, we visualized the decision tree, which revealed:  
- **Key Features:** Alcohol and flavonoid content were the most critical predictors.  
- **Decision Paths:** Showed how different wines were classified based on their attributes.  
- **Interpretability:** Enabled understanding of why certain wines were categorized differently.  

## Applications of Wine Classification  
1. **Wine Quality Control:** Ensures wines meet quality standards before distribution.  
2. **Automated Sorting in Wineries:** Helps classify wine batches during production.  
3. **Recommender Systems:** Suggests wines to consumers based on chemical analysis.  
4. **Research in Chemistry:** Assists in understanding the relationship between wine composition and classification.  
5. **Counterfeit Detection:** Verifies wine authenticity in the food industry.  

## Conclusion  
This project demonstrates how decision trees can effectively classify wine types with **94% accuracy** while maintaining high interpretability. The decision tree model allows for **easy visualization**, helping researchers and winemakers understand which features contribute to wine classification. By leveraging Scikit-learn’s tools, we achieved a reliable and explainable machine learning model, making it useful for real-world applications in wine assessment, production, and consumer recommendations.
