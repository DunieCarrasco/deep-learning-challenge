# deep-learning-challenge
**Overview**

The purpose of this analysis is to develop a machine learning model to select the a fictitious charitable organization for funding with the best chance of success in their ventures. The dataset from the nonprofit foundation Alphabet Soup containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. That data contains information about application type, affiliation, classification, use case for funding, organization type, active status, income, special considerations, funding amount requested and if it was considered successful for each applicant.

The goal is to use this data to develop a model that can accurately predict which charitable organization will be successful, in order to help Alphabet Soup make more informed decisions about which charitable organization applications to approve. Specifically, we will be using a binary classification model to predict whether the funding will be approved or not.

The analysis involves several steps, including data cleaning and preprocessing, feature engineering, model selection and training, and evaluation of model performance. The end goal is to develop a model that can accurately predict funding success based on the available data, and to use this model to inform future funding approval decisions.

**Results**
* Data Preprocessing
 * What variable(s) are the target(s) for your model?
   - My target in my model is IS_SUCCESSFUL data 
 * What variable(s) are the features for your model?
   - My variables in my model is 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', 'USE_CASE',
       'ORGANIZATION', 'STATUS', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS',
       'ASK_AMT' data.
 * What variable(s) should be removed from the input data because they are neither targets nor features?
   - Variable that I removed from the data where "EIN", "NAME" as they were neither targets nor features.

* Compiling, Training, and Evaluating the Model
 * How many neurons, layers, and activation functions did you select for your neural network model, and why?
   - For the neural network model developed for this classification problem, I selected a total of four layers, with 80 neurons in the first layer, 30 neurons in the second layer, and 10 neurons in both the third and output layers.
 * Were you able to achieve the target model performance?
   - I was not able to achieve the target goal of above 75% accuracy.

**Summary**

The deep learning model developed for this classification problem achieved an accuracy score of approximately 72%. While this is better than random guessing, it is not a particularly high accuracy score and there is likely room for improvement.

One potential approach for improving the model's performance is to try a different algorithm, such as a Random Forest model. These algorithms have been shown to perform well in a wide range of classification problems and may be better suited to the particular features of this dataset.
