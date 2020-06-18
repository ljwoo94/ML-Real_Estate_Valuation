# ML-Real_Estate_Valuation

Real Estate Valuation prediction by using Kernel Ridge Regression model.<br>
A project to accomplish Assignment2 of Machine Learning course in Yonsei University

Used Data Set:
<a>https://archive.ics.uci.edu/ml/datasets/Real+estate+valuation+data+set</a>

## Installation (Environment)
  
*To Read / Write Excel File*<br>

    pip install pandas

*To Use Machine Learning Model in Scikit-Learn*<br>
<a>https://scikit-learn.org/stable/install.html#installation-instructions</a>

    pip install -U scikit-learn

*For Easier Visualization of Graphs*<br>

    pip install seaborn
    
*To Visualize map*<br>

    pip install folium

*If you want to get your own temperature data*<br>
<a>https://openweathermap.org/</a>

    pip install pyowm
    
## Process
**1. Data Analysis including normality and correlations.**<br>
**2. Feature Engineering process**<br>
 > Normalize hyperparameter<br>
 > Add Temperature according to latitude and longitude<br>
 > K-means Clustering<br>
 > Omit outliers<br>

**3. Merge Data set after feature engineering to make best sub set**<br>
**4. Conclusion**

## Reference
[BaseLine][BaseLine]

[Application of Geographical Data][Geo]

[BaseLine]:https://www.kaggle.com/chocozzz/house-price-prediction-eda-updated-2019-03-12

[Geo]:https://www.kaggle.com/tmheo74/geo-data-eda-and-feature-engineering#Baseline-Model
