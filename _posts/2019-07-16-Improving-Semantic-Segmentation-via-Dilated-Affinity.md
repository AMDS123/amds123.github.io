---
layout: post
title: "Improving Semantic Segmentation via Dilated Affinity"
date: 2019-07-16 13:59:22
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation CNN Semantic_Segmentation Prediction Relation
author: Boxi Wu, Shuai Zhao, Wenqing Chu, Zheng Yang, Deng Cai
mathjax: true
---

* content
{:toc}

##### Abstract
Introducing explicit constraints on the structural predictions has been an effective way to improve the performance of semantic segmentation models. Existing methods are mainly based on insufficient hand-crafted rules that only partially capture the image structure, and some methods can also suffer from the efficiency issue. As a result, most of the state-of-the-art fully convolutional networks did not adopt these techniques. In this work, we propose a simple, fast yet effective method that exploits structural information through direct supervision with minor additional expense. To be specific, our method explicitly requires the network to predict semantic segmentation as well as dilated affinity, which is a sparse version of pair-wise pixel affinity. The capability of telling the relationships between pixels are directly built into the model and enhance the quality of segmentation in two stages. 1) Joint training with dilated affinity can provide robust feature representations and thus lead to finer segmentation results. 2) The extra output of affinity information can be further utilized to refine the original segmentation with a fast propagation process. Consistent improvements are observed on various benchmark datasets when applying our framework to the existing state-of-the-art model. Codes will be released soon.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.07011](http://arxiv.org/abs/1907.07011)

##### PDF
[http://arxiv.org/pdf/1907.07011](http://arxiv.org/pdf/1907.07011)

