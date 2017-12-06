---
layout: post
title: 'Dilated FCN for Multi-Agent 2D/3D Medical Image Registration'
date: 2017-11-22 03:22:17
categories: arXiv_CV
tags: arXiv_CV CNN
author: Shun Miao, Sebastien Piat, Peter Fischer, Ahmet Tuysuzoglu, Philip Mewes, Tommaso Mansi, Rui Liao
---

* content
{:toc}

##### Abstract
2D/3D image registration to align a 3D volume and 2D X-ray images is a challenging problem due to its ill-posed nature and various artifacts presented in 2D X-ray images. In this paper, we propose a multi-agent system with an auto attention mechanism for robust and efficient 2D/3D image registration. Specifically, an individual agent is trained with dilated Fully Convolutional Network (FCN) to perform registration in a Markov Decision Process (MDP) by observing a local region, and the final action is then taken based on the proposals from multiple agents and weighted by their corresponding confidence levels. The contributions of this paper are threefold. First, we formulate 2D/3D registration as a MDP with observations, actions, and rewards properly defined with respect to X-ray imaging systems. Second, to handle various artifacts in 2D X-ray images, multiple local agents are employed efficiently via FCN-based structures, and an auto attention mechanism is proposed to favor the proposals from regions with more reliable visual cues. Third, a dilated FCN-based training mechanism is proposed to significantly reduce the Degree of Freedom in the simulation of registration environment, and drastically improve training efficiency by an order of magnitude compared to standard CNN-based training method. We demonstrate that the proposed method achieves high robustness on both spine cone beam Computed Tomography data with a low signal-to-noise ratio and data from minimally invasive spine surgery where severe image artifacts and occlusions are presented due to metal screws and guide wires, outperforming other state-of-the-art methods (single agent-based and optimization-based) by a large margin.

##### Abstract (translated by Google)
2D / 3D图像配准以对准3D体积和2D X射线图像是一个具有挑战性的问题，因为它的病态性质和2D X射线图像中呈现的各种伪像。在本文中，我们提出了一个具有自动关注机制的多智能体系统，用于稳健和高效的2D / 3D图像配准。具体来说，通过观察本地区域，利用扩张完全卷积网络（FCN）对个体代理进行训练，以在马尔可夫决策过程（MDP）中执行注册，然后基于来自多个代理的提议并且根据其相应的置信水平。本文的贡献是三倍的。首先，我们将2D / 3D配准制定为MDP，其中关于X射线成像系统适当地定义了观察，动作和奖励。其次，为了处理二维X射线图像中的各种伪影，通过基于FCN的结构有效地采用了多个本地代理，并且提出了一种自动关注机制来支持来自具有更可靠视觉提示的区域的建议。第三，提出了一种基于FCN的扩张训练机制，在注册环境模拟中显着降低了自由度，与标准的基于CNN的训练方法相比，训练效率显着提高了一个数量级。我们证明，提出的方法实现了脊柱锥束计算机断层扫描数据与低信噪比和来自微创脊柱手术的数据，其中由于金属螺钉和导丝引起的严重图像伪影和闭塞的数据具有高鲁棒性，优于其他最先进的方法（单个代理和基于优化）。

##### URL
[https://arxiv.org/abs/1712.01651](https://arxiv.org/abs/1712.01651)

