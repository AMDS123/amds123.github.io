---
layout: post
title: "Online Localization and Prediction of Actions and Interactions"
date: 2016-12-04 22:16:55
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Prediction Detection Recognition
author: Khurram Soomro, Haroon Idrees, Mubarak Shah
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a person-centric and online approach to the challenging problem of localization and prediction of actions and interactions in videos. Typically, localization or recognition is performed in an offline manner where all the frames in the video are processed together. This prevents timely localization and prediction of actions and interactions - an important consideration for many tasks including surveillance and human-machine interaction. In our approach, we estimate human poses at each frame and train discriminative appearance models using the superpixels inside the pose bounding boxes. Since the pose estimation per frame is inherently noisy, the conditional probability of pose hypotheses at current time-step (frame) is computed using pose estimations in the current frame and their consistency with poses in the previous frames. Next, both the superpixel and pose-based foreground likelihoods are used to infer the location of actors at each time through a Conditional Random. The issue of visual drift is handled by updating the appearance models, and refining poses using motion smoothness on joint locations, in an online manner. For online prediction of action (interaction) confidences, we propose an approach based on Structural SVM that operates on short video segments, and is trained with the objective that confidence of an action or interaction increases as time progresses. Lastly, we quantify the performance of both detection and prediction together, and analyze how the prediction accuracy varies as a time function of observed action (interaction) at different levels of detection performance. Our experiments on several datasets suggest that despite using only a few frames to localize actions (interactions) at each time instant, we are able to obtain competitive results to state-of-the-art offline methods.

##### Abstract (translated by Google)
本文提出了一种以人为中心的在线方法来解决视频中的动作和交互的本地化和预测的挑战性问题。通常，本地化或识别是以离线方式执行的，其中视频中的所有帧一起处理。这妨碍了及时定位和预测行动和相互作用 - 这是许多任务（包括监视和人机交互）的重要考虑因素。在我们的方法中，我们估计每个帧的人体姿态，并使用姿态边框内的超像素训练辨别外观模型。由于每帧的姿态估计本质上是有噪声的，因此使用当前帧中的姿态估计以及它们与前一帧中的姿态的一致性来计算当前时间步（帧）处的姿态假设的条件概率。接下来，超像素和基于姿势的前景可能性被用来通过条件随机来推断演员在每次的位置。视觉漂移的问题是通过更新外观模型，并在联机位置上使用运动平滑度来提炼姿势。为了在线预测动作（交互）的可信度，我们提出了一种基于结构SVM的方法，该方法在短视频片段上进行操作，并且训练目标是随着时间的推移，动作或交互的信心增加。最后，我们一起量化检测和预测的性能，并分析预测精度如何在不同检测性能水平上作为观测行为（交互作用）的时间函数变化。我们在多个数据集上进行的实验表明，尽管只使用几帧来在每个时刻对动作（交互）进行本地化，但是我们能够获得最先进的离线方法的竞争结果。

##### URL
[https://arxiv.org/abs/1612.01194](https://arxiv.org/abs/1612.01194)

##### PDF
[https://arxiv.org/pdf/1612.01194](https://arxiv.org/pdf/1612.01194)

