---
layout: post
title: "Pairwise Relational Networks for Face Recognition"
date: 2018-08-15 05:52:31
categories: arXiv_CV
tags: arXiv_CV Face RNN Relation Recognition Face_Recognition
author: Bong-Nam Kang, Yonghyun Kim, Daijin Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Existing face recognition using deep neural networks is difficult to know what kind of features are used to discriminate the identities of face images clearly. To investigate the effective features for face recognition, we propose a novel face recognition method, called a pairwise relational network (PRN), that obtains local appearance patches around landmark points on the feature map, and captures the pairwise relation between a pair of local appearance patches. The PRN is trained to capture unique and discriminative pairwise relations among different identities. Because the existence and meaning of pairwise relations should be identity dependent, we add a face identity state feature, which obtains from the long short-term memory (LSTM) units network with the sequential local appearance patches on the feature maps, to the PRN. To further improve accuracy of face recognition, we combined the global appearance representation with the pairwise relational feature. Experimental results on the LFW show that the PRN using only pairwise relations achieved 99.65% accuracy and the PRN using both pairwise relations and face identity state feature achieved 99.76% accuracy. On the YTF, both the PRN using only pairwise relations and the PRN using pairwise relations and the face identity state feature achieved the state-of-the-art (95.7% and 96.3%). The PRN also achieved comparable results to the state-of-the-art for both face verification and face identification tasks on the IJB-A, and the state-of-the-art on the IJB-B.

##### Abstract (translated by Google)
使用深度神经网络的现有面部识别难以知道使用何种特征来清楚地区分面部图像的身份。为了研究人脸识别的有效特征，我们提出了一种新的人脸识别方法，称为成对关系网络（PRN），获取特征图上标志点周围的局部外观斑块，并捕获一对局部外观之间的成对关系。补丁。 PRN经过训练以捕获不同身份之间的独特和判别性成对关系。因为成对关系的存在和意义应该是依赖于身份的，所以我们添加一个面部身份状态特征，它从长期短期记忆（LSTM）单元网络获得特征图上的连续局部外观补丁到PRN。为了进一步提高人脸识别的准确性，我们将全局外观表示与成对关系特征相结合。 LFW的实验结果表明，仅使用成对关系的PRN精度达到99.65％，使用成对关系和面部身份状态特征的PRN精度达到99.76％。在YTF上，仅使用成对关系的PRN和使用成对关系的PRN和面部身份状态特征都达到了现有技术水平（95.7％和96.3％）。 PRN在IJB-A上的面部验证和面部识别任务以及IJB-B的最新技术方面也取得了与现有技术相当的结果。

##### URL
[http://arxiv.org/abs/1808.04976](http://arxiv.org/abs/1808.04976)

##### PDF
[http://arxiv.org/pdf/1808.04976](http://arxiv.org/pdf/1808.04976)

