---
layout: post
title: "Incremental Learning in Deep Convolutional Neural Networks Using Partial Network Sharing"
date: 2019-05-02 06:20:19
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Transfer_Learning Classification Recognition
author: Syed Shakib Sarwar, Aayush Ankit, Kaushik Roy
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural network (DCNN) based supervised learning is a widely practiced approach for large-scale image classification. However, retraining these large networks to accommodate new, previously unseen data demands high computational time and energy requirements. Also, previously seen training samples may not be available at the time of retraining. We propose an efficient training methodology and incrementally growing DCNN to learn new tasks while sharing part of the base network. Our proposed methodology is inspired by transfer learning techniques, although it does not forget previously learned tasks. An updated network for learning new set of classes is formed using previously learned convolutional layers (shared from initial part of base network) with addition of few newly added convolutional kernels included in the later layers of the network. We employed a `clone-and-branch' technique which allows the network to learn new tasks one after another without any performance loss in old tasks. We evaluated the proposed scheme on several recognition applications. The classification accuracy achieved by our approach is comparable to the regular incremental learning approach (where networks are updated with new training samples only, without any network sharing), while achieving energy efficiency, reduction in storage requirements, memory access and training time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1712.02719](http://arxiv.org/abs/1712.02719)

##### PDF
[http://arxiv.org/pdf/1712.02719](http://arxiv.org/pdf/1712.02719)

