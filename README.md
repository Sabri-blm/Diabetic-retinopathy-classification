<h2 align="center">Diabetic-retinopathy-classification</h3>
<h4 align="center">A classification problem on the Messidor dataset for diabetic retinopathy</h4>


## Table of Contents
- [Project Overview](#project_overview)
- [Project Details](#details)

### 1.Project Overview <a name="project_overview"></a>

This GitHub repository aims to address the problem of classifying diabetic retinopathy using machine learning techniques. Diabetic retinopathy is a common complication of diabetes and is a leading cause of blindness. The repository provides a comprehensive pipeline for data preprocessing, model creation from scratch, model training, evaluation, and visualization.

The dataset that we will be wrangling (and analyzing and visualizing) is the [Diabetic Retinopathy Debrecen Data Set Data Set](https://archive.ics.uci.edu/ml/datasets/Diabetic+Retinopathy+Debrecen+Data+Set), also known as the Messidor dataset.
This dataset contains features extracted from the Messidor image set to predict whether an image contains signs of diabetic retinopathy or not. All features represent either a detected lesion, a descriptive feature of a anatomical part or an image-level descriptor.

### 3.Project Details <a name="details"></a>

The tasks in this project are as follows:
<ul>
    <li>Data Preprocessing:</li>
  <ul>
        <li>Gathering data :</li> collecting the data from the UCI website
        <li>Assessing data :</li> applying an exploratory data analysis to understand the data, from the correlation of different features, outliers, studying features distribution... ect.
        <li>Cleaning data :</li> removing missing values, unwanted features, correcting labels\features names.
        <li>Feature Engineering :</li> grouping multiple features into one, added polynomial features.
        <li>Data normalization :</li> used StandardScaler for the normalization.
        <li>Creation of different dataset :</li> we used different features engineering techniques to each of the 4 created dataset to test which one gives the best results.
        <li>Features selection :</li> we created 3 different pipeline using the different models (RandomForestClassifier, SVC, KNneighborsClassifier) to train and test the created datasets, we selected the best one and used these pipelines to apply features selection.
  </ul>
    <li>Creating Logistic regression model from scratch :</li> we created a logistic regression model from scratch, where we define each function used in the model (loss function, min-max function, training function, logistic function, log_gradient, gradient_descent... ect).
    <li>Training phase</li>
    <li>visualizations of the results</li>
</ul>
