# California Housing Clustering Analysis
This folder contains a series of clustering analyses performed on the modified California Housing dataset originally sourced from Kaggle, focusing on understanding housing patterns through different clustering techniques. The analysis explores hierarchical clustering with multiple linkage methods and k-means clustering, applied to both raw and standardized data.

## Dataset Overview
**Dataset Title**: california_housing

**Number of Instances**: 300

**Number of Features**: 7

**Features**: Housing Median Age, Total Rooms, Total Bedrooms, Population ,Households, Median Income, Median House Value

All features are numerical and there are no null values.

## Clustering Tasks
### Hierarchical Clustering
**Affinity Measure**: Euclidean distance

**Linkage Methods**: Single linkage, Complete linkage, Average linkage, Ward’s linkage, Centroid linkage

**Outputs**: Dendrograms for each linkage method.

**Standardization**: Analysis repeated on standardized data to observe the effect of scaling.

### K-means Clustering
**Initial Analysis**: Applied on the original data with k values ranging from 2 to 10. Analysis includes within cluster sum of squared errors (SSE / inertia), cluster sizes, centroids for each feature, and number of iterations for convergence.

**Extended Analysis**:

Number of Clusters: 2, 3, 4

Distribution of observations within each cluster.

Examination of feature values for each cluster.

Variable differences across clusters visualized using box plots.

ANOVA analysis to find statistically significant differences.

Elbow plot, silhouette score, Davies-Bouldin index, and Calinski-Harabasz index for evaluating clustering performance.

**Standardization**: Analysis repeated on standardized data to observe the effect of scaling.

## Tools and Technologies
**Python**: Main programming language.

**Scikit-learn**: For implementing clustering algorithms.

**SciPy**: For generating dendrograms and conducting ANOVA.

**Matplotlib and Seaborn**: For creating visualizations including dendrograms and box plots.
