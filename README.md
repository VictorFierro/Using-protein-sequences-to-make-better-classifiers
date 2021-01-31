# Using-protein-sequences-to-make-better-classifiers
Using protein sequences to make better classifiers 

This investigation represents a summary of the research conducted by Stephan Heijl


Transfer learning is widely used in image classification and natural language processing. Image classifiers are often fine-tuned models, initially trained on large datasets with millions of pictures like ImageNet. Language models will be pre-trained on large corpuses of text with billions of words. This leads to more efficient training and less overfitting on smaller, targeted datasets. 

Here, it is proposed a set of recurrent neural networks trained on generic protein prediction tasks, like secondary structure prediction, contact map prediction and transmembrane prediction. The intermediate representations of those pre-trained networks can be used to annotate your dataset and enhance your predictor’s performance.
