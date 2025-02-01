# Week2
This project focuses on predicting solar power output by building a machine learning model using linear regression. The model estimates solar power generation based on key environmental and operational factors such as temperature, sunlight intensity, and panel orientation.

1. Introduction
This report summarizes the progress of the solar power prediction model using linear regression. The goal is to predict the amount of power generated (in kW) based on various environmental and operational features.

2. Data Exploration & Preprocessing
- The dataset was loaded from 'solar power dataset.csv'.
- Initial exploratory analysis showed that the dataset contains multiple numerical features.
- Summary statistics and data structure were analyzed using `.describe()`, `.info()`, and `.shape()`.
- Missing values and duplicate records were checked and handled appropriately.
- Data visualization techniques (histograms, scatter plots) were applied to understand feature distributions and relationships.

3. Model Development
- The dataset was split into training and testing sets.
- A linear regression model was trained using key predictive features.
- Feature selection was performed based on correlation analysis.

4. Model Performance Evaluation
The model was evaluated using the following metrics:
- Mean Absolute Error (MAE): Measures the average absolute errors in predictions.
- Mean Squared Error (MSE): Evaluates the squared differences between actual and predicted values.
- R² Score: Assesses how well the model explains the variance in power generation.

5. Observations & Insights
- The model showed moderate performance, indicating that linear regression captures some trends in the data but may not account for all complexities.
- Some features may exhibit non-linear relationships, requiring more advanced models such as polynomial regression or machine learning approaches.

6. Next Steps & Recommendations
- Improve feature engineering by incorporating additional environmental factors.
- Explore alternative regression models, such as decision trees or random forests, to improve accuracy.
- Fine-tune hyperparameters and experiment with feature scaling to enhance model performance.

Conclusion
The linear regression model provides a basic but effective starting point for solar power prediction. Further refinements and experimentation with more advanced techniques could enhance predictive accuracy for real-world applications.
