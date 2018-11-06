---
layout: post
title: "FUNN: Flexible Unsupervised Neural Network"
date: 2018-11-05 14:42:02
categories: arXiv_CV
tags: arXiv_CV Adversarial Image_Classification Classification
author: David Vigouroux, Sylvain Picard
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have demonstrated high accuracy in image classification tasks. However, they were shown to be weak against adversarial examples: a small perturbation in the image which changes the classification output dramatically. In recent years, several defenses have been proposed to solve this issue in supervised classification tasks. We propose a method to obtain robust features in unsupervised learning tasks against adversarial attacks. Our method differs from existing solutions by directly learning the robust features without the need to project the adversarial examples in the original examples distribution space. A first auto-encoder A1 is in charge of perturbing the input image to fool another auto-encoder A2 which is in charge of regenerating the original image. A1 tries to find the less perturbed image under the constraint that the error in the output of A2 should be at least equal to a threshold. Thanks to this training, the encoder of A2 will be robust against adversarial attacks and could be used in different tasks like classification. Using state-of-art network architectures, we demonstrate the robustness of the features obtained thanks to this method in classification tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.01749](http://arxiv.org/abs/1811.01749)

##### PDF
[http://arxiv.org/pdf/1811.01749](http://arxiv.org/pdf/1811.01749)

