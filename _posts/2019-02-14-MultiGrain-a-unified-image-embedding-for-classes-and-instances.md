---
layout: post
title: "MultiGrain: a unified image embedding for classes and instances"
date: 2019-02-14 17:32:21
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Embedding Image_Classification Classification
author: Maxim Berman, Herv&#xe9; J&#xe9;gou, Andrea Vedaldi, Iasonas Kokkinos, Matthijs Douze
mathjax: true
---

* content
{:toc}

##### Abstract
MultiGrain is a network architecture producing compact vector representations that are suited both for image classification and particular object retrieval. It builds on a standard classification trunk. The top of the network produces an embedding containing coarse and fine-grained information, so that images can be recognized based on the object class, particular object, or if they are distorted copies. Our joint training is simple: we minimize a cross-entropy loss for classification and a ranking loss that determines if two images are identical up to data augmentation, with no need for additional labels. A key component of MultiGrain is a pooling layer that allow us to take advantage of high-resolution images with a network trained at a lower resolution. 
 When fed to a linear classifier, the learned embeddings provide state-of-the-art classification accuracy. For instance, we obtain 79.3% top-1 accuracy with a ResNet-50 learned on Imagenet, which is a +1.7% absolute improvement over the AutoAugment method. When compared with the cosine similarity, the same embeddings perform on par with the state-of-the-art for image retrieval at moderate resolutions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.05509](http://arxiv.org/abs/1902.05509)

##### PDF
[http://arxiv.org/pdf/1902.05509](http://arxiv.org/pdf/1902.05509)

