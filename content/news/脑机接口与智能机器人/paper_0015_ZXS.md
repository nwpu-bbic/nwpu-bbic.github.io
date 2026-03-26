---
author: 张晓珊
title: "顶会MICCAI early accept论文：DTCA：交叉注意力下的双Transformer的脑电和眼动数据融合"
date: 2024-05-14
categories: 脑机接口与智能机器人
tags: 脑机接口与智能机器人
authorimage: ../assets/images/global/favicon-32x32.png
language: zh-CN
featured_image: ../assets/images/featured/paper_images/paper_0015_图1.png
summary: 论文“DTCA：“Dual-Branch Transformer with Cross-Attention for EEG and Eye Movement Data Fusion”被会议MICCAI2024 early accept

---

## <center>论文“DTCA: Dual-Branch Transformer with Cross-Attention for EEG and Eye Movement Data Fusion”被会议MICCAI2024 early accept


#### 时间：2024-05-14
#### 关键词：脑机接口与智能机器人，文章接收



&emsp;&emsp;近日，硕士研究生张晓珊在MICCAI2024 上发表题为“DTCA: Dual-Branch Transformer with Cross-Attention for EEG and Eye Movement Data Fusion”的文章，通讯作者为张枢教授。

#### Objective: 

&emsp;&emsp;Integrating Electroencephalography (EEG) and eye movements (EM) provides a comprehensive understanding of brain dynamics. However, effectively capturing essential information from EEG and EM poses challenges. Previous studies have investigated aligning and identifying correlations between them, yet they have not fully utilized the deep dynamic relationship and complementary features inherent in EEG and EM data. To address this issue, we propose the Dual-Branch Transformer with Cross-Attention (DTCA) framework. It encodes EEG and EM data into a latent space, leveraging a multimodal fusion module to learn the facilitative information and dynamic relationships between EEG and EM data. Utilizing cross-attention with pooling computation, DTCA captures the complementary features and aggregates promoted information. Extensive experiments on multiple open datasets show that DTCA outperforms previous state-of-the-art methods: 99.15% on SEED, 99.65% on SEED-IV, and 86.05% on SEED-V datasets. We also visualize confusion matrices and features to demonstrate how DTCA works. Our findings demonstrate that (1) EEG and EM effectively distinguish changes in brain states during tasks such as watching videos. (2) Encoding EEG and EM into a latent space for fusion facilitates learning promoted information and dynamic correlation associated with brain states. (3) DTCA efficiently fuses EEG and EM data to leverage their synergistic effects in understanding the brain’s dynamic processes and classifying brain states.

<img src="/images/paper_images/paper_0015_图1.png" align="center" alt="图1.Overview of Multimodal Fusion Framework." title="图1.Overview of Multimodal Fusion Framework." style="zoom:60%;"/>
<center>图1：Overview of Multimodal Fusion Framework.</center>

<img src="/images/paper_images/paper_0015_图2.png" align="center" alt="图2. Dual-Branch Transformer with Cross-Attention (DTCA) Feature Fusion Module." title="图2. Dual-Branch Transformer with Cross-Attention (DTCA) Feature Fusion Module." style="zoom:60%;"/>
<center>图2. Dual-Branch Transformer with Cross-Attention (DTCA) Feature Fusion Module.</center>






