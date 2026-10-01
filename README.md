Data set Link:https://www.kaggle.com/api/v1/datasets/download/unitednations/un-general-debatesLinks to an external site.
The goal of Part I of the task is to use raw textual data in language models for recommendation-based application.
The goal of Part II of task is to implement comprehensive preprocessing steps for a given dataset, enhancing the quality and relevance of the textual information. The preprocessed text is then transformed into a feature-rich representation using a chosen vectorization method for further use in the application to perform similarity analysis.

Part I
Sentence completion using N-gram: 
Recommend the top 3 words to complete the given sentence using N-gram language model. The goal is to demonstrate the relevance of recommended words based on the occurrence of Bigram within the corpus. Use all the instances in the dataset as a training corpus.
Test Sentence: it is a pleasure ________________________.

Part II
Perform the below sequential tasks on the given dataset.
 * i)  Text Preprocessing: 
Tokenization
Lowercasing
Stop Words Removal
Stemming
Lemmatization
 * ii)  Feature Extraction: 
Use the pre-processed data from previous step and implement the below vectorization methods to extract features.
Word Embedding using Skip Gram
Similarity Analysis: 
Use the vectorized representation from previous step and implement a method to identify and print the names of top two similar documents that exhibit significant similarity. Justify your choice of similarity metric and feature design. Visualize a subset of vector embedding in 2D semantic space suitable for this use case.
HINT: (Use PCA for Dimensionality reduction)
