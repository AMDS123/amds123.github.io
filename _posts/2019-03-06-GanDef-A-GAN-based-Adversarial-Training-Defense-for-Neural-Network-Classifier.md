---
layout: post
title: "GanDef: A GAN based Adversarial Training Defense for Neural Network Classifier"
date: 2019-03-06 19:09:47
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Guanxiong Liu, Issa Khalil, Abdallah Khreishah
mathjax: true
---

* content
{:toc}

##### Abstract
Machine learning models, especially neural network (NN) classifiers, are widely used in many applications including natural language processing, computer vision and cybersecurity. They provide high accuracy under the assumption of attack-free scenarios. However, this assumption has been defied by the introduction of adversarial examples -- carefully perturbed samples of input that are usually misclassified. Many researchers have tried to develop a defense against adversarial examples; however, we are still far from achieving that goal. In this paper, we design a Generative Adversarial Net (GAN) based adversarial training defense, dubbed GanDef, which utilizes a competition game to regulate the feature selection during the training. We analytically show that GanDef can train a classifier so it can defend against adversarial examples. Through extensive evaluation on different white-box adversarial examples, the classifier trained by GanDef shows the same level of test accuracy as those trained by state-of-the-art adversarial training defenses. More importantly, GanDef-Comb, a variant of GanDef, could utilize the discriminator to achieve a dynamic trade-off between correctly classifying original and adversarial examples. As a result, it achieves the highest overall test accuracy when the ratio of adversarial examples exceeds 41.7%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.02585](http://arxiv.org/abs/1903.02585)

##### PDF
[http://arxiv.org/pdf/1903.02585](http://arxiv.org/pdf/1903.02585)

