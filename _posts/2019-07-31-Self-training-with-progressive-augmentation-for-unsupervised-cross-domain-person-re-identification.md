---
layout: post
title: "Self-training with progressive augmentation for unsupervised cross-domain person re-identification"
date: 2019-07-31 05:51:38
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification Classification Deep_Learning
author: Xinyu Zhang, Jiewei Cao, Chunhua Shen, Mingyu You
mathjax: true
---

* content
{:toc}

##### Abstract
Person re-identification (Re-ID) has achieved great improvement with deep learning and a large amount of labelled training data. However, it remains a challenging task for adapting a model trained in a source domain of labelled data to a target domain of only unlabelled data available. In this work, we develop a self-training method with progressive augmentation framework (PAST) to promote the model performance progressively on the target dataset. Specially, our PAST framework consists of two stages, namely, conservative stage and promoting stage. The conservative stage captures the local structure of target-domain data points with triplet-based loss functions, leading to improved feature representations. The promoting stage continuously optimizes the network by appending a changeable classification layer to the last layer of the model, enabling the use of global information about the data distribution. Importantly, we propose a new self-training strategy that progressively augments the model capability by adopting conservative and promoting stages alternately. Furthermore, to improve the reliability of selected triplet samples, we introduce a ranking-based triplet loss in the conservative stage, which is a label-free objective function basing on the similarities between data pairs. Experiments demonstrate that the proposed method achieves state-of-the-art person Re-ID performance under the unsupervised cross-domain setting. Code is available at: https://tinyurl.com/PASTReID

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.13315](http://arxiv.org/abs/1907.13315)

##### PDF
[http://arxiv.org/pdf/1907.13315](http://arxiv.org/pdf/1907.13315)

