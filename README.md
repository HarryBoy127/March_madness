Project Overview
This project was to  to provide a dataset  of all the songs  from 1950 to 2019. describing the music metadata columns: Track Name, artist_name, datinf violence, world/life , night /time, family and gospel, romantic, family/romantic, violence, dating. in this project we are going to create a  machine learning pipeline to analysze a datasets of the songs and lyrics content  in the music. The pipeline includes steps such as exploratory data analysis (EDA),  data cleaning, pre-processing, & dimensionality analysis,Model creation, hyperparameter search, and model evaluation and New Sample Prediction.

Project Structure

The project follows a structured approach with the following notebooks:

Initial EDA:

Conduct univariate, bivariate, and multivariate exploratory analysis.
Formulate hypotheses based on insights gained from the analysis.
Explore relationships between predictors and the target variable.
Data Cleaning and Pre-processing:

Clean and wrangle the dataset.
Handle missing values, outliers, and incorrectly formatted data.
Drop unnecessary columns based on EDA findings.
Save the pre-processed dataset for further analysis.
Model Creation and Evaluation:

Model Creation and Evaluation:
implement a KMeans Clustering or any other clustering algorithm.
evaluate the best number of clusters using one of the cluster identification techniques
save these cluster-labels as a new column in your dataframe
save this dataframe for further analysis.

Report:
I found the highest number of clusters in the cluster model and i explained how i used it to get the value.
Explain the criteria for selecting columns to drop or keep.
Summarize insights gained from EDA.
Take a look at the clusters to determine which song will they recommend to these users.

EDA Highlights:

in my analysis, johnny cash has the highest release date in the song.
No missing values identified.
Diverse data types: float64, int64, and object.
Discovered that "lyrics and "len" have strong correlation on the datasets so i dropped the colum
 
 Model Evaluation Results:
 Silhouette score is 0.20349044046358872
 There are 8 number of cluster in the silhouette score
