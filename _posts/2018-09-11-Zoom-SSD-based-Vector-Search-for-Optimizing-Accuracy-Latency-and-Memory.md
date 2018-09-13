---
layout: post
title: "Zoom: SSD-based Vector Search for Optimizing Accuracy, Latency and Memory"
date: 2018-09-11 23:46:33
categories: arXiv_CV
tags: arXiv_CV Review Deep_Learning
author: Minjia Zhang, Yuxiong He
mathjax: true
---

* content
{:toc}

##### Abstract
With the advancement of machine learning and deep learning, vector search becomes instrumental to many information retrieval systems, to search and find best matches to user queries based on their semantic similarities.These online services require the search architecture to be both effective with high accuracy and efficient with low latency and memory footprint, which existing work fails to offer. We develop, Zoom, a new vector search solution that collaboratively optimizes accuracy, latency and memory based on a multiview approach. (1) A "preview" step generates a small set of good candidates, leveraging compressed vectors in memory for reduced footprint and fast lookup. (2) A "fullview" step on SSDs reranks those candidates with their full-length vector, striking high accuracy. Our evaluation shows that, Zoom achieves an order of magnitude improvements on efficiency while attaining equal or higher accuracy, comparing with the state-of-the-art.

##### Abstract (translated by Google)
随着机器学习和深度学习的进步，矢量搜索成为许多信息检索系统的基础，可以根据用户查询的语义相似性搜索和找到最佳匹配。这些在线服务要求搜索体系结构既有效又高精度。高效，低延迟和内存占用，现有工作无法提供。我们开发了Zoom，这是一种新的矢量搜索解决方案，可以基于多视图方法协同优化准确性，延迟和内存。 （1）“预览”步骤生成一小组好的候选者，利用内存中的压缩矢量来减少占用空间和快速查找。 （2）SSD上的“全视图”步骤使用全长矢量重新排列那些候选者，具有高精度。我们的评估表明，与现有技术相比，Zoom在效率方面实现了一个数量级的改进，同时获得了相同或更高的精度。

##### URL
[http://arxiv.org/abs/1809.04067](http://arxiv.org/abs/1809.04067)

##### PDF
[http://arxiv.org/pdf/1809.04067](http://arxiv.org/pdf/1809.04067)

