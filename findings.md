1)  Which insights did you gain from your EDA? Were any columns
    highly correlated? If so, name them.

    in my analysis of the EDA, I found correlations between  certain variables. Specifically, there was a correlation between 'music' and 'release date', indicating that certain types of music were more prevalent during specific periods of time. 

    ii. lastly, I observed a strong correlation between 'dating' and 'romantic', suggesting a relationship between dating-related themes and romantic themes in the song.

2)  How did you determine which columns to drop or keep? If your EDA
    informed this process, explain which insights you used to determine
    which columns were not needed.

    In my EDA analysis, I conducted a value counts analysis on all of the columns to identify which columns were unnecessary for this dataset. 
    
    Based on this analysis, I discovered a correlation between certain columns that needed to be dropped.
    
    Therefore, I decided to drop the "lyrics" and "len" columns because they did not contain relevant information for further analysis.

3)  What was the optimal number of clusters in your cluster model?
    Explain how you determined this value

    The optimal number of clusters in our cluster model was 8. This suggestion  was made using the silhouette score metric, which measures the proximity of data points to their assigned clusters relative to other clusters. By calculating the silhouette score for total numbers of clusters, we identified the number that maximizes this metric, indicating better clustering results.

4)  Take a look at the respective songs that fell into your clusters.
    Describe these clusters in human terms to the best of your ability
    using the columns in your dataset (for example high-gospel songs,
    low-gospel songs, etc). Feel free to listen to these songs as well to
    get a sense of what nuance your algorithm picked up on.

    After listening to the song, it was described that it falls into the category of low-gospel songs because the lyrics do not match with the themes associated with family and gospel songs.

5)   Take a look at the clusters that your algorithm assigned to your test
    samples. Based on these clusters, which songs would you
    recommend to this user?

    Based on these clusters, it appears that sadness will be the primary recommendation among users, as indicated by the algorithm.



