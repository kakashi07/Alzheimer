# Alzheimer Severity Classification

## Research Problem:
A computer vision healthcare project that takes MRI images of clinical patients and classifies patients based on Extreme to Low Severity.

## Data Pipeline
![img5](/images/pipeline.png)


## Solution Approach
In this project, the MRI dataset of clinical patients for the hippocampus region is used as the primary input. Based on this input feature, relevant features are extracted. Given the high dimensionality of the input, we apply PCA to get the top 10 features that explain 90% variance in the data.

Finally, we experimented with different ML algorithms to find the best algorithm. In our case, SVM turned out to be the superior algorithm with **97% test accuracy.**

## Figure 1: Top 10 PCA Features
![img4](/images/img1.png)

## Figure 2: Pairplot to understand relative feature relationships
![img2](/images/img4.png)


## Figure 3: Cross Validation Accuracies for SVM
![img3](/images/img3.png)

## Figure 4: Confusion Matrix
![img4](/images/img2.png)


