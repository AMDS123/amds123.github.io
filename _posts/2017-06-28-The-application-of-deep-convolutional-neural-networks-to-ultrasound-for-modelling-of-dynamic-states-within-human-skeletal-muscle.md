---
layout: post
title: "The application of deep convolutional neural networks to ultrasound for modelling of dynamic states within human skeletal muscle"
date: 2017-06-28 19:18:04
categories: arXiv_CV
tags: arXiv_CV Image_Caption Segmentation CNN Deep_Learning
author: Ryan J. Cunningham, Peter J. Harding, Ian D. Loram
mathjax: true
---

* content
{:toc}

##### Abstract
This paper concerns the fully automatic direct in vivo measurement of active and passive dynamic skeletal muscle states using ultrasound imaging. Despite the long standing medical need (myopathies, neuropathies, pain, injury, ageing), currently technology (electromyography, dynamometry, shear wave imaging) provides no general, non-invasive method for online estimation of skeletal intramuscular states. Ultrasound provides a technology in which static and dynamic muscle states can be observed non-invasively, yet current computational image understanding approaches are inadequate. We propose a new approach in which deep learning methods are used for understanding the content of ultrasound images of muscle in terms of its measured state. Ultrasound data synchronized with electromyography of the calf muscles, with measures of joint torque/angle were recorded from 19 healthy participants (6 female, ages: 30 +- 7.7). A segmentation algorithm previously developed by our group was applied to extract a region of interest of the medial gastrocnemius. Then a deep convolutional neural network was trained to predict the measured states (joint angle/torque, electromyography) directly from the segmented images. Results revealed for the first time that active and passive muscle states can be measured directly from standard b-mode ultrasound images, accurately predicting for a held out test participant changes in the joint angle, electromyography, and torque with as little error as 0.022{\deg}, 0.0001V, 0.256Nm (root mean square error) respectively.

##### Abstract (translated by Google)
本文涉及全自动直接在体内测量主动和被动动态骨骼肌肉状态使用超声成像。尽管长期以来医学上的需求（肌病，神经病，疼痛，损伤，老化），但目前的技术（肌电图，测力，剪切波成像）不能提供用于在线评估骨骼肌肉状态的一般非侵入性方法。超声提供了一种技术，其中静态和动态肌肉状态可以非侵入性地被观察到，然而目前的计算图像理解方法是不充分的。我们提出了一种新的方法，其中使用深度学习方法来了解肌肉的超声图像的内容在其测量状态方面。记录来自19位健康参与者（6名女性，年龄：30±7.7）的与小腿肌肉肌电图同步的超声数据，以及关节扭矩/角度的测量。我们的小组以前开发的分割算法被应用于提取内侧腓肠肌的感兴趣区域。然后深层卷积神经网络训练，直接从分割图像预测测量状态（关节角度/扭矩，肌电图）。结果首次显示，主动和被动肌肉状态可以直接从标准的b型超声图像测量，准确地预测测试参与者关节角度，肌电图和扭矩的变化，误差为0.022 deg}，0.0001V，0.256Nm（均方根误差）。

##### URL
[https://arxiv.org/abs/1706.09450](https://arxiv.org/abs/1706.09450)

##### PDF
[https://arxiv.org/pdf/1706.09450](https://arxiv.org/pdf/1706.09450)

