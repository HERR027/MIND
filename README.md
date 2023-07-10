# MIND
## Recommendation System based on the MIND news dataset. Link to the dataset: https://msnews.github.io/ 
This repository contains a notebook demonstrating how to build a hybrid model on the small 2020 MIND news recommendation dataset, the slides and report on how to implement such a model.   
The notebook is running in the Python 3.8 with Pytorch and Tensorflow installed Azure environment.  
The details for each step is documented on the top of each code.  
Due to limited computational power, the evaluations are done on only the first 100 users on the test set. If trained and tested with the larger dataset, the performance is expected to improve based on results from other available models.  
Experiment the threshold value for better performance. In our case, the threshold is optimized to minimize negatives rather than false positives. This is because false negatives can lead to poor user experience, where the user may miss out on valuable items. On the other hand, false positives are usually less harmful, as the user can simply ignore irrelevant recommendations.  

