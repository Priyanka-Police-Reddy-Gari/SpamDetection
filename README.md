# SpamDetection
**Loading the dataset**
For this I used usespam dataset from kaggle which can be found from this link. We can download this data and either upload it in google drive or in colab workspace. Load the data in pandas dataframe.

There are only two useful columns. These columns are related to (1) label (ham and spam) and the (2) text of email.
Renamed columns as label and message
Finding the % ham amd spam in the data.

**Classification Pipelines**
As We learned Data processing, Featurization such as CountVectorizer, TFIDFVectorizer, and also Feature Engineering.
I used folllowing methods to create fearures which you can use in your model.

Sparse Embeddings (TF-IDF)
Feature Engineering (see examples below)
Sparse Embeddings (TF-IDF) + Feature Engineering
Approach:

Using a smaller subset of dataset (e.g. 5-10 %) to evaluate the three pipelines . Based on our analysis (e.g. model score, learning curves) , choosing one pipeline from the three. Provided rational for choosing the pipleine. Training only the final pipeline on randomly selected larger subset (e.g. 40%) of the data.

**File1 is analysis with smaller subset and all three pipelines
File 2 is analysis with bigger subset and only final pipeline**
