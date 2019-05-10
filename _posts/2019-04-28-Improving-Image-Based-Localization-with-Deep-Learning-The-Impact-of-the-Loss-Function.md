---
layout: post
title: "Improving Image-Based Localization with Deep Learning: The Impact of the Loss Function"
date: 2019-04-28 05:47:37
categories: arXiv_AI
tags: arXiv_AI Deep_Learning
author: Isaac Ronald Ward, M. A. Asim K. Jalwana, Mohammed Bennamoun
mathjax: true
---

* content
{:toc}

##### Abstract
This work formulates a novel loss term which can be appended to an RGB only image localization network's loss function to improve its performance. A common technique used when regressing a camera's pose from an image is to formulate the loss as a linear combination of positional and rotational error (using tuned hyperparameters as coefficients). In this work we observe that changes to rotation and position mutually affect the captured image, and in order to improve performance, a network's loss function should include a term which combines error in both position and rotation. To that end we design a geometric loss term which considers the similarity between the predicted and ground truth poses using both position and rotation, and use it to augment the existing image localization network PoseNet. The loss term is simply appended to the loss function of the already existing image localization network. We achieve improvements in the localization accuracy of the network for indoor scenes: with decreases of up to 9.64% and 2.99% in the median positional and rotational error when compared to similar pipelines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.03692](http://arxiv.org/abs/1905.03692)

##### PDF
[http://arxiv.org/pdf/1905.03692](http://arxiv.org/pdf/1905.03692)

