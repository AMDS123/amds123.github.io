---
layout: post
title: "Simultaneous Feature Learning and Hash Coding with Deep Neural Networks"
date: 2015-04-14 03:14:24
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval
author: Hanjiang Lai, Yan Pan, Ye Liu, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Similarity-preserving hashing is a widely-used method for nearest neighbour search in large-scale image retrieval tasks. For most existing hashing methods, an image is first encoded as a vector of hand-engineering visual features, followed by another separate projection or quantization step that generates binary codes. However, such visual feature vectors may not be optimally compatible with the coding process, thus producing sub-optimal hashing codes. In this paper, we propose a deep architecture for supervised hashing, in which images are mapped into binary codes via carefully designed deep neural networks. The pipeline of the proposed deep architecture consists of three building blocks: 1) a sub-network with a stack of convolution layers to produce the effective intermediate image features; 2) a divide-and-encode module to divide the intermediate image features into multiple branches, each encoded into one hash bit; and 3) a triplet ranking loss designed to characterize that one image is more similar to the second image than to the third one. Extensive evaluations on several benchmark image datasets show that the proposed simultaneous feature learning and hash coding pipeline brings substantial improvements over other state-of-the-art supervised or unsupervised hashing methods.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1504.03410](https://arxiv.org/abs/1504.03410)

##### PDF
[https://arxiv.org/pdf/1504.03410](https://arxiv.org/pdf/1504.03410)

