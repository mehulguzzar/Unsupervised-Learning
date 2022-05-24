# Unsupervised-Learning

Implementation of the various unsupervised learning techniques using the Playstore games dataset

We have been provided with a dataset which consists of the list of games which are available to download on the Google Playstore for the Android OS. The dataset consists of the game title, along with other metadata which includes the google playstore ranking, the total number of ratings received, number of installs, avergae rating, the rate of growth in the initial days and the ratings received in the different start categories.

This dataset does not have a target variable by itself, so we will proceed with the analysis of the dataset by applying certain unsupervised learning algorithms to make sense of any pattern or meaningful information which can be obtained from the data at hand. We will also try to apply supervised learning algorithms at a later stage, when we have an idea about the cluster formation which can be obtained from the dataset.

The dataset consists of 1730 rows and 15 columns as described below:

rank: The rank of the game in Google Playstore title: The title of the game total ratings: The total number of ratings received by the game installs: The total number of times the game has been installed average rating: The average of all the ratings received by the game growth (30 days): The percentage growth in the first 30 days since upload growth (60 days): The percentage growth in the first 60 days since upload price: The price incurred to play the game category: The category to which the game belongs 5 star ratings: The number of 5 star ratings received by the game 4 star ratings: The number of 4 star ratings received by the game 3 star ratings: The number of 3 star ratings received by the game 2 star ratings: The number of 2 star ratings received by the game 1 star ratings: The number of 1 star ratings received by the game paid: Is the game paid or free
