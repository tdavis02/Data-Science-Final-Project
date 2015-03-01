# Data-Science-Final-Project
final project for data science course General Assembly LA 

Yelp Ratings and Useful Vote Count - Final Project
by Taylor Renee Davis

This project was influenced by research examining approach/avoidance content in American versus Japanese Amazon reviews and decision making. Approach versus avoidance content indicates the amount of positive or negative sentiment expressed in the review, for example "This book was unclear and poorly organized" would be considered avoidance content. When evaluating book reviews, there is a difference in the type of information that Americans and Japanese found helpful. Reviews rated as helpful in the United States contained a greater amount of approach content than avoidance content whereas avoidance content was viewed as especially unhelpful for book reviews among Americans but not among Japanese

The hypothesis for the current project was "does star rating predict more useful vote counts on Yelp reviews?"

Linear Regression was the chosen analysis based on the 1 continous predictor variable x 1 continuous outcome variable set up. There were some problems with setting up the analysis which led to implementing Sklearn-pandas found on GitHub. 

Sklearn-pandas is a bridge between Scikit-Learn's machine learning methods and pandas-style Data Frames. In particular, it provides a way to map DataFrame columns to transformations, which are later recombined into features and cross-validate a pipeline that takes a pandas DataFrame as input. This was used after trying to run Linear Regression in sklearn was leading to errors, as stated above. 

Conclusion: still working on fixing errors and fitting regression model. Results are inconclusive at the moment. 

Implementation: Identifying informative reviews; reviews whose text best “explains” the hidden factors of a product are rated as being useful. If useful vote count is predicted by review attributes like star count, this creates potential for a new way of sorting reviews on Yelp. The current ways to sort reviews are limited to Yelp sort, date, rating, and elites. Providing new ways to sort reviews could help Yelp users quickly and efficiently find the information they are looking for. 
