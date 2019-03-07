---
layout: post
title: "Abnormal Chest X-ray Identification With Generative Adversarial One-Class Classifier"
date: 2019-03-05 20:24:23
categories: arXiv_CV
tags: arXiv_CV Adversarial Quantitative
author: Yuxing Tang, Youbao Tang, Mei Han, Jing Xiao, Ronald M. Summers
mathjax: true
---

* content
{:toc}

##### Abstract
Being one of the most common diagnostic imaging tests, chest radiography requires timely reporting of potential findings in the images. In this paper, we propose an end-to-end architecture for abnormal chest X-ray identification using generative adversarial one-class learning. Unlike previous approaches, our method takes only normal chest X-ray images as input. The architecture is composed of three deep neural networks, each of which learned by competing while collaborating among them to model the underlying content structure of the normal chest X-rays. Given a chest X-ray image in the testing phase, if it is normal, the learned architecture can well model and reconstruct the content; if it is abnormal, since the content is unseen in the training phase, the model would perform poorly in its reconstruction. It thus enables distinguishing abnormal chest X-rays from normal ones. Quantitative and qualitative experiments demonstrate the effectiveness and efficiency of our approach, where an AUC of 0.841 is achieved on the challenging NIH Chest X-ray dataset in a one-class learning setting, with the potential in reducing the workload for radiologists.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.02040](http://arxiv.org/abs/1903.02040)

##### PDF
[http://arxiv.org/pdf/1903.02040](http://arxiv.org/pdf/1903.02040)

