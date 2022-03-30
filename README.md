# Hotel-Booking-Cancellation

This notebook serves as an exercise project for supervised (classification) machine learning model building.

<p align="center">
<img src="https://github.com/b1llywitant0/Hotel-Booking-Cancellation/blob/main/Data/Hotel%20Header.jpg">
</p>


## Background
<p align='justify' style="font-weight: bold;">
Hotel usually prepares for the arrival of their customers. By giving them the best first impression, hopefully, it will increase the customer satisfactions that will lead to more profit and popularity for the hotel. However, how does the hotel distinguish which customers that will surely come? In this project, we will aid the hotel with booking cancellation prediction.
</p>

## Dataset Source
<p align='justify' style="font-weight: bold;">
This is a real-world data of customers, obtained from 2 hotels which are located in Portugal: Resort Hotel at the resort region of Algarve and City Hotel at the city of Lisbon. You can download it from <a href="https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand">Kaggle</a>. Because this project only serves as exercise, we will only use the first 5000 data and certain columns for the prediction model building.
</p>

## Data Cleaning and EDA
<p align='justify' style="font-weight: bold;">
Detailed data cleaning and EDA can be read at <a href="https://github.com/b1llywitant0/Hotel-Booking-Cancellation/blob/main/Supervised%20Model%20-%20Hotel%20Booking.ipynb">Jupyter</a>. 
</p>

## Prediction Results
### Benchmark Model
<p align="center">
<img src="https://github.com/b1llywitant0/Hotel-Booking-Cancellation/blob/main/Data/Hotel%20CV%20Results.png">
</p>
<p align='justify' style="font-weight: bold;">
Considering the mean score and its standard deviation, XGBClassifier was used.
</p>

### Hyperparameter Tuning
<p align='justify' style="font-weight: bold;">
Detailed hyperparameter tuning can be read at <a href="https://github.com/b1llywitant0/Hotel-Booking-Cancellation/blob/main/Supervised%20Model%20-%20Hotel%20Booking.ipynb">Jupyter</a>. 
</p>

### Test Data
<p align="center">
<img src="https://github.com/b1llywitant0/Hotel-Booking-Cancellation/blob/main/Data/Hotel%20Results.png">
</p>
<p align='justify' style="font-weight: bold;">
After hyperparameter tuning, this prediction model can identify which booking will be cancelled with good F1-score (0.8695).
</p>

# Conclusion
We can use this model to predict hotel booking cancellation of resort hotels in Portugal.
