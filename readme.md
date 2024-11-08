This project uses machine learning to predict the quality of red wines based on various chemical features such as alcohol content, acidity, pH, and more. The dataset used contains different attributes of wine that can help assess its quality. The goal is to build a predictive model that can be used by wine producers and distributors to make data-driven decisions regarding wine production, grading, and marketing.

To run this project, make sure you have the following Python libraries installed:

pandas
numpy
scikit-learn
matplotlib
seaborn
jupyterlab (for running Jupyter notebooks)
statsmodels

You can install all the depedencies using this line of code in your terminal
pip install -r requirements.txt

This project can be used by wineries to predict the quality of their wine based on its chemical properties. For example:

A winery may use this project to predict the quality of a wine batch before release, ensuring that only wines with the highest predicted quality reach consumers.
Wine distributors can use the model to assess the expected quality of wines from different producers and make better purchasing decisions.
Consumers can use the predicted quality scores to find wines that match their preferences.
Machine Learning Models
Random Forest: A robust ensemble model that is well-suited for high-dimensional data and provides feature importance.
Decision Trees: A simple and interpretable model for predicting wine quality.
Support Vector Machines: Another powerful model that works well for classification tasks.