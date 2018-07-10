---
layout: post
title: "Auto-Context R-CNN"
date: 2018-07-08 15:45:28
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection CNN Prediction Detection
author: Bo Li, Tianfu Wu, Lun Zhang, Rufeng Chu
mathjax: true
---

* content
{:toc}

##### Abstract
Region-based convolutional neural networks (R-CNN)~\cite{fast_rcnn,faster_rcnn,mask_rcnn} have largely dominated object detection. Operators defined on RoIs (Region of Interests) play an important role in R-CNNs such as RoIPooling~\cite{fast_rcnn} and RoIAlign~\cite{mask_rcnn}. They all only utilize information inside RoIs for RoI prediction, even with their recent deformable extensions~\cite{deformable_cnn}. Although surrounding context is well-known for its importance in object detection, it has yet been integrated in R-CNNs in a flexible and effective way. Inspired by the auto-context work~\cite{auto_context} and the multi-class object layout work~\cite{nms_context}, this paper presents a generic context-mining RoI operator (i.e., \textit{RoICtxMining}) seamlessly integrated in R-CNNs, and the resulting object detection system is termed \textbf{Auto-Context R-CNN} which is trained end-to-end. The proposed RoICtxMining operator is a simple yet effective two-layer extension of the RoIPooling or RoIAlign operator. Centered at an object-RoI, it creates a $3\times 3$ layout to mine contextual information adaptively in the $8$ surrounding context regions on-the-fly. Within each of the $8$ context regions, a context-RoI is mined in term of discriminative power and its RoIPooling / RoIAlign features are concatenated with the object-RoI for final prediction. \textit{The proposed Auto-Context R-CNN is robust to occlusion and small objects, and shows promising vulnerability for adversarial attacks without being adversarially-trained.} In experiments, it is evaluated using RoIPooling as the backbone and shows competitive results on Pascal VOC, Microsoft COCO, and KITTI datasets (including $6.9\%$ mAP improvements over the R-FCN~\cite{rfcn} method on COCO \textit{test-dev} dataset and the first place on both KITTI pedestrian and cyclist detection as of this submission).

##### Abstract (translated by Google)
基于区域的卷积神经网络（R-CNN）〜\ cite {fast_rcnn，faster_rcnn，mask_rcnn}在很大程度上主导了对象检测。在RoIs（兴趣区域）上定义的运营商在R-CNN中扮演重要角色，例如RoIPooling~ \ cite {fast_rcnn}和RoIAlign~ \ cite {mask_rcnn}。它们都只利用RoIs中的信息进行RoI预测，即使是最近的可变形扩展〜\ cite {deformable_cnn}。尽管周围环境因其在物体检测中的重要性而众所周知，但它已经以灵活有效的方式集成在R-CNN中。受自动上下文工作〜\ cite {auto_context}和多类对象布局工作〜\ cite {nms_context}的启发，本文提出了一个通用的上下文挖掘RoI操作符（即\ textit {RoICtxMining}）无缝集成在R-CNN和由此产生的对象检测系统被称为\ textbf {Auto-Context R-CNN}，它是端到端训练的。建议的RoICtxMining运算符是RoIPooling或RoIAlign运算符的简单而有效的两层扩展。以对象RoI为中心，它创建了一个$ 3 \ times 3 $布局，以便在$ 8 $周围环境区域内即时自适应地挖掘上下文信息。在每个$ 8 $上下文区域内，根据判别力挖掘上下文RoI，并将其RoIPooling / RoIAlign特征与object-RoI连接以进行最终预测。 \ textit {建议的自动上下文R-CNN对遮挡和小物体具有很强的鲁棒性，并且在没有经过对抗训练的情况下显示出对抗攻击的有希望的脆弱性。}在实验中，使用RoIPooling作为骨干进行评估，并在Pascal上显示出有竞争力的结果VOC，Microsoft COCO和KITTI数据集（包括对COCO \ textit {test-dev}数据集上的R-FCN~ \ cite {rfcn}方法的6.9％/％$ mAP改进，以及KITTI步行和骑车人检测的第一个位置这个提交）。

##### URL
[http://arxiv.org/abs/1807.02842](http://arxiv.org/abs/1807.02842)

##### PDF
[http://arxiv.org/pdf/1807.02842](http://arxiv.org/pdf/1807.02842)

