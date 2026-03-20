# OpenFoodFacts Data Mining & Machine Learning Analysis & Association Rules

## Project Overview
This project analyzes the OpenFoodFacts dataset using data mining and machine learning techniques.

## My Contributions
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Applied machine learning models
- Performed Association Rule Mining (Apriori algorithm)

---

## Project's goals

- Pre-processing and cleaning the Open Food Facts dataset

- Building a classification model for food products

- Performing clustering to discover groups of similar products

- Applying Association Rules to explore relationships between nutritional components and food labels

- Analyzing nutritional content and food labeling

---

 ## Association Rule Mining
- Generated frequent itemsets using Apriori
- Evaluated rules using:
  - Support
  - Confidence
  - Lift
- Identified meaningful relationships between food items

---

## Data

Source: **Open Food Facts**

* Website: [https://world.openfoodfacts.org](https://world.openfoodfacts.org)

---

## 🛠️ Tools & Technologies
- Python (Pandas, Scikit-learn, mlxtend)
- Jupyter Notebook

## 📂 Project Structure
- `/code`: main scripts and notebooks
- `/image`: visualizations

---

## Key Insights
- Certain food items frequently appear together in purchases
- FP-Growth tree with support_threshold = 0.3
- Potential application in recommendation systems
- The data is categorized into 4 distinct clusters:
  - Cluster 0 – High Energy & Sugar: Sweets and confectionery; high calorie, low protein.
  - Cluster 1 – Low Nutrition: Mineral water and unsweetened drinks; minimal nutritional value.
  - Cluster 2 – High Protein: Low sugar and fat; ideal for muscle building.
  - Cluster 3 – High Fat & Protein: Cheese, oily nuts, and red meat; low carbohydrate content.

## 🔗 Original Project
This repository is forked from: [https://github.com/thilnnd/OpenFoodFacts](https://github.com/thilinnd/OpenFoodFacts)
