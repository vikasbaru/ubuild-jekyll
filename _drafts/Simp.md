---
title: Simp
layout: default
date: 2018-09-20 07:05:17 -0700

---
# The Simpsons Character Classifier

This dataset consists of a relatively small amount of labeled screenshots of different characters from The Simpsons.

## Dataset

* The labeled dataset is available on [Kaggle](https://www.kaggle.com/alexattia/the-simpsons-characters-dataset).           

* Most images/screenshots appear to contain only one character; however there is a small number of images containing multiple characters (e.g. in the background), with the labeled character taking up the majority of the image space.     
*  There are 47 labeled characters. However, not all contain very many images (and some actually have **no** images). Most of the previous analyses have focused on 20 or so main characters
*  SoTA: The author of the Simpsons dataset (i.e. the user who hand-labeled the images) used Keras/Tensorflow and a 6-layer CNN to achieve 96% accuracy for the Top 20 characters. Blog post [here](https://medium.com/alex-attia-blog/the-simpsons-character-recognition-using-keras-d8e1796eae36), code on [github](https://github.com/alexattia/SimpsonRecognition/blob/master/Data%20Processing%20and%20Learning.ipynb).

## Relevant blog posts or fastai references/code

*  The use of [AdamW with fastai](http://www.fast.ai/2018/07/02/adam-weight-decay/)
* The [1 cycle policy](https://sgugger.github.io/the-1cycle-policy.html)
* A general [overview of gradient descent optimizers](http://ruder.io/optimizing-gradient-descent/)
*  [Leslie Smith's approach to \[batch norm, learning rates, momentum, and weight decay](https://arxiv.org/pdf/1803.09820.pdf)