---
layout: post
title: "Feature Matters: A Stage-by-Stage Approach for Knowledge Transfer"
date: 2018-12-05 05:09:45
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Classification Detection
author: Mengya Gao, Yujun Shen, Quanquan Li, Chen Change Loy, Xiaoou Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNNs) become deeper and deeper in recent years, making the study of model acceleration imperative. It is a common practice to employ a shallow network, called student, to learn from a deep one, which is termed as teacher. Prior work made many attempts to transfer different types of knowledge from teacher to student, however, there are two problems remaining unsolved. Firstly, the knowledge used by existing methods is usually manually defined, which may not be consistent with the information learned by the original model. Secondly, there lacks an effective training scheme for the transfer process, leading to degradation of performance. In this work, we argue that feature is the most important knowledge from teacher. It is sufficient for student to achieve appealing performance by just learning similar features as teacher without any processing. Based on this discovery, we further present an efficient learning strategy, which is to make student mimic features of teacher stage by stage. Extensive experiments suggest that the proposed approach significantly narrows down the gap between student and teacher, and shows strong stability on various tasks, ie classification and detection, outperforming the state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.01819](http://arxiv.org/abs/1812.01819)

##### PDF
[http://arxiv.org/pdf/1812.01819](http://arxiv.org/pdf/1812.01819)

