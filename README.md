# Airbnb-Listing-Classification

#### Technologies Used - R(Caret, dplyr, ggplot, e1071), Shiny 

#### The project uses Airbnb listing data to learn what sort of housing options are available in what part of New York City and what are the different kinds of amenities they have. There are multiple features in the dataset like number of reviews, the price, etc. After balancing the dataset and deducing that 98% of the data lies between $0 and $2000 I seggregated the listings into different classes according to the price. Then classification models like decision trees, Naive Bayes and SVM were built on the data I had. Finally, I developed a Shiny app where if you input all the features the best model runs in the background and predicts the class of the listing you are looking for. This can be used by Airbnb users anytime to check what category does the price of the listing fall in if they are looking to stay in NYC.
