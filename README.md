# Geosegmentation-model
The objective of this geodemographic segmentation model was to determine which customers are most likely to leave the bank.
Some Exploratory Data Analysis(EDA) was conducted to find patterns in the data or to locate any missing values if available.
The data was split into training and test data using ski-kit learn library.
The logistic regression algorithm was used to model the data and was tested using test data.
The model was refined by making use of the null hypothesis test to eliminate columns whose p-value was the highest and greater than 0.05 itteratively.
The performance of the refined model was evaluated by the Cumulative Accuracy Profile(CAP) curve, the confusion matrix and classification report.
According to the CAP curve, the model states that by reaching out to 50% of the customers, 80% of those are churners with be reached, which is a sign that the model is a gool model.
