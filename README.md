# Anti-Reproductive-Rights-Crimes
Project On Anti-Reproductive Rights Crimes
Francis Kwame Segbe

# Desired Outcome (Framing)
The assignment's goal is to group Anti-reproductive rights crimes into smaller chunks. Anti-reproductive rights crimes are defined as crimes committed partly or wholly because the victim is a reproductive health services patient, provider, or assistant, or a crime that is partly or wholly intended to intimidate the victim, any other person or entity, or any class of persons or entities from becoming or remaining a reproductive health services patient, provider, or assistant.

 For us to be able to do this, we will categorize the offenses into various categories like geographic location, victim race, victim gender, charge type, etc. 
 In essence, what we are looking at accomplishing is identifying crime patterns based on the features provided to us from the dataset.
 
# Hypothesis
We expect that the offenses related to anti-reproductive crimes will show clustering characteristics instead of being randomly distributed. This is likely to show in the geographic location, temporal trends such as the period in our specific case we are looking at year and month, and the nature of the offense (BSC). We could also see clustering based on demographics such as gender, victim type, offense code etc.
# Methodology
Throughout this project, the methodologies we are likely to employ would be clustering algorithms for grouping and identifying underlying patterns in our dataset.
In using clustering algorithms, we will employ algorithms such as K-means, and K-mode to find patterns in crimes based on features, such as demographics, and characteristics of the crime.
For us to evaluate similarity and group offenses, we made of used the k-mode clustering technique because it is much more suitable for categorical data. This choice was determined after examining our dataset and found that the nature of the dataset primarily consists of non-numeric, categorical variables. We, however, also cluster based on k-means. To work with K-means, we had to feature encode categorical variables. This was done to check if we could identify any significant patterns in comparison to k-modes. The models seem to have produced similar results with only small variations in the number of clusters and cluster categories.

# Data Preprocessing:  
During the preprocessing stage we focused mainly on missing variables, taking out redundant features or features with more than 25% missing variables. Through further analysis, we checked cleaned inconsistent data types in features such as suspect gender and suspect race among others. The dataset was prepared by focusing on relevant categorical features and data was formatted to ensure compatibility with the k-means algorithm.  We also handled NaN values while working through our data since k-means and k-modes could not work properly with NaN in our dataset.
We also looked at the features with a lot of categorical values and tried mapping those values into fewer more broadly representative values.

# Optimal Number of Clusters: 
We used various methods, such as the Elbow Method adapted for k-modes and k-means were considered to estimate the right number of clusters. This step is crucial for balancing the granularity of the clustering against the group coherence formed. Clustering 

# Implementation: 
The k-mode clustering was applied iteratively, exploring different numbers of clusters to observe how the offenses grouped together. Each iteration aimed to learn patterns within the clusters formed.
