---
layout: post
title: "Speeding up VP9 Intra Encoder with Hierarchical Deep Learning Based Partition Prediction"
date: 2019-06-15 05:50:25
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Deep_Learning Prediction
author: Somdyuti Paul, Andrey Norkin, Alan C. Bovik
mathjax: true
---

* content
{:toc}

##### Abstract
In VP9 video codec, the sizes of blocks are decided during encoding by recursively partitioning 64$\times$64 superblocks using rate-distortion optimization (RDO). This process is computationally intensive because of the combinatorial search space of possible partitions of a superblock. Here, we propose a deep learning based alternative framework to predict the intra-mode superblock partitions in the form of a four-level partition tree, using a hierarchical fully convolutional network (H-FCN). We created a large database of VP9 superblocks and the corresponding partitions to train an H-FCN model, which was subsequently integrated with the VP9 encoder to reduce the intra-mode encoding time. The experimental results establish that our approach speeds up intra-mode encoding by 69.7% on average, at the expense of a 1.71% increase in the Bjontegaard-Delta bitrate (BD-rate). While VP9 provides several built-in speed levels which are designed to provide faster encoding at the expense of decreased rate-distortion performance, we find that our model is able to outperform the fastest recommended speed level of the reference VP9 encoder for the good quality intra encoding configuration, in terms of both speedup and BD-rate.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06476](http://arxiv.org/abs/1906.06476)

##### PDF
[http://arxiv.org/pdf/1906.06476](http://arxiv.org/pdf/1906.06476)

