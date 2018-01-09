---
layout: post
title: "Building Generalizable Agents with a Realistic and Rich 3D Environment"
date: 2018-01-07 16:34:41
categories: arXiv_AI
tags: arXiv_AI Segmentation
author: Yi Wu, Yuxin Wu, Georgia Gkioxari, Yuandong Tian
mathjax: true
---

* content
{:toc}

##### Abstract
Towards bridging the gap between machine and human intelligence, it is of utmost importance to introduce environments that are visually realistic and rich in content. In such environments, one can evaluate and improve a crucial property of practical intelligent systems, namely \emph{generalization}. In this work, we build \emph{House3D}, a rich, extensible and efficient environment that contains 45,622 human-designed 3D scenes of houses, ranging from single-room studios to multi-storeyed houses, equipped with a diverse set of fully labeled 3D objects, textures and scene layouts, based on the SUNCG dataset (Song et al., 2017). With an emphasis on semantic-level generalization, we study the task of concept-driven navigation, \emph{RoomNav}, using a subset of houses in House3D. In RoomNav, an agent navigates towards a target specified by a semantic concept. To succeed, the agent learns to comprehend the scene it lives in by developing perception, understand the concept by mapping it to the correct semantics, and navigate to the target by obeying the underlying physical rules. We train RL agents with both continuous and discrete action spaces and show their ability to generalize in new unseen environments. In particular, we observe that (1) training is substantially harder on large house sets but results in better generalization, (2) using semantic signals (e.g., segmentation mask) boosts the generalization performance, and (3) gated networks on semantic input signal lead to improved training performance and generalization. We hope House3D, including the analysis of the RoomNav task, serves as a building block towards designing practical intelligent systems and we wish it to be broadly adopted by the community.

##### Abstract (translated by Google)
为了弥合机器与人类智能之间的差距，引入视觉逼真和内容丰富的环境是非常重要的。在这样的环境中，人们可以评估和改进实际智能系统的一个关键性质，即\ emph {generalization}。在这项工作中，我们构建了一个丰富，可扩展和高效的环境，这个环境包含45,622个人性化的3D房屋场景，从单房工作室到多层房屋，配备了各种各样的完全标记三维物体，纹理和场景布局，基于SUNCG数据集（Song et al。，2017）。重点在于语义层面的概括，我们使用House3D中的房子子集来研究概念驱动导航的任务：emph {RoomNav}。在RoomNav中，代理人通过语义概念指向目标。为了获得成功，代理人通过发展知觉来理解其所处的场景，通过将概念映射到正确的语义来理解概念，并通过服从潜在的物理规则导航到目标。我们训练RL代理人连续和离散的行动空间，并展示他们的能力推广在新的看不见的环境。 （2）使用语义信号（例如分段掩模）提高了泛化性能，（3）门控网络中的语义输入信号（1）在大型房屋集合上训练更加困难，但导致更好的泛化。导致改进的训练表现和泛化。我们希望House3D，包括RoomNav任务的分析，是设计实用智能系统的基石，希望能够被社区广泛采用。

##### URL
[http://arxiv.org/abs/1801.02209](http://arxiv.org/abs/1801.02209)

##### PDF
[http://arxiv.org/pdf/1801.02209](http://arxiv.org/pdf/1801.02209)

