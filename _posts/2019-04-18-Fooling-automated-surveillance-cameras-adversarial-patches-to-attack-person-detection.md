---
layout: post
title: "Fooling automated surveillance cameras: adversarial patches to attack person detection"
date: 2019-04-18 09:46:03
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Knowledge CNN Detection
author: Simen Thys, Wiebe Van Ranst, Toon Goedem&#xe9;
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial attacks on machine learning models have seen increasing interest in the past years. By making only subtle changes to the input of a convolutional neural network, the output of the network can be swayed to output a completely different result. The first attacks did this by changing pixel values of an input image slightly to fool a classifier to output the wrong class. Other approaches have tried to learn "patches" that can be applied to an object to fool detectors and classifiers. Some of these approaches have also shown that these attacks are feasible in the real-world, i.e. by modifying an object and filming it with a video camera. However, all of these approaches target classes that contain almost no intra-class variety (e.g. stop signs). The known structure of the object is then used to generate an adversarial patch on top of it. 
 In this paper, we present an approach to generate adversarial patches to targets with lots of intra-class variety, namely persons. The goal is to generate a patch that is able successfully hide a person from a person detector. An attack that could for instance be used maliciously to circumvent surveillance systems, intruders can sneak around undetected by holding a small cardboard plate in front of their body aimed towards the surveillance camera. 
 From our results we can see that our system is able significantly lower the accuracy of a person detector. Our approach also functions well in real-life scenarios where the patch is filmed by a camera. To the best of our knowledge we are the first to attempt this kind of attack on targets with a high level of intra-class variety like persons.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08653](http://arxiv.org/abs/1904.08653)

##### PDF
[http://arxiv.org/pdf/1904.08653](http://arxiv.org/pdf/1904.08653)

