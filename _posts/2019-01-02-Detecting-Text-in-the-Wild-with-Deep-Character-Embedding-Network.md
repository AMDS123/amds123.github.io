---
layout: post
title: "Detecting Text in the Wild with Deep Character Embedding Network"
date: 2019-01-02 14:00:33
categories: arXiv_CV
tags: arXiv_CV Embedding Prediction Detection
author: Jiaming Liu, Chengquan Zhang, Yipeng Sun, Junyu Han, Errui Ding
mathjax: true
---

* content
{:toc}

##### Abstract
Most text detection methods hypothesize texts are horizontal or multi-oriented and thus define quadrangles as the basic detection unit. However, text in the wild is usually perspectively distorted or curved, which can not be easily tackled by existing approaches. In this paper, we propose a deep character embedding network (CENet) which simultaneously predicts the bounding boxes of characters and their embedding vectors, thus making text detection a simple clustering task in the character embedding space. The proposed method does not require strong assumptions of forming a straight line on general text detection, which provides flexibility on arbitrarily curved or perspectively distorted text. For character detection task, a dense prediction subnetwork is designed to obtain the confidence score and bounding boxes of characters. For character embedding task, a subnet is trained with contrastive loss to project detected characters into embedding space. The two tasks share a backbone CNN from which the multi-scale feature maps are extracted. The final text regions can be easily achieved by a thresholding process on character confidence and embedding distance of character pairs. We evaluated our method on ICDAR13, ICDAR15, MSRA-TD500, and Total-Text. The proposed method achieves state-of-the-art or comparable performance on all these datasets, and shows substantial improvement in the irregular-text datasets, i.e. Total-Text.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.00363](https://arxiv.org/abs/1901.00363)

##### PDF
[https://arxiv.org/pdf/1901.00363](https://arxiv.org/pdf/1901.00363)

