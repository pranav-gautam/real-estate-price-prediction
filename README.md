# real-estate-price-prediction
In this project, we used Python, machine learning, and data science to predict the house prices of Bengaluru, India using the attributes provided by the user.

![BHP_website](https://user-images.githubusercontent.com/64377125/189205374-07270bbb-f399-401e-bca3-2eebd0e13f2a.PNG)

We started by getting a dataset of Bengaluru house prices from kaggle.com. Then we modified this dataset and built a model using sklearn and linear regression. The second step was to write a Python Flask server that uses the saved model to serve HTTP requests. Then we designed a website for the users using HTML, CSS, and JavaScript where they can enter the size (in square feet), number of bedrooms and bathrooms, and the location, and then this website calls the Python Flask server to retrieve the predicted price. During model building, we used numerous data science concepts: data load and cleaning, outlier detection and removal, feature engineering, dimensionality reduction, gridsearchCV, k-fold cross validation, etc.

Technology and tools wise, this project covers:

1) Python 
2) Numpy and Pandas for data cleaning 
3) Matplotlib for data visualization 
4) sklearn for model building 
5) Jupyter Notebook, Visual Studio Code, and PyCharm as an IDE 
6) python flask for HTTP server
7) HTML, CSS and JavaScript for UI

Hope you guys like this :)
