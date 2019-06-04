---
layout: post
title: "Enhancing Transformation-based Defenses using a Distribution Classifier"
date: 2019-06-01 16:59:17
categories: arXiv_CV
tags: arXiv_CV Adversarial Attention CNN Classification
author: Connie Kou, Hwee Kuan Lee, Teck Khim Ng, Ee-Chien Chang
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial attacks on convolutional neural networks (CNN) have gained significant attention and research efforts have focused on defense methods that make the classifiers more robust. Stochastic input transformation methods have been proposed, where the idea is to randomly transform the input images to try to recover from the adversarial attacks. While these transformation-based methods have shown considerable success at recovering from adversarial images, the performance on clean images deteriorates as the magnitude of the transformation increases. In this paper, we propose a defense mechanism that can be integrated with existing transformation-based defenses and reduce the deterioration of performance on clean images. Exploiting the fact that the transformation methods are stochastic, our method samples a population of transformed images and performs the final classification on distributions of softmax probabilities. We train a separate compact distribution classifier to recognize distinctive features in the distributions of softmax probabilities of transformed clean images. Without retraining the original CNN, our distribution classifier improves the performance of transformation-based defenses on both clean and adversarial images, even though the distribution classifier was never trained on distributions obtained from the adversarial images. Our method is generic and can be integrated with existing transformation-based methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00258](http://arxiv.org/abs/1906.00258)

##### PDF
[http://arxiv.org/pdf/1906.00258](http://arxiv.org/pdf/1906.00258)

