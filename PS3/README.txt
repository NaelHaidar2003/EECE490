Mortality Rate Predictor
Hey! This is a neural network I built that predicts mortality rates. It's pretty straightforward - you give it some historical death rate data and it tries to figure out patterns to make predictions.
What it does:

Takes in mortality data from a CSV file
Processes the data to work with the neural network
Trains a model to predict death rates
Shows you some graphs of how well it's doing
Gives you prediction results

How to use it:

Make sure you have a CSV with mortality data (needs Year column + age group columns)
Run the main script
It'll train the model and show you the results

The code handles all the complicated stuff like scaling the data and splitting it into training/validation sets. It'll also save the best version of the model automatically