# Well Functionality In Tanzania

## Project Overview
This project aims to predict the operational status of water wells in Tanzania using machine learning models. The goal is to improve water resource management by proactively identifying wells that are likely to fail.

## Business Problem
Access to clean drinking water is a critical challenge in Tanzania due to failing water wells. Many wells have been installed, but maintenance and repairs are inefficient. This project helps predict well failures to enhance decision-making.

## Data Overview
- **Dataset:** Contains attributes related to well characteristics, location, depth, and water quality.
- **Key Features:**
  - Well status (Functional, Non-functional, Needs Repair)
  - Geographic location
  - Construction year and depth
  - Water quality indicators
- **Data Source:** Publicly available well data records from [Taarifa](http://taarifa.org/) and [Tanzania Ministry of Water](http://maji.go.tz/) .

## Methodology
1. **Exploratory Data Analysis (EDA):** Understanding the dataset through visualization and summary statistics.
2. **Feature Engineering:** Selecting and transforming important variables for better model performance.
3. **Model Training:** Implementing machine learning models to classify well functionality.
4. **Evaluation:** Assessing the model's accuracy, precision, recall, and overall performance.

## Results
- **Model Performance:** Best Performing Model: XGBoost with Hyperparameter Tuning
- Confusion Matrix: Shows fewer misclassifications compared to other models
- ROC-AUC: High values indicate strong classification performance
  
## Visualizations
- For better business understanding, the following visualizations were created in Tableau:
  [View Tableau Dashboard](https://public.tableau.com/views/Book2_17413502549780/AnalysisofWellFunctionalityinTanzania?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
  
## Recommendations
- Focus maintenance efforts on wells predicted to fail.
- Improve resource allocation using predictive insights.
- Continuously update the model with new well data to improve accuracy.

 
See the full analysis in the Jupyter Notebook or review this Presentation.

 For additional information contact:

* [Diana Ogeto] at [dianaogeto0@gmail.com].
