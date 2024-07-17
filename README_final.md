# Project Title - Classification of Breast Tumor images using Machine Learning
## Author - Rajesh Kumar Gottimukkala

## Executive summary
This project aims to explore the application of machine learning in the classification of breast tumors as benign or malignant, underscoring its significance in augmenting diagnostic accuracy and patient outcomes. Through the exploratory data analysis(EDA), development and evaluation of various simple machine learning models on breast cancer data, we seek to elucidate the potential of such techniques in addressing this critical healthcare challenge.

## Rationale
Breast cancer stands as one of the most pervasive health concerns globally, with significant implications for public health and individual well-being. As a leading cause of cancer-related mortality among women, it garners considerable attention from healthcare professionals, researchers, and policymakers alike. According to the World Health Organization (WHO), breast cancer accounts for a substantial proportion of new cancer cases diagnosed each year, making it a critical area of focus in the realm of oncology.

Statistics reveal the alarming prevalence of breast cancer, affecting a considerable percentage of the world's population. While estimates may vary across regions and populations, it is estimated that approximately 2.3 million new cases of breast cancer were diagnosed worldwide in 2020 alone, underlining the magnitude of this disease's impact on global health.

The classification of breast tumors into benign and malignant categories plays a pivotal role in clinical practice and treatment decisions. Distinguishing between these two classes is vital as it dictates the subsequent course of action, with malignancies necessitating aggressive treatment modalities such as surgery, chemotherapy, and radiation therapy. Timely and accurate identification of malignancies not only facilitates prompt intervention but also enhances the prospects for successful outcomes and improved patient survival rates.

In this context, machine learning techniques offer promising avenues for enhancing the classification of breast tumors.

## Research Question
Using Machine learning models for Classification of breast tumors into bening and malignant categories to aid in the early detection and management of the breast cancer.

## Data Sources
We will utilize the breast cancer dataset from the UCI Machine Learning Repository, which is publicly accessible at the following link: http://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+%28diagnostic%29 This dataset was curated by Dr. William H. Wolberg, a physician at the University of Wisconsin Hospital in Madison, Wisconsin, USA.Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe
characteristics of the cell nuclei present in the image.

The dataset includes an ID number, diagnosis (malignant or benign), and thirty real-valued features derived from the mean, standard error, and "worst" (mean of the three largest values) measurements of these cell features. For instance, Mean Radius is represented by field 3, Radius SE by field 13, and Worst Radius by field 23. This comprehensive dataset provides valuable information for the classification of breast tumors, contributing to the advancement of diagnostic techniques and treatment strategies.

## Methodology
My main goal is to develop and evaluate various machine learning models, including Logistic Regression, Support Vector Machines, Random Forest Classification, Naive Bayes etc for predicting whether breast cancer is malignant or benign. I will evaluate the performance of each model to determine the best-performing model for our task.The model demonstrating the highest performance will be leveraged to classify breast tumor images.

## Results
I scaled the data using the StandardScaler and built the following classification models : Logistic Regression, Support Vector Machines, Random Forest Classification, Naive Bayes and Decision Trees.
I have generated the confusion matrix for each model to understand the performance better and for better comparisons
I have the accuracy scores generated for each of the classification model : 
Logistic Regression Accuracy is  95.90643274853801 %
SVC Accuracy is  96.49122807017544 %
Naive Bayes Accuracy is  94.15204678362574 %
Decision Tree Regression Accuracy is  90.64327485380117 %
Random Forest Accuracy is : 92.98245614035088 %

Results suggest that all models performed decently well with this dataset and had >90% accuracy scores. SVC turned out be the best Classification algorithm with 96.5% accuracy with Logistic Regression closely at 96%.

## Next steps
Test these models using a larger dataset. 

#### Link to notebook 1 
https://github.com/awsRKG/ML-capstone-project/tree/main/src
## Contact and Further Information

### References: 
https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic
