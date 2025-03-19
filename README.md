# GA SIM: Sleep Health and Lifestyle

## Project Overview
This project explores the relationship between sleep health and lifestyle factors using a dataset containing various attributes such as sleep duration, quality of sleep, physical activity level, stress level, and heart rate. The analysis includes data cleaning, exploratory data analysis (EDA), statistical analysis, and machine learning modeling.

## Author
**Supriya Tandukar**

## Dataset
The dataset used in this project is **Sleep_health_and_lifestyle_dataset.csv**, which includes:
- Sleep Duration (hours)
- Quality of Sleep (rating scale)
- Physical Activity Level
- Stress Level
- Daily Steps
- Heart Rate
- BMI Category
- Gender
- Occupation
- Sleep Disorder

## Project Components
### 1. Data Preprocessing
- Loaded the dataset and checked for missing values.
- Identified and handled duplicate rows.
- Converted categorical variables to factors.

### 2. Exploratory Data Analysis (EDA)
- Visualized the distribution of sleep duration.
- Analyzed the quality of sleep by gender.
- Explored physical activity levels by occupation.
- Assessed stress levels across different BMI categories.
- Created a correlation matrix of numerical variables.

### 3. Statistical Analysis
- Performed ANOVA to assess differences in sleep quality by occupation.
- Conducted a Chi-Square test to examine the association between gender and sleep disorder.
- Built a linear regression model to predict sleep quality.
- Evaluated model performance using RMSE, MAE, and R-squared metrics.

### 4. Model Training & Evaluation
- Split data into training and testing sets.
- Built and evaluated a multiple linear regression model.
- Applied cross-validation for better generalization.

### 5. Feature Importance
- Identified key features influencing sleep quality.
- Visualized feature importance using bar plots.

## Dependencies
Ensure you have the following R libraries installed before running the code:
```r
install.packages("dplyr")
install.packages("ggplot2")
install.packages("caret")
install.packages("tidyr")
install.packages("corrplot")
install.packages("plotly")
install.packages("knitr")
```

## Running the Code
1. Clone this repository.
2. Load the required libraries.
3. Ensure the dataset is in the correct file path.
4. Run the R script to execute data analysis and visualization.

## Results
- Sleep duration and physical activity levels significantly impact sleep quality.
- Stress levels vary across different BMI categories.
- The regression model helps predict sleep quality with reasonable accuracy.

## Outputs
The following visualizations are generated and saved:
- Sleep Duration Distribution (`sleep_duration_distribution.png`)
- Quality of Sleep by Gender (`quality_of_sleep_by_gender.png`)
- Physical Activity by Occupation (`physical_activity_by_occupation.png`)
- Stress Level by BMI (`stress_level_by_bmi.png`)
- Correlation Matrix (`correlation_matrix.png`)
- Actual vs Predicted Quality of Sleep (`actual_vs_predicted_quality_of_sleep.png`)

## License
This project is open-source and available under the [MIT License](LICENSE).

## Contact
For any questions or contributions, feel free to reach out to Supriya Tandukar.

