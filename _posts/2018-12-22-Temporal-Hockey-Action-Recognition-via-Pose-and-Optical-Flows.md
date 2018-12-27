---
layout: post
title: "Temporal Hockey Action Recognition via Pose and Optical Flows"
date: 2018-12-22 14:15:15
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Action_Recognition Transfer_Learning Recognition
author: Zixi Cai, Helmut Neher, Kanav Vats, David Clausi, John Zelek
mathjax: true
---

* content
{:toc}

##### Abstract
Recognizing actions in ice hockey using computer vision poses challenges due to bulky equipment and inadequate image quality. A novel two-stream framework has been designed to improve action recognition accuracy for hockey using three main components. First, pose is estimated via the Part Affinity Fields model to extract meaningful cues from the player. Second, optical flow (using LiteFlowNet) is used to extract temporal features. Third, pose and optical flow streams are fused and passed to fully-connected layers to estimate the hockey player's action. A novel publicly available dataset named HARPET (Hockey Action Recognition Pose Estimation, Temporal) was created, composed of sequences of annotated actions and pose of hockey players including their hockey sticks as an extension of human body pose. Three contributions are recognized. (1) The novel two-stream architecture achieves 85% action recognition accuracy, with the inclusion of optical flows increasing accuracy by about 10%. (2) The unique localization of hand-held objects (e.g., hockey sticks) as part of pose increases accuracy by about 13%. (3) For pose estimation, a bigger and more general dataset, MSCOCO, is successfully used for transfer learning to a smaller and more specific dataset, HARPET, achieving a PCKh of 87%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.09533](http://arxiv.org/abs/1812.09533)

##### PDF
[http://arxiv.org/pdf/1812.09533](http://arxiv.org/pdf/1812.09533)

