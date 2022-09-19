# hyland-hakathon

It contains 8 attributes, of which 7 are chemical pollution quantities and one is Air Quality Index. PM2.5-AVG, PM10-AVG, NO2-AVG, NH3-AVG, SO2-AG, OZONE-AVG are independent attributes. air_quality_index is a dependent attribute. Since air_quality_index is calculated based on the 7 attributes.

As the data is numeric and there are no missing values in the data, so no preprocessing is required. Our goal is to predict the AQI, so this task is either Classification or regression. So as our class label is continuous, regression technique is required.

Regression is supervised learning technique that fits the data in a given range. Example Regression techniques in Python:

Random Forest Regressor
Ada Boost Regressor
Bagging Regressor
Linear Regression etc.
