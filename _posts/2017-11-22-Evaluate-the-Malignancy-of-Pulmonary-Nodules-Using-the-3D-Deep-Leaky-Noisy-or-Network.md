---
layout: post
title: "Evaluate the Malignancy of Pulmonary Nodules Using the 3D Deep Leaky Noisy-or Network"
date: 2017-11-22 15:14:10
categories: arXiv_CV
tags: arXiv_CV Detection Relation
author: Fangzhou Liao, Ming Liang, Zhe Li, Xiaolin Hu, Sen Song
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic diagnosing lung cancer from Computed Tomography (CT) scans involves two steps: detect all suspicious lesions (pulmonary nodules) and evaluate the whole-lung/pulmonary malignancy. Currently, there are many studies about the first step, but few about the second step. Since the existence of nodule does not definitely indicate cancer, and the morphology of nodule has a complicated relationship with cancer, the diagnosis of lung cancer demands careful investigations on every suspicious nodule and integration of information of all nodules. We propose a 3D deep neural network to solve this problem. The model consists of two modules. The first one is a 3D region proposal network for nodule detection, which outputs all suspicious nodules for a subject. The second one selects the top five nodules based on the detection confidence, evaluates their cancer probabilities and combines them with a leaky noisy-or gate to obtain the probability of lung cancer for the subject. The two modules share the same backbone network, a modified U-net. The over-fitting caused by the shortage of training data is alleviated by training the two modules alternately. The proposed model won the first place in the Data Science Bowl 2017 competition. The code has been made publicly available.

##### Abstract (translated by Google)
从计算机断层扫描（CT）扫描自动诊断肺癌涉及两个步骤：检测所有可疑病变（肺结节）和评估全肺/肺部恶性肿瘤。目前，关于第一步有许多研究，但第二步很少。既然结节的存在并不能明确指示癌症，结节的形态与癌症的复杂关系，肺癌的诊断需要仔细调查每一个可疑的结节和所有结节的信息整合。我们提出了一个三维深度神经网络来解决这个问题。该模型由两个模块组成。第一个是用于结节检测的3D区域提议网络，其输出所有可疑的结节。第二个是根据检测的可信度选择前五个结节，评估他们的癌症概率，并将它们与泄漏的噪声或门相结合，以获得受试者的肺癌概率。这两个模块共享相同的骨干网络，一个修改的U网。训练数据不足导致的过度训练通过交替训练这两个模块来缓解。提出的模型赢得了数据科学碗2017年比赛的第一名。该代码已公开发布。

##### URL
[https://arxiv.org/abs/1711.08324](https://arxiv.org/abs/1711.08324)

##### PDF
[https://arxiv.org/pdf/1711.08324](https://arxiv.org/pdf/1711.08324)

