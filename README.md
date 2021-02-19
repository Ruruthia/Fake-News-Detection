# Fake-News-Detection

This is a final, group project for Machine Learning course. 
We used KNN, boosted ensembles and SVMs to classify articles based on their estimated truthfullness.
Data was collected by ourselves from numerous websites.

Classifers were also run on dataset from Kaggle (https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset). 

This is a prime example of "garbage in, garbage out" rule - almost all of the true articles from this dataset are from Reuters and include word "Reuters".
It was funny to see that the results on Kaggle achieved by people using state-of-the-art neural networks can be bested using simple if checking whether the word "Reuters" appears in the article!

Full report can be found in "Project_summary" file.
