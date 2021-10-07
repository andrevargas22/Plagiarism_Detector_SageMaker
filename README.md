# SageMaker Plagiarism Detector Project

This is the second project of the Machine Learning Engineer Nanodegree by Udacity. The majority of the code was provided by Udacity, with a few sections completed by me as part of the exercise.

The Plagiarism Detector examines a text file and performs binary classification, labeling that file as either *plagiarized* or *not*, depending on how similar that text file is to a provided source text. 

This project is broken down into two main notebooks:

**Notebook 2: Feature Engineering**

* Clean and pre-processing of the text data.
* Definition of features for comparing the similarity of an answer text and a source text, and extract similarity features.
* Selection of "good" features by analyzing the correlations between different features.
* Creation train/test `.csv` files that hold the relevant features and class labels for train/test data points.

**Notebook 3: Train and Deploy Your Model in SageMaker**

* Upload the train/test feature data to S3 bucked in AWS SageMaker.
* Definition of a binary classification model and a training script.
* Training the model and deploy it using SageMaker.
* Evaluate the deployed classifier.

Please see the [README](https://github.com/udacity/sagemaker-deployment/tree/master/README.md) in the root directory for instructions on setting up a SageMaker notebook and downloading the project files.
