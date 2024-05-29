# econ481-project

## Final Project Proposal

Presentation Date: May 29

Group 9 - Yuzhi Fu, Vicky Guo, Lesley Xu

1. **Your setting (any background that I might need to understand the question)**
   - This dataset presents data on a range of diamonds with different features such as size, clarity and prices. Variables take on both string and numerical values.
   - While variables such as “Carat” and “Price” are self-explanatory, categorical variables “Cut”, “Clarity” and “Color” require explanations:
     - For the “Cut” column, objects take on five string values ( “Fair”, “Good”, “Very Good”, “Premium”, “Ideal”, ranking from the worst to the best).
     - For the “Clarity” column, objects take on a range of string values (from left to right is worst to best: I1, SI2, SI1, VS2, VS1, VVS2, VVS1, IF).
     - For the “Color” column, objects take on a range of string values (from the letter J to D in alphabetical order, ranking from the worst to the best).
2. **What question(s) you want to answer**
   - What’s the distribution of data points and basic statistical summary in the dataset? i.e. minimum, median, mode, mean, maximum, interquartile range, etc.
   - What are the relationships between features of a diamond and price of a diamond?
   - Of all the explanatory variables, which ones have the largest effect on the price?
   - Among several models we choose, which model provides the most accurate price prediction?
3. **How you plan to answer these questions (what tests, what models, etc.)**
   - Models
     - Model 1 - Linear regression. We choose this model because we assume a simple linear relationship between explanatory variables and response variables.
     - Model 2 - Decision Tree based methods (Random Forest, and/or Gradient Boosting). We choose this model because it builds multiple decision trees and combines their predictions to improve accuracy.
   - Methods
     - We are planning on using LASSO for feature selection since it shrinks some coefficients to zero. We are planning on using Ridge regression to deal with multicollinearity among the features. Those two methods help to effectively mitigate overfitting.
     - We are planning on using a test train split and cross validation method to evaluate the performance of the models. This approach provides a more robust assessment of how well the model will perform on unseen data.
   - Metrics
     - Mean Absolute Error
     - Mean Squared Error
     - Root Mean Squared Error
     - R-squared
   - Presentation Components (TBD)
     - Clean & Process
     - Exploratory data analysis
     - Data visualization
4. **Your data acquisition strategy (link me to the dataset or how you'll get it)**
   [Link to Dataset](https://www.kaggle.com/datasets/amirhosseinmirzaie/diamonds-price-dataset)
