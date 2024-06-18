# Pitch Sequence Predicting
Wouldn't it be awesome if we could have a reliable source to go to when guessing upon what pitch will come next?

This project was a very very rough attempt at applying machine learning to a tale long task of predicting the next pitch of an at-bat. 

### The Model
The model takes in a couple years worth of data from a specific pitcher and the hitters he faced. Their at-bats are preprocessed and are trained into a model to predict the next pitch of an at-bat based on the pitches that come before it.

### Issues
- This kind of model needs a sigificant amount of data that currently there might not be enough for yet
- It's going to take time to find the right features and probably many features need to be engineered to make it even close to having some truth to it

## Previous work by others
This came up with this idea one day not knowing that someone by the name of Connor Turner and his peers had created a model like this with tens of thousands of pitches and still the model was on average 50% correct. 50% is still a significant amount considering the best
MLB players get a hit 30% of the time. I believe the most correct for any one pitcher they had was Josh Hader.

## Next Steps
A lot more data needs to be included in the model and a significant amount of preprocessing but this type of model could potentially be used to help hitters make better swing decisions and in turn create more production.
