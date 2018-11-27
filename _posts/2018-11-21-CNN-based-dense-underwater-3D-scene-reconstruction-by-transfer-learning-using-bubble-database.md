---
layout: post
title: "CNN based dense underwater 3D scene reconstruction by transfer learning using bubble database"
date: 2018-11-21 01:08:51
categories: arXiv_CV
tags: arXiv_CV Face CNN Transfer_Learning
author: Kazuto Ichimaru, Ryo Furukawa, Hiroshi Kawasaki
mathjax: true
---

* content
{:toc}

##### Abstract
Dense 3D shape acquisition of swimming human or live fish is an important research topic for sports, biological science and so on. For this purpose, active stereo sensor is usually used in the air, however it cannot be applied to the underwater environment because of refraction, strong light attenuation and severe interference of bubbles. Passive stereo is a simple solution for capturing dynamic scenes at underwater environment, however the shape with textureless surfaces or irregular reflections cannot be recovered. Recently, the stereo camera pair with a pattern projector for adding artificial textures on the objects is proposed. However, to use the system for underwater environment, several problems should be compensated, i.e., disturbance by fluctuation and bubbles. Simple solution is to use convolutional neural network for stereo to cancel the effects of bubbles and/or water fluctuation. Since it is not easy to train CNN with small size of database with large variation, we develop a special bubble generation device to efficiently create real bubble database of multiple size and density. In addition, we propose a transfer learning technique for multi-scale CNN to effectively remove bubbles and projected-patterns on the object. Further, we develop a real system and actually captured live swimming human, which has not been done before. Experiments are conducted to show the effectiveness of our method compared with the state of the art techniques.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.09675](https://arxiv.org/abs/1811.09675)

##### PDF
[https://arxiv.org/pdf/1811.09675](https://arxiv.org/pdf/1811.09675)

