---
layout: post
title: "Boosting the rule-out accuracy of deep disease detection using class weight modifiers"
date: 2019-06-21 23:55:36
categories: arXiv_CV
tags: arXiv_CV Detection
author: Alexandros Karargyris, Ken C. L. Wong, Joy T. Wu, Mehdi Moradi, Tanveer Syeda-Mahmood
mathjax: true
---

* content
{:toc}

##### Abstract
In many screening applications, the primary goal of a radiologist or assisting artificial intelligence is to rule out certain findings. The classifiers built for such applications are often trained on large datasets that derive labels from clinical notes written for patients. While the quality of the positive findings described in these notes is often reliable, lack of the mention of a finding does not always rule out the presence of it. This happens because radiologists comment on the patient in the context of the exam, for example focusing on trauma as opposed to chronic disease at emergency rooms. However, this disease finding ambiguity can affect the performance of algorithms. Hence it is critical to model the ambiguity during training. We propose a scheme to apply reasonable class weight modifiers to our loss function for the no mention cases during training. We experiment with two different deep neural network architectures and show that the proposed method results in a large improvement in the performance of the classifiers, specially on negated findings. The baseline performance of a custom-made dilated block network proposed in this paper shows an improvement in comparison with baseline DenseNet-201, while both architectures benefit from the new proposed loss function weighting scheme. Over 200,000 chest X-ray images and three highly common diseases, along with their negated counterparts, are included in this study.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09354](http://arxiv.org/abs/1906.09354)

##### PDF
[http://arxiv.org/pdf/1906.09354](http://arxiv.org/pdf/1906.09354)

