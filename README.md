# Earthquake-Prediction-Model-using-Machine-Learning
Earthquake Prediction Model using Machine Learning. Important : predicting the earthquake with date and time, latitude and longitude from previous data is not a trend that follows like other things, it happens naturally.
The unix time stamp is a way to track time as a running total of seconds. This count starts at the Unix Epoch on January 1st, 1970 at UTC. Therefore, the unix time stamp is merely the number of seconds between a particular date and the Unix Epoch.
We know that if a disaster occurs in one region, it is likely to happen again.Some regions have frequent earthquakes, but this is only a comparative amount compared to other regions.
Tecniques used: Dense layer, neurons - 32, 'SGD' optimizer, unix timer,epochs-10,loss='squared_hinge',keras.callbacks.EarlyStopping,patience = 3
Evaluation result on Test Data : Loss = 0.5301416516304016, Accuracy = 0.9293473958969116
X = data_final[['latitude','longitude','TimeStamp_f']] # Input data
y = data_final[['depth','mag']] # Output data
