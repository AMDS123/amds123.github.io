---
layout: post
title: "Factors in Finetuning Deep Model for object detection"
date: 2016-04-14 01:15:12
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Detection
author: Wanli Ouyang, Xiaogang Wang, Cong Zhang, Xiaokang Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Finetuning from a pretrained deep model is found to yield state-of-the-art performance for many vision tasks. This paper investigates many factors that influence the performance in finetuning for object detection. There is a long-tailed distribution of sample numbers for classes in object detection. Our analysis and empirical results show that classes with more samples have higher impact on the feature learning. And it is better to make the sample number more uniform across classes. Generic object detection can be considered as multiple equally important tasks. Detection of each class is a task. These classes/tasks have their individuality in discriminative visual appearance representation. Taking this individuality into account, we cluster objects into visually similar class groups and learn deep representations for these groups separately. A hierarchical feature learning scheme is proposed. In this scheme, the knowledge from the group with large number of classes is transferred for learning features in its sub-groups. Finetuned on the GoogLeNet model, experimental results show 4.7% absolute mAP improvement of our approach on the ImageNet object detection dataset without increasing much computational cost at the testing stage.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1601.05150](https://arxiv.org/abs/1601.05150)

##### PDF
[https://arxiv.org/pdf/1601.05150](https://arxiv.org/pdf/1601.05150)

