---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am currently a third-year MSc student in Jiangsu Provincial Engineering Laboratory of Pattern Recognition and Computational Intelligence, [Jiangnan University](https://www.jiangnan.edu.cn/). My research field focuses on skeleton-based action recognition, which is about the process of recognizing actions based on key points.I am very fortunate to be advised by [Assoc. Prof. XuTianyang](https://xu-tianyang.github.io/) of [Jiangnan University](https://www.jiangnan.edu.cn/).

You can find my CV here: [ZhouYouwei's Curriculum Vitae](../assets/Curriculum_Vitae.pdf).

[Email](1805063546@qq.com) / [Github](https://github.com/6UOOON9) / [Wechat](../images/wechat.jpg)


Research
======
**Adaptive Hyper-graph Convolution Network for Skeleton-based Human Action Recognition with Virtual Connections** (ICCV 2025)

- Most of the existing GCNs rely on the binary connection of two neighboring vertices (joints) formed by a nedge(bone), overlooking the potential of constructing multi-vertex convolution structures. To address this, we propose a method of constructing adaptive hyper-graph (A-NHG) to characterize the multivariate synergistic relationships among human joints in action.
- In order to enrich the general semantic information of actions, we introduce the learnable virtual hyper-joints with physical joints to inspire the model to learn generic information about human behavior implicit in the data.
- The multi-head hyper-graph convolution (M-HGC) is designed for skeleton-based action recognition. The accuracy of Hyper-GCN has achieved the SOTA level on public datasets. The code has been open-sourced to [Hyper-GCN](https://github.com/6UOOON9/Hyper-GCN).

**A Hybrid Multi-Perspective Complementary Model for Human Skeleton-Based Action Recognition** (ICME Workshop 2024 2-nd Place)

- Fine-tuning and ensemble for Skeleton-MixFormer, InfoGCN and STTFormer on UAV-Hum an dataset (UAV view) for skeleton-based human recognition task.
- Adopting multi-modality and multi-model ensemble, introducing FR-Head and Focal Loss to distinguish difficult samples in action.
- The proposed solution improves the accuracy by more than 10% on the basis of the origi nal official baseline. It has achieved 48.51% in V1 and 76.13% in V2. The code has been open-sourced to [UAV-SAR](https://github.com/happylinze/UAV-SAR).


