## Predicting the Number of Subscriber for 10k Development Courses from Udemy
Reem Bin Obaidan

## Abstract:
The goal of this project was to use regression models to predict the number of subscriber for 10k Development Courses from Udemy in order to help job seekers who want to develop their skills in web development, mobile development, programming languages, game development, database design, and software testing by taking the most appropriate course. Also, it can be used by employers for improving their employees’ skills. 
I worked with data provided by kaggle [https://www.kaggle.com/jilkothari/udemy-courses-development], leveraging plotting and with regression model to achieve promising results predicting the number of subscriber. 

## Design:
This dataset originates from the kaggle [https://www.kaggle.com/jilkothari/udemy-courses-development]

## Data:
The dataset contains 9933 Development Courses with 17 features for each,A few feature highlights include:course ID ,course title
,course url ,number of subscribers ,average rating ,number of reviews ,number of published lectures ,number of published practice tests ,Time of publishing the course ,discounted price ,and The original price of a particular course.
## Algorithms:

*Feature Engineering*

Reformat 'created'feature  ,which displays the time of creation of the course. and 'published_time' feature, which displays courses' published date as a datetime object .

*Models*

Support Vector Regression, Linear Regression, Random Forest Regressor, Kernel Ridge Regression, Gradient Boosting Regression, and Elastic Net Regression.
Linear Regression,Kernel Ridge Regression ,Elastic Net Regression are strongest cross-validation performance where R-squared arround 0.835. 

*Model Evaluation and Selection*

The entire training dataset of 9933 records was split into 80/20 train vs. test, and all scores reported below .

**Final test score:**

**Linear Regression** R_squerd: 0.834927       RMSE:14024.971312

**Kernel Ridge Regression** R_squerd:0.835146  RMSE:14015.631563

**Elastic Net Regression** R_squerd:0.834880   RMSE:14026.944374



## Tools:
- Numpy and Pandas for data manipulation
- Scikit-learn for modeling
- Matplotlib and ploty for plotting


## Communication:
slides and visuals presented.
