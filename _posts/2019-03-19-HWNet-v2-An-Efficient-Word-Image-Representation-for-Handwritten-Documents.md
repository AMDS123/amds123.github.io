---
layout: post
title: "HWNet v2: An Efficient Word Image Representation for Handwritten Documents"
date: 2019-03-19 09:07:02
categories: arXiv_CV
tags: arXiv_CV Image_Caption CNN Transfer_Learning Classification
author: Praveen Krishnan, C.V. Jawahar
mathjax: true
---

* content
{:toc}

##### Abstract
We present a framework for learning an efficient holistic representation for handwritten word images. The proposed method uses a deep convolutional neural network with traditional classification loss. The major strengths of our work lie in: (i) the efficient usage of synthetic data to pre-train a deep network, (ii) an adapted version of the ResNet-34 architecture with the region of interest pooling (referred to as HWNet v2) which learns discriminative features for variable sized word images, and (iii) a realistic augmentation of training data with multiple scales and distortions which mimics the natural process of handwriting. We further investigate the process of transfer learning to reduce the domain gap between synthetic and real domain, and also analyze the invariances learned at different layers of the network using visualization techniques proposed in the literature. 
 Our representation leads to a state-of-the-art word spotting performance on standard handwritten datasets and historical manuscripts in different languages with minimal representation size. On the challenging IAM dataset, our method is first to report an mAP of around 0.90 for word spotting with a representation size of just 32 dimensions. Furthermore, we also present results on printed document datasets in English and Indic scripts which validates the generic nature of the proposed framework for learning word image representation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1802.06194](http://arxiv.org/abs/1802.06194)

##### PDF
[http://arxiv.org/pdf/1802.06194](http://arxiv.org/pdf/1802.06194)

