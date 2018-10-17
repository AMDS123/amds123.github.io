---
layout: post
title: "Equivalent Constraints for Two-View Geometry: Pose Solution/Pure Rotation Identification and 3D Reconstruction"
date: 2018-10-13 13:51:15
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation
author: Qi Cai, Yuanxin Wu, Lilian Zhang, Peike Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Two-view relative pose estimation and structure reconstruction is a classical problem in computer vision. The typical methods usually employ the singular value decomposition of the essential matrix to get multiple solutions of the relative pose, from which the right solution is picked out by reconstructing the three-dimension (3D) feature points and imposing the constraint of positive depth. This paper revisits the two-view geometry problem and discovers that the two-view imaging geometry is equivalently governed by a Pair of new Pose-Only (PPO) constraints: the same-side constraint and the intersection constraint. From the perspective of solving equation, the complete pose solutions of the essential matrix are explicitly derived and we rigorously prove that the orientation part of the pose can still be recovered in the case of pure rotation. The PPO constraints are simplified and formulated in the form of inequalities to directly identify the right pose solution with no need of 3D reconstruction and the 3D reconstruction can be analytically achieved from the identified right pose. Furthermore, the intersection inequality also enables a robust criterion for pure rotation identification. Experiment results validate the correctness of analyses and the robustness of the derived pose solution/pure rotation identification and analytical 3D reconstruction.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.05863](https://arxiv.org/abs/1810.05863)

##### PDF
[https://arxiv.org/pdf/1810.05863](https://arxiv.org/pdf/1810.05863)

