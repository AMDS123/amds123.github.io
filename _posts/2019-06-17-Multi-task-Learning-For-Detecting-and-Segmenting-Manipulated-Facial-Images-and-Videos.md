---
layout: post
title: "Multi-task Learning For Detecting and Segmenting Manipulated Facial Images and Videos"
date: 2019-06-17 07:27:54
categories: arXiv_CV
tags: arXiv_CV Segmentation Face CNN Classification Detection
author: Huy H. Nguyen, Fuming Fang, Junichi Yamagishi, Isao Echizen
mathjax: true
---

* content
{:toc}

##### Abstract
Detecting manipulated images and videos is an important topic in digital media forensics. Most detection methods use binary classification to determine the probability of a query being manipulated. Another important topic is locating manipulated regions (i.e., performing segmentation), which are mostly created by three commonly used attacks: removal, copy-move, and splicing. We have designed a convolutional neural network that uses the multi-task learning approach to simultaneously detect manipulated images and videos and locate the manipulated regions for each query. Information gained by performing one task is shared with the other task and thereby enhance the performance of both tasks. A semi-supervised learning approach is used to improve the network's generability. The network includes an encoder and a Y-shaped decoder. Activation of the encoded features is used for the binary classification. The output of one branch of the decoder is used for segmenting the manipulated regions while that of the other branch is used for reconstructing the input, which helps improve overall performance. Experiments using the FaceForensics and FaceForensics++ databases demonstrated the network's effectiveness against facial reenactment attacks and face swapping attacks as well as its ability to deal with the mismatch condition for previously seen attacks. Moreover, fine-tuning using just a small amount of data enables the network to deal with unseen attacks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06876](http://arxiv.org/abs/1906.06876)

##### PDF
[http://arxiv.org/pdf/1906.06876](http://arxiv.org/pdf/1906.06876)

