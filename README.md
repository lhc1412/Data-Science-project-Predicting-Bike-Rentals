# Predicting Bike Rentals

Many American cities have communal bike sharing stations where you can rent bicycles by the hour or day. Washington, D.C. is one of these cities. The District collects detailed data on the number of bicycles people rent by the hour and day.

In this project, I will create a few different machine learning models to predict the total number of bikes people rented in a given hour and evaluate their performance. The data set used in this project is from [Hadi Fanaee-T](http://www.liaad.up.pt/area/fanaee) at the [University of Porto](https://sigarra.up.pt/up/pt/web_base.gera_pagina?p_pagina=home). The file contains 17380 rows, with each row representing the number of bike rentals for a single hour of a single day. You can download the data from the [University of California, Irvine's website](http://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset).

## Summary of results

Three models have been created and MSE is used to evaluate their performances. We can see that Random forest model performs the best so far. But the difference between the MSE of training set and testing set is large. I consider the model is overfitted. It also appears in the Decision tree model.

## Further Study

Here are some potential next steps:

Calculate additional features, such as:
- An index combining temperature, humidity, and wind speed
- Try predicting casual and registered instead of cnt.
