# World Happiness Report 2024 - Happiness Score Prediction

This project analyzes the World Happiness Report 2024 dataset to explore and predict happiness scores across countries based on socio-economic indicators. We applied exploratory data analysis (EDA), simple linear regression, and multiple linear regression techniques to understand how various features influence happiness levels.

## Dataset

- **Source:** World Happiness Report 2024
- **Key Columns Used:**
  - Log GDP per capita
  - Social support
  - Healthy life expectancy
  - Freedom to make life choices
  - Generosity
  - Perceptions of corruption
  - Dystopia + residual
  - Ladder score (Happiness score)

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow

1. **Importing Libraries**
2. **Loading and Exploring the Data** (EDA)
3. **Data Preprocessing**
   - Handling missing values
4. **Data Visualization**
   - Correlation heatmap
   - Distribution plots
   - Pair plots
   - Residual plots
5. **Simple Linear Regression**
   - Predicting Happiness Score using Log GDP per Capita
6. **Multiple Linear Regression**
   - Using multiple features to predict Happiness Score
7. **Model Evaluation**
   - Metrics: MAE, MSE, R² Score
8. **Conclusion**

## Results

- **Simple Linear Regression** indicated a positive relationship between GDP per capita and happiness score.
- **Multiple Linear Regression** provided a stronger model by incorporating multiple features.
- Residual analysis showed that while the model explains a significant portion of the variance, there are additional factors influencing happiness.

## Future Improvements

- Explore more complex models such as Random Forest, XGBoost, or Ridge Regression.
- Perform deeper feature engineering to enhance model performance.
- Apply clustering techniques to group countries with similar happiness profiles.

## Conclusion

GDP per capita, social support, healthy life expectancy, and freedom to make life choices significantly impact the happiness levels of countries. However, happiness is a multifaceted concept, and fully capturing it requires considering qualitative factors beyond numerical indicators.

