---
layout: post
title: "Localisation via Deep Imagination: learn the features not the map"
date: 2018-11-19 09:52:34
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Jaime Spencer, Oscar Mendez, Richard Bowden, Simon Hadfield
mathjax: true
---

* content
{:toc}

##### Abstract
How many times does a human have to drive through the same area to become familiar with it? To begin with, we might first build a mental model of our surroundings. Upon revisiting this area, we can use this model to extrapolate to new unseen locations and imagine their appearance. Based on this, we propose an approach where an agent is capable of modelling new environments after a single visitation. To this end, we introduce "Deep Imagination", a combination of classical Visual-based Monte Carlo Localisation and deep learning. By making use of a feature embedded 3D map, the system can "imagine" the view from any novel location. These "imagined" views are contrasted with the current observation in order to estimate the agent's current location. In order to build the embedded map, we train a deep Siamese Fully Convolutional U-Net to perform dense feature extraction. By training these features to be generic, no additional training or fine tuning is required to adapt to new environments. Our results demonstrate the generality and transfer capability of our learnt dense features by training and evaluating on multiple datasets. Additionally, we include several visualizations of the feature representations and resulting 3D maps, as well as their application to localisation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07583](http://arxiv.org/abs/1811.07583)

##### PDF
[http://arxiv.org/pdf/1811.07583](http://arxiv.org/pdf/1811.07583)

