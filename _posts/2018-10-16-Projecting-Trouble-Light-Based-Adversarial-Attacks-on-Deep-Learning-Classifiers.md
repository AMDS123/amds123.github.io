---
layout: post
title: "Projecting Trouble: Light Based Adversarial Attacks on Deep Learning Classifiers"
date: 2018-10-16 17:47:07
categories: arXiv_CV
tags: arXiv_CV Adversarial Image_Classification Classification Deep_Learning
author: Nicole Nichols, Robert Jasper
mathjax: true
---

* content
{:toc}

##### Abstract
This work demonstrates a physical attack on a deep learning image classification system using projected light onto a physical scene. Prior work is dominated by techniques for creating adversarial examples which directly manipulate the digital input of the classifier. Such an attack is limited to scenarios where the adversary can directly update the inputs to the classifier. This could happen by intercepting and modifying the inputs to an online API such as Clarifai or Cloud Vision. Such limitations have led to a vein of research around physical attacks where objects are constructed to be inherently adversarial or adversarial modifications are added to cause misclassification. Our work differs from other physical attacks in that we can cause misclassification dynamically without altering physical objects in a permanent way. 
 We construct an experimental setup which includes a light projection source, an object for classification, and a camera to capture the scene. Experiments are conducted against 2D and 3D objects from CIFAR-10. Initial tests show projected light patterns selected via differential evolution could degrade classification from 98% to 22% and 89% to 43% probability for 2D and 3D targets respectively. Subsequent experiments explore sensitivity to physical setup and compare two additional baseline conditions for all 10 CIFAR classes. Some physical targets are more susceptible to perturbation. Simple attacks show near equivalent success, and 6 of the 10 classes were disrupted by light.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.10337](http://arxiv.org/abs/1810.10337)

##### PDF
[http://arxiv.org/pdf/1810.10337](http://arxiv.org/pdf/1810.10337)

