---
layout: post
title: "Face Alignment Across Large Poses: A 3D Solution"
date: 2015-11-23 13:23:19
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Xiangyu Zhu, Zhen Lei, Xiaoming Liu, Hailin Shi, Stan Z. Li
mathjax: true
---

* content
{:toc}

##### Abstract
Face alignment, which fits a face model to an image and extracts the semantic meanings of facial pixels, has been an important topic in CV community. However, most algorithms are designed for faces in small to medium poses (below 45 degree), lacking the ability to align faces in large poses up to 90 degree. The challenges are three-fold: Firstly, the commonly used landmark-based face model assumes that all the landmarks are visible and is therefore not suitable for profile views. Secondly, the face appearance varies more dramatically across large poses, ranging from frontal view to profile view. Thirdly, labelling landmarks in large poses is extremely challenging since the invisible landmarks have to be guessed. In this paper, we propose a solution to the three problems in an new alignment framework, called 3D Dense Face Alignment (3DDFA), in which a dense 3D face model is fitted to the image via convolutional neutral network (CNN). We also propose a method to synthesize large-scale training samples in profile views to solve the third problem of data labelling. Experiments on the challenging AFLW database show that our approach achieves significant improvements over state-of-the-art methods.

##### Abstract (translated by Google)
面部对齐，将人脸模型拟合成图像，提取面部像素的语义，是CV社区的一个重要课题。但是，大多数算法都是针对小到中等姿势（低于45度）的面部进行设计的，缺乏将姿势调整到90度以上的能力。挑战有三个方面：首先，常用的基于地标的人脸模型假设所有地标都是可见的，因此不适合剖面视图。其次，脸型从正面看到配置文件视角在大型姿势中变化更大。第三，由于不可见的地标必须被猜测，因此以大姿势标记地标是非常具有挑战性的。在本文中，我们提出了一个新的对齐框架中的三个问题的解决方案，称为三维密集面对齐（3DDFA），其中密集的三维人脸模型通过卷积中性网络（CNN）拟合图像。我们还提出了一种在剖面视图中合成大规模训练样本的方法，以解决数据标记的第三个问题。在具有挑战性的AFLW数据库上的实验表明，我们的方法比最先进的方法取得了显着的改进。

##### URL
[https://arxiv.org/abs/1511.07212](https://arxiv.org/abs/1511.07212)

##### PDF
[https://arxiv.org/pdf/1511.07212](https://arxiv.org/pdf/1511.07212)

