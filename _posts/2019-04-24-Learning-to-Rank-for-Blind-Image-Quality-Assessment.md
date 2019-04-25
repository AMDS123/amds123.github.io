---
layout: post
title: "Learning to Rank for Blind Image Quality Assessment"
date: 2019-04-24 00:26:17
categories: arXiv_CV
tags: arXiv_CV QA Classification
author: Fei Gao, Dacheng Tao, Xinbo Gao, Xuelong Li
mathjax: true
---

* content
{:toc}

##### Abstract
Blind image quality assessment (BIQA) aims to predict perceptual image quality scores without access to reference images. State-of-the-art BIQA methods typically require subjects to score a large number of images to train a robust model. However, subjective quality scores are imprecise, biased, and inconsistent, and it is challenging to obtain a large scale database, or to extend existing databases, because of the inconvenience of collecting images, training the subjects, conducting subjective experiments, and realigning human quality evaluations. To combat these limitations, this paper explores and exploits preference image pairs (PIPs) such as "the quality of image $I_a$ is better than that of image $I_b$" for training a robust BIQA model. The preference label, representing the relative quality of two images, is generally precise and consistent, and is not sensitive to image content, distortion type, or subject identity; such PIPs can be generated at very low cost. The proposed BIQA method is one of learning to rank. We first formulate the problem of learning the mapping from the image features to the preference label as one of classification. In particular, we investigate the utilization of a multiple kernel learning algorithm based on group lasso (MKLGL) to provide a solution. A simple but effective strategy to estimate perceptual image quality scores is then presented. Experiments show that the proposed BIQA method is highly effective and achieves comparable performance to state-of-the-art BIQA algorithms. Moreover, the proposed method can be easily extended to new distortion categories.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1309.0213](http://arxiv.org/abs/1309.0213)

##### PDF
[http://arxiv.org/pdf/1309.0213](http://arxiv.org/pdf/1309.0213)

