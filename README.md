# NTUA-Neural-Networks

## Programming Exercises for the 2021-2022 NTUA class Neural-Networks

> Projects

🔴 <b>1st Project: The aim of the work is the study and optimization of classifiers in datasets. Every team
of the lab will study two datasets, one from the UCI repository and one from the platform
Kaggle and conclude some very important results.</b>

🔴 <b>2nd Project: The aim of the work is to create a  movie recommendation system based on
content.![image](https://user-images.githubusercontent.com/94322040/181795540-4ec52077-8a5a-4e50-bc01-816c010c96ee.png)
Firstly TfidfVectorizer will be used for this purpose and later in the notebook Word2Vec will be deployed. Lastly this two techniques are being compared.

🔴 <b>3rd Project: The subject of the 3rd paper of the course is Deep Learning. We will study a problem that combines Computer Vision and Natural Language Processing. Specifically, we will build a neural network for producing verbal descriptions from images (Image Captioning). 

A starting point will be the official TensorFlow tutorial "Image captioning with visual attention". We will however work on another dataset and try to improve the tutorial in various places.

We will use "flickr30k-images-ecemod", a variant of flick30k for our tutorial.

The tutorial model follows the usual Encoder - Decoder Deep Learning architecture.

![image](https://user-images.githubusercontent.com/94322040/181798137-030d5afb-ef85-4cf3-bc37-691d16eea8e3.png)

Encoder corresponds to steps 1 and 2 and Decoder corresponds to steps 3-5.

The tutorial does not include any reference to the quality of the generated captioning. If we consider that each image has some real captions (references) and the neuron produces its own caption (hypothesis) we will use the BLEU (Bilingual Evaluation Understudy) score, between hypothesis and references. Briefly, BLEU is a weighted average of the number of shared unigrams, bigrams, trigrams, and fourgrams between hypothesis and references. The worst captioning gets 0 and the best 1.

</b>
