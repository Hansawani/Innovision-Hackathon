# Problem Statement
On the basis of given Music Extravaganza dataset :
1. Divide the songs into various categories (pop, rock, country etc.)
2. What are the factors that contribute the most to the views of the song.

# Problem 1 Approach
Classification of songs according to genre is performed through Gaussian Mixture Models (GMMs) in order to identify natural clusters of audio features. This unsupervised technique enables the model to adjust itself better into the music's complex patterns. These clusters will be made from loudness, energy, speechiness, and such like patterning characteristics. Then, a rule-based mapping would assign music genres based on the mean of different features across clusters.

# Problem 2 Approach
We will conduct correlation analysis for numerical features and their linear relationship with Views. To ascertain feature importance through potential linear and non-linear dependencies, we will apply Random Forest. Hence, a combination of both methods will be used for optimization. 
For categorical features, we will use aggregation method to analyse impact of them on Views. Coupled with that, boxplots will visualize the variations across the different categories in a broad analysis.






