---
layout: post
title: "Detection of Unauthorized IoT Devices Using Machine Learning Techniques"
date: 2017-09-14 07:50:46
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Classification Detection
author: Yair Meidan, Michael Bohadana, Asaf Shabtai, Martin Ochoa, Nils Ole Tippenhauer, Juan Davis Guarnizo, Yuval Elovici
mathjax: true
---

* content
{:toc}

##### Abstract
Security experts have demonstrated numerous risks imposed by Internet of Things (IoT) devices on organizations. Due to the widespread adoption of such devices, their diversity, standardization obstacles, and inherent mobility, organizations require an intelligent mechanism capable of automatically detecting suspicious IoT devices connected to their networks. In particular, devices not included in a white list of trustworthy IoT device types (allowed to be used within the organizational premises) should be detected. In this research, Random Forest, a supervised machine learning algorithm, was applied to features extracted from network traffic data with the aim of accurately identifying IoT device types from the white list. To train and evaluate multi-class classifiers, we collected and manually labeled network traffic data from 17 distinct IoT devices, representing nine types of IoT devices. Based on the classification of 20 consecutive sessions and the use of majority rule, IoT device types that are not on the white list were correctly detected as unknown in 96% of test cases (on average), and white listed device types were correctly classified by their actual types in 99% of cases. Some IoT device types were identified quicker than others (e.g., sockets and thermostats were successfully detected within five TCP sessions of connecting to the network). Perfect detection of unauthorized IoT device types was achieved upon analyzing 110 consecutive sessions; perfect classification of white listed types required 346 consecutive sessions, 110 of which resulted in 99.49% accuracy. Further experiments demonstrated the successful applicability of classifiers trained in one location and tested on another. In addition, a discussion is provided regarding the resilience of our machine learning-based IoT white listing method to adversarial attacks.

##### Abstract (translated by Google)
安全专家已经展示了物联网（IoT）设备对组织带来的无数风险。由于这种设备的广泛采用，其多样性，标准化障碍和固有的移动性，组织需要一种能够自动检测连接到其网络的可疑物联网设备的智能机制。特别是，应该检测到不包括在可信的物联网设备类型的白名单中（允许在组织场所内使用）的设备。在这项研究中，随机森林，监督机器学习算法，被应用于从网络流量数据中提取的特征，目的是从白名单中准确地识别物联网设备类型。为了训练和评估多级分类器，我们从17个不同的物联网设备收集并手动标记了网络流量数据，代表了九种类型的物联网设备。根据连续20次会话的分类以及多数规则的使用情况，在96％的测试用例（平均）中，未在白名单上的物联网设备类型被正确检测为未知，并且白名单设备类型被正确分类他们的实际类型在99％的情况下。某些物联网设备类型比其他设备类型更快（例如，在连接到网络的五个TCP会话内成功检测到套接字和恒温器）。通过分析110个连续会话，完成对未经授权的物联网设备类型的完美检测;白名单的完美分类需要346个连续会议，其中110个准确率为99.49％。进一步的实验证明分类器在一个位置训练的成功适用性，并在另一个位置进行测试。此外，还提供了关于我们基于机器学习的物联网白名单方法对敌对攻击的适应性的讨论。

##### URL
[https://arxiv.org/abs/1709.04647](https://arxiv.org/abs/1709.04647)

##### PDF
[https://arxiv.org/pdf/1709.04647](https://arxiv.org/pdf/1709.04647)

