# Mercedes-Benz-Greener-Manufacturing

Project Title: Mercedes-Benz Greener Manufacturing

Project Description:

In the pursuit of optimizing manufacturing processes and contributing to greener practices, the Mercedes-Benz Greener Manufacturing project aims to predict the time it takes for a car to pass testing. The dataset comprises various features, including binary and categorical variables, with the target variable "y" representing the testing time in seconds.

The project initiates with a comprehensive data preprocessing phase, where irrelevant features, such as those with a constant value of 0, are identified and removed. This meticulous data-cleaning process ensures that only meaningful information is utilized in subsequent analyses.

Exploratory Data Analysis (EDA) and data visualization techniques are employed to gain insights into the relationships between different features and the testing time. The exploration particularly focuses on the categorical features, among which "X0" emerges as a significant contributor to the target variable.

The modelling phase employs a sophisticated approach using TPOT (Tree-based Pipeline Optimization Tool) to automatically discover the most effective machine learning pipeline for predicting testing times. The generated models undergo multiple iterations (generations), with the best-performing model evolving over each generation.

The current best internal cross-validation scores indicate the efficacy of the RandomForestRegressor model, revealing its potential for accurate predictions. The model is fine-tuned with parameters such as bootstrap, max_features, min_samples_leaf, min_samples_split, and n_estimators, resulting in improved performance.

One noteworthy observation from the outcomes is the impact of certain categorical features on the target variable. In particular, "X0" exhibits the highest effect, emphasizing its significance in predicting testing times.

To enhance the model's understanding of categorical features, an encoding strategy using Scikit-learn's MultiLabelBinarizer is implemented. This technique transforms categorical levels into numerical representations, creating new features that contribute to the overall predictive power of the model.

In summary, the Mercedes-Benz Greener Manufacturing project not only aims to predict testing times accurately but also endeavors to uncover insights into the influence of categorical features. By leveraging advanced modeling techniques and encoding strategies, the project aligns with Mercedes-Benz's commitment to sustainable manufacturing practices and continuous improvement in production processes.
