# An Analysis of Hotel Reservations
Are reservation cancelations and no-shows predictable? 
How can hotels combat this this problem?

## Introduction to Problem
In today’s day and age, ho
tels have a reservation paradox on their hands.  Ideally, a hotel wants to fill every room they have every night in order to maximize their profits.  Most people have their travels planned, so hotels cater to this by offering reservations for their hotel rooms.  Of course, hotels run into the inevitable problem: travel plans change.  Hotels are required to walk a fine line.  If every room is reserved for a future night, what are they supposed to do if they believe they will have cancellations or no shows?  Do they overbook in anticipation of this phenomenon?  
Andrew and I set out to come to the aid of hotels hoping to address this problem.  We are going to analyze a dataset of hotel reservations to see if we can predict if a reservation will follow through and stay the allotted nights, if they will cancel their reservation, or if they will not show up without any explanation.  We plan to develop a model that could look at future reservations and help hotel managers predict what the guest will end up doing.  Ideally this could help them overbook just the right number of rooms so that when people cancel or no-show, the hotel is not left with empty rooms generating no revenue.  
In addition to using our model to predict future reservation outcomes, we also plan to use it to find insights into what kind of things make people more likely to cancel or not show up.  This information could be used to find ways to better accommodate guests before their stay even begins, hopefully reducing cancellation rates and improving the customer’s experience.

## Data Background
The data is lots of information about a certain hotel reservation.  The 30 explanatory variables include information on the date of the hotel stay, the lead time in which the booking was made, information about the guest, including previous history, the number of guests staying with them, and if they are traveling with child or not.  Our target variable is the outcome of the reservation and has three possible responses.  The guest showed up for their reservation and has now checked-out, the guest canceled their stay prior to arriving, or the guest was a no-show (having neither shown up nor gone through the proper cancelation process).
This dataset was originally made public here: https://www.sciencedirect.com/science/article/pii/S2352340918315191#f0010

## Method and Results
Coming very soon...

## Influential Variables
After finding the model with parameters, we wanted to explore what parameters were most influential.  We began by creating a new random forest model, but this time we used all the data available, instead of splitting any into a train and test set.  After creating this model, we used the function feature_importances_ to find the impurity decrease value for each explanatory variable in our model.  A higher value indicates that it is more important in our model than variables with lower values. 

## Conclusion
Also coming soon

