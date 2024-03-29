# Playground
**Featuring Python Notebooks from the analyses conducted by Maryam Agahi.** 
* Please note GitHub doesn't support intra-notebook linking directly, and clicking on links may redirect you to the repository itself.

## Project 1. EDA_FoodHub
**Description:** The data from a company named FoodHub (similar to Doordash and UberEats) is used to analyze the demand for different restaurants and identify ways to enhance customer experience.
*  **Challenges:**
    * Determining when to perform in-depth analyses versus when to maintain a higher-level overview
    * Conducting univariate and bivariate analyses for all critical fields and their combinations was time-consuming.
    * Incorporating business acumen is crucial for guiding data scientists in focusing on relevant factors.
*  **Improvement Opportunities:**
    * I would Invest more time upfront to carefully plan the analysis in a strategic and efficient approach.
    * Creating template notebooks for common analyses can streamline the process and improve efficiency.
 

## Project 2. ML_Classification_Potential Customer Prediction
**Description:**  Analyze and build ML models to identify which leads are more likely to convert to paid customers for an early stage EdTech startup. The goal was to find the factors driving the lead conversion process and create a profile of the leads which are likely to convert.

* **Challenges:**
  * Selecting the correct values for hyperparameters can be challenging and requires some trial and error, which can be time-consuming, especially for someone newer to machine learning.
  * Building ML models demands a lot of patience, as there is a necessity to iterate through the model-building process until the desired outcome is achieved.

*  **Improvement Opportunities:**
   * One adjustment I might consider is strategically limiting the number of features used in the machine learning model. Although this wasn't a significant concern in the current analysis due to the manageable size of the feature set, a more focused approach based on exploratory data analysis (EDA) could enhance model runtime efficiency.


## Project 3. ML_Classification_Customer Satisfaction Prediction
**Description:** The goal of the problem is to predict whether a passenger was satisfied or not considering his/her overall experience of travelling on the Shinkansen Bullet Train.

* **Challenges:**
  * The large number of features in the set makes traditional exploratory analysis tedious, not scalable, and, in some sense, inconclusive.
  * This exercise was part of a Hackathon in which the only feedback on prediction performance data was accuracy score. Not having visibility into deeper insights on model performance makes iteration a bit more challenging.

*  **Improvement Opportunities:**
   * For the sake of exercise, I did not perform any feature selection for Logistic Regression Models, which is also evident in the lower-performing model. This also resulted in longer training time, which is not scalable for production use cases. At a minimum, some features could be filtered out.
