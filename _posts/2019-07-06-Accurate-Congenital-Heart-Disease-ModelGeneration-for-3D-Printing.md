---
layout: post
title: "Accurate Congenital Heart Disease ModelGeneration for 3D Printing"
date: 2019-07-06 15:15:06
categories: arXiv_CV
tags: arXiv_CV Segmentation Deep_Learning
author: Xiaowei Xu, Tianchen Wang, Dewen Zeng, Yiyu Shi, Qianjun Jia, Haiyun Yuan, Meiping Huang, Jian Zhuang
mathjax: true
---

* content
{:toc}

##### Abstract
3D printing has been widely adopted for clinical decision making and interventional planning of Congenital heart disease (CHD), while whole heart and great vessel segmentation is the most significant but time-consuming step in the model generation for 3D printing. While various automatic whole heart and great vessel segmentation frameworks have been developed in the literature, they are ineffective when applied to medical images in CHD, which have significant variations in heart structure and great vessel connections. To address the challenge, we leverage the power of deep learning in processing regular structures and that of graph algorithms in dealing with large variations and propose a framework that combines both for whole heart and great vessel segmentation in CHD. Particularly, we first use deep learning to segment the four chambers and myocardium followed by bloodpool, where variations are usually small. We then extract the connection information and apply graph matching to determine the categories of all the vessels. Experimental results using 683D CT images covering 14 types of CHD show that our method can increase Dice score by 11.9% on average compared with the state-of-the-art whole heart and great vessel segmentation method in normal anatomy. The segmentation results are also printed out using 3D printers for validation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05273](http://arxiv.org/abs/1907.05273)

##### PDF
[http://arxiv.org/pdf/1907.05273](http://arxiv.org/pdf/1907.05273)

