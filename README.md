# ARTI308-Lab7
 **Ad Click Prediction Project**

 **Overview**
The purpose of this project is to determine whether a user is likely to click on an online advertisement by analyzing their demographic details and browsing behavior. A Logistic Regression model was developed using a synthetic dataset to classify user actions with high reliability.

 **The Dataset**
The dataset contains multiple attributes describing user activity and characteristics, including:

* **Daily Time Spent on Site** – Number of minutes a user spends on the website
* **Age** – User’s age in years
* **Area Income** – Mean income of the user’s geographic region
* **Daily Internet Usage** – Average time spent online per day (minutes)
* **Ad Topic Line** – Headline of the advertisement
* **City** – City where the user is located
* **Male** – Gender indicator (1 = male, 0 = female)
* **Country** – User’s country of residence
* **Timestamp** – Time of user interaction with the ad
* **Clicked on Ad** – Outcome variable (1 = clicked, 0 = not clicked)

 **Exploratory Data Analysis (EDA)**
Several visualization techniques were used to better understand the dataset:

* Histograms were used to observe the distribution of user age
* Joint plots helped examine the relationship between age and area income
* Scatter-based analysis explored the link between time spent on the site and internet usage
* Pair plots categorized by ad-click behavior highlighted differences between users

 **Data Preparation**
The model focused on key numerical features:

* Age
* Area Income
* Daily Time Spent on Site
* Daily Internet Usage

The dataset was split into two parts:

* Training data (67%)
* Testing data (33%)

 **Model**

* Model type: Logistic Regression
* Implemented using: Scikit-Learn
* Modification: Increased the number of iterations (`max_iter`) to ensure the model converges properly

 **Performance**
The model delivered strong classification results:

* Accuracy: 97%
* Precision: 0.98
* Recall: 0.96
* F1-Score: 0.97

 **Tools and Libraries**

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

**Conclusion**
The Logistic Regression model proved to be highly effective in predicting advertisement click behavior. The selected input features successfully captured user patterns, resulting in accurate and well-balanced performance metrics.
