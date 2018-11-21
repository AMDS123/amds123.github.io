---
layout: post
title: "ArcFace: Additive Angular Margin Loss for Deep Face Recognition"
date: 2018-11-20 17:36:29
categories: arXiv_CV
tags: arXiv_CV Face CNN Recognition Face_Recognition
author: Jiankang Deng, Jia Guo, Niannan Xue, Stefanos Zafeiriou
mathjax: true
---

* content
{:toc}

##### Abstract
One of the main challenges in feature learning using Deep Convolutional Neural Networks (DCNNs) for large-scale face recognition is the design of appropriate loss functions that enhance discriminative power. Centre loss penalises the distance between the deep features and their corresponding class centres in the Euclidean space to achieve intra-class compactness. SphereFace assumes that the linear transformation matrix in the last fully connected layer can be used as a representation of the class centres in an angular space and penalises the angles between the deep features and their corresponding weights in a multiplicative way. Recently, a popular line of research is to incorporate margins in well-established loss functions in order to maximise face class separability. In this paper, we propose an Additive Angular Margin Loss (ArcFace) to obtain highly discriminative features for face recognition. The proposed ArcFace has a clear geometric interpretation due to the exact correspondence to the geodesic distance on the hypersphere. We present arguably the most extensive experimental evaluation of all the recent state-of-the-art face recognition methods on over 10 face recognition benchmarks including a new large-scale image database with trillion level of pairs and a large-scale video dataset. We show that ArcFace consistently outperforms the state-of-the-art and can be easily implemented with negligible computational overhead. We release all refined training data, training codes, pre-trained models and training logs, which will help reproduce the results in this paper.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1801.07698](http://arxiv.org/abs/1801.07698)

##### PDF
[http://arxiv.org/pdf/1801.07698](http://arxiv.org/pdf/1801.07698)

