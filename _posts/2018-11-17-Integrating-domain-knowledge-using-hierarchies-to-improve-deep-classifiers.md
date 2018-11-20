---
layout: post
title: "Integrating domain knowledge: using hierarchies to improve deep classifiers"
date: 2018-11-17 08:23:32
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Classification Deep_Learning Recognition
author: Clemens-Alexander Brust, Joachim Denzler
mathjax: true
---

* content
{:toc}

##### Abstract
One of the most prominent problems in machine learning in the age of deep learning is the availability of sufficiently large annotated datasets. While for standard problem domains (ImageNet classification), appropriate datasets exist, for specific domains, \eg classification of animal species, a long-tail distribution means that some classes are observed and annotated insufficiently. Challenges like iNaturalist show that there is a strong interest in species recognition. Acquiring additional labels can be prohibitively expensive. First, since domain experts need to be involved, and second, because acquisition of new data might be costly. Although there exist methods for data augmentation, which not always lead to better performance of the classifier, there is more additional information available that is to the best of our knowledge not exploited accordingly. 
 In this paper, we propose to make use of existing class hierarchies like WordNet to integrate additional domain knowledge into classification. We encode the properties of such a class hierarchy into a probabilistic model. From there, we derive a special label encoding together with a corresponding loss function. Using a convolutional neural network, on the ImageNet and NABirds datasets our method offers a relative improvement of 10.4% and 9.6% in accuracy over the baseline respectively. After less than a third of training time, it is already able to match the baseline's fine-grained recognition performance. Both results show that our suggested method is efficient and effective.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07125](http://arxiv.org/abs/1811.07125)

##### PDF
[http://arxiv.org/pdf/1811.07125](http://arxiv.org/pdf/1811.07125)

