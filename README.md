# K-NN
**About Algorithm:**<br />
KNN is the simplest machine learning algorithm used for classification and regression.This algorithm makes predictions by calculating similarity between the input sample and each training instance.Training a k-NN model is time taking.It is the most laziest algorithm since it takes every training instance into account.This algorithm does not make strong assumptions about the form of mapping function hence it is Non-parametric.<br />
**Data:**<br />
I have used Amazon data which contains summary of reviews that is featurized using NLP techniques(Bag of words,TfIdf,Average word2vec,TfIdf word2vec) gives higher dimensional.The Amazon data that is been used has already been pre-processed and loaded.<br />
**Summary**:  <br />

|          Model           | Hyper_parameter(K) |   Train f1-score   |   Test f1-score    |
| ------------- | ------------- |------------- | ------------- |
|           BOW            |         11         | 0.9432983198569234 | 0.9433562731604023 | 
|          TF_IDF          |         7          | 0.9470129738238505 | 0.9471684672919388 |
|       Avg Word2Vec       |         13         | 0.9455183640248245 | 0.9461533884690903 | 
| TF_IDF_wieghted_Word2Vec |         17         | 0.9442105797027945 | 0.9458898832454218 | 
