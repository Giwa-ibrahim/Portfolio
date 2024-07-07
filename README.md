## About Me

I am a recent graduate of Ladoke Akintola University of Technology (LAUTECH), where I studied Electronic and Electrical Engineering. With 1-2 years of experience in the Data Science field, I have undertaken several professional courses covering the basics of Data Analytics and Machine Learning. Presently, I am working as a research assistant at Bells University, Ota, due to my mandatory one-year youth service, which will be completed around September 2024.

My research interest lies in the use of Machine Learning and Embedded Systems technologies to solve energy-related problems. To date, I have successfully completed three projects related to renewable energy. I am seeking postgraduate scholarships to further enhance my knowledge and, in the long run, fulfill my potential.

## [Project 1: Wind Speed Prediction using LSTM Model](https://github.com/Giwa-ibrahim/Giwa_Portfolio/blob/main/Wind_Speed_Prediction_Model.ipynb)

This was a project I did for my Undergraduate Final year project.

Duration: 6 months (between Jan 2023 and July 2023).

**Project Goal**

Develop and simulate an efficient machine learning-based wind speed prediction model for renewable energy solutions to power telecommunication base stations in Nigeria. 

**Project Overview**

* Data was collected from the Nigerian Meteorological Agency (NIMET) and contained 10 years (2007-2018) of wind speed dataset from Kano state, Nigeria.
* Preprocessing steps such as Data cleaning and feature engineering were done.
* LSTM, ANN, GRU, and SimpleRNN models were used to train the models where LSTM outperformed other models based on the error metrics.
*  The LSTM hyperparameters such as the number of neurons, layers, timesteps, number of engineered features, optimizers, etc,  were iterated to optimize the accuracy of the model and were finally compared with other neural network variants.

### Performance of the LSTM Model

![](https://github.com/Giwa-ibrahim/Giwa_Portfolio/blob/main/Performance%20of%20LSTM.png?raw=true)

![Comparison of LSTM with other models](https://github.com/Giwa-ibrahim/Giwa_Portfolio/blob/main/Comaprison%20of%20LSTM%20with%20other%20models%20plot.png?raw=true)


## [Project 2: Energy Consumption Price Model](https://github.com/Giwa-ibrahim/Giwa_Portfolio/blob/main/Energy_Consumption_Price_Model.ipynb)

This was a virtual Hackathon project organized by Optimus AI Labs.

Duration: 5 days (between April 8th and April 12th, 2024).

**Project Scope**

Develop a User interface model for forecasting energy consumption for buildings, areas, or utilities, as well as predicting renewable energy output from sources such as wind turbines or solar panels, considering weather conditions and environmental factors.

**Project Overview**

* The dataset was sourced from Kaggle, which comprises two extensive sets spanning four years (2015-2018). It includes Consumption and Generation data, and Weather Features data from the five largest cities in Spain.
* Preprocessing techniques, such as removal of unnecessary columns and missing values, renaming of columns, merging of the both datasets via the date-time columns, checking for outliers, and feature engineering by transforming the date-time into hour, day, month and year columns.
*  Trained the dataset with the Random Forest (RF) Regression model which involves experimenting with various Machine Learning (ML) models including  LSTM, Random Forest, XGBoost, Gradient Boost, and AdaBoost, but RF model produced the least error metric with a Root Mean Square Error (RMSE) of 3.301.
*  The model was deployed using Streamlit library to ensure an easy access user interface as shown below.

### Performance of the Energy Consumption Model 

![](https://github.com/Giwa-ibrahim/Giwa_Portfolio/blob/main/Performance%20of%20Energy%20Consuption%20Predicted%20and%20actual%20price.png?raw=true)

### The User Interface Model Testing
![Model Testing Phase 1](https://github.com/Giwa-ibrahim/Giwa_Portfolio/blob/main/Model%20Deploy%20(1).png?raw=true)
![Model Testing Phase 2](https://github.com/Giwa-ibrahim/Giwa_Portfolio/blob/main/Model%20Deploy%20(2).png?raw=true)

## [Project 3: Predictive Power Transformer Maintenance using Random Forest Model](https://github.com/Giwa-ibrahim/Giwa_Portfolio/blob/main/Predictive_Transformer_Maintenance.ipynb)

This is a master's project I collaborated with my supervisor during my Mandatory one-year service at Bells University, Ota.

Duration: 2 months (between June and July 2024).

**Project Goal**

Design and simulate a predictive maintenance model for a 60 MVA power transformer at the Akangba 330kV/132kV transmission sub-station

**Project Overview**

* Data was collected from one of the 60MVA Power transformers at Akangba Transmission Substation (ATS) and contained 3 years (2021-2023) of breakdown and Preventive maintenance dataset.
* The preprocessing stage involves feature engineering where some necessary features were computed in order to derive the target variable in the form of binary classification using the mean and standard deviation of some features as a threshold.
* Tree-based models (such as RF, XGBoost, lightGBT, AdaBoost), and ANN models were used to train the models, which they all had the same accuracy (97%) but the RF classifier model was preferred because it outperformed other models based on its lesser computational time and minimal hyperparameter tuning.
*  The RF hyperparameters such as the number of estimators, Minimum Samples Split, Minimum Samples Leaf, Maximum Features, Maximum Depth, and, Bootstrap were tuned using the Random Search method to optimize the accuracy of the model and were finally compared with other tree-based and ANN model.

### Performance of the RF Model

![Confusion Matrix of the RF Model](https://github.com/Giwa-ibrahim/Giwa_Portfolio/blob/main/Confusion%20matrix%20report.png?raw=true)

![Predicted Maintenance with Date](https://github.com/Giwa-ibrahim/Giwa_Portfolio/blob/main/Predicted%20PT%20Maintenance.png?raw=true)


In case you want to reach out to me about the portfolio, work opportunities, or collaboration, feel free to contact me on:
    - [LinkedIn](https://www.linkedin.com/in/ibrahim-giwa-0718a9192/)
    - [Gmail](giwaibrahim98@gmail.com)

