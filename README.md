# Dataset Description
## Overview
### This dataset provides detailed information about 600 samples of wine, including their chemical properties, sensory characteristics, and overall quality ratings. The aim is to analyze the relationships between the physical and chemical attributes of wine and their perceived quality, as rated on a scale of 1 to 10. Key features include acidity levels, sugar content, sulfur dioxide concentration, alcohol percentage, and descriptors such as wine type (e.g., White, Port, Rose) and taste profile (e.g., Balanced, Earthy, Sour). These attributes are commonly used to evaluate wine quality and identify factors that influence consumer preferences. The data is a mix of numerical and categorical columns, with a few missing values in fields like name, citric acid, total sulfur dioxide, and Taste. This makes it an excellent resource for building a machine learning model to predict wine quality.

## Columns

- **id**: Unique identifier for each wine.
- **name**: Name of the wine (e.g., Chardonnay, Merlot).
- **fixed acidity**: Level of fixed acids in the wine.
- **citric acid**: Amount of citric acid present.
- **residual sugar**: Amount of sugar left after fermentation.
- **chlorides**: Chloride (salt) levels in the wine.
- **total sulfur dioxide**: Total amount of sulfur dioxide, a preservative in wine.
- **density**: The density of the wine, often related to alcohol and sugar content.
- **sulphates**: The level of sulphates that influence wine preservation and aroma.
- **alcohol**: Alcohol content in the wine.
- **type**: Type of wine (e.g., Red, White, Rose, Port).
- **Taste**: Subjective taste classification (e.g., Balanced, Sour, Earthy).
- **Temp**: Temperature at which the wine was measured.
- **quality**: Quality rating (binary: 0 or 1).
<br>

----

<br>

## Best Model:
### KNN was the best model for this dataset because wine quality is influenced by multiple numerical factors like acidity, alcohol, and sulphates, which makes distance-based classification highly effective. Unlike models that assume linear relationships, KNN naturally captures complex, non-linear patterns. KNN remains efficient without overfitting. Its ability to classify wines based on similarity leads to higher accuracy compared to models that rely on strict mathematical assumptions.

## Reasons

### 1. Hyperparameter Tuning for Optimal K  
- We test different **K values (1 to 40)** and plots an **Error Rate vs. K Value** graph.  
- The best **K value (e.g., 25 or 30)** was chosen where the error rate was minimized.

### 2. Strong Performance in Classification  
- The **confusion matrix** and **classification report** show that KNN achieved high accuracy.  
- **Accuracy scores were printed**, confirming KNN’s superior performance.

### 3. KNN’s Strengths for This Dataset  
- Wine quality depends on **numerical features** (acidity, alcohol, sulphates), making **distance-based classification** effective.  
- KNN **does not assume a linear relationship**, unlike Logistic Regression.  
- With only **600 samples**, KNN remains computationally efficient.


---


