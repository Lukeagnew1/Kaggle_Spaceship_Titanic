# Kaggle_Spaceship_Titanic

https://www.kaggle.com/competitions/spaceship-titanic/data

This Kaggle competition is comrised of creating a binary classification model for predicting survival or non survival among passengers on the "titantic spaceship". Participants are given features and a label, the features include many different variables such as: 

PassengerId - A unique Id for each passenger. Each Id takes the form gggg_pp where gggg indicates a group the passenger is travelling with and pp is their number within the group. People in a group are often family members, but not always.
HomePlanet - The planet the passenger departed from, typically their planet of permanent residence.
CryoSleep - Indicates whether the passenger elected to be put into suspended animation for the duration of the voyage. Passengers in cryosleep are confined to their cabins.
Cabin - The cabin number where the passenger is staying. Takes the form deck/num/side, where side can be either P for Port or S for Starboard.
Destination - The planet the passenger will be debarking to.
Age - The age of the passenger.
VIP - Whether the passenger has paid for special VIP service during the voyage.
RoomService, FoodCourt, ShoppingMall, Spa, VRDeck - Amount the passenger has billed at each of the Spaceship Titanic's many luxury amenities.
Name - The first and last names of the passenger.
Transported - Whether the passenger was transported to another dimension. This is the target, the column you are trying to predict.

The label, the outcome our model is to predict, is either True or False, indicating whether passengers survived the space voyage. 

After Data Preprocessing, Mining, and Final Preperations for Model Building, i tested a 

- Decision Tree Classifier
- XG Boost Classifier
- Random Forest Classifier
- Supported Vector Machine (SVM) Classifier 
- Logistic Regression Classifier 
- Naive Bayes Classifier 

Ended up going with a 3 layered Random Forest Algorithm for my predictions 
