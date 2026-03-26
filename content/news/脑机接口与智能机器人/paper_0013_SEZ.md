---
author: 史恩泽
title: "期刊TBME发表论文：一种用于大脑状态解码的多频段EEG Transformer"
date: 2023-12-06
categories: 脑机接口与智能机器人
tags: 脑机接口与智能机器人
authorimage: ../assets/images/global/favicon-32x32.png
language: zh-CN

featured_image: ../assets/images/featured/paper_images/paper_0013_图1.png
summary: "论文“MEET: A Multi-Band EEG Transformer for Brain States Decoding”被期刊TBME接收"

---

## <center>论文“MEET: A Multi-Band EEG Transformer for Brain States Decoding”被期刊TBME接收


#### 时间：2023-12-06
#### 关键词：脑机接口与智能机器人，文章接收



&emsp;&emsp;近日，硕士研究生史恩泽在计算机科学领域高质量水平期刊（IEEE Transactions on Biomedical Engineering，IF = 4.6，JCR Q2）发表题为“MEET: A Multi-Band EEG Transformer for Brain States Decoding”的研究性文章，通讯作者为张枢教授。

#### Objective: 

&emsp;&emsp;Electroencephalography (EEG) is among the most widely used and inexpensive neuroimaging techniques. Compared to the CNN or RNN based models, Transformer can better capture the temporal information in EEG signals and focus more on global features of the brain's functional activities. Importantly, according to the multiscale nature of EEG signals, it is crucial to consider the multi-band concept into the design of EEG Transformer architecture. Methods: We propose a novel Multi-band EEG Transformer (MEET) to represent and analyze the multiscale temporal time series of human brain EEG signals (图 1). MEET mainly includes three parts: 1) transform the EEG signals into multi-band images, and preserve the 3D spatial information between electrodes; 2) design a Band Attention Block to compute the attention maps of the stacked multi-band images and infer the fused feature maps; 3) apply the Temporal Self-Attention and Spatial Self-Attention modules to extract the spatiotemporal features for the characterization and differentiation of multi-frame dynamic brain states (图 2). Results: The experimental results show that: 1) MEET outperforms state-of-the-art methods on multiple open EEG datasets (SEED, SEED-IV, WM) for brain states classification; 2) MEET demonstrates that 5-bands fusion is the best integration strategy; and 3) MEET identifies interpretable brain attention regions. Significance: MEET is an interpretable and universal model based on the multiband-multiscale characteristics of EEG. Conclusion: The innovative combination of band attention and temporal/spatial self-attention mechanisms in MEET achieves promising data-driven learning of the temporal dependencies and spatial relationships of EEG signals across the entire brain in a holistic and comprehensive fashion. 

<img src="/images/paper_images/paper_0013_图1.png" align="center" alt="图1.MEET模型框架" title="图1.MEET模型框架" style="zoom:80%;"/>
<center>图1：MEET模型框架</center>

<center><img src="/images/paper_images/paper_0013_图2.png" align="center" alt="图2：Band Attention Block与Temporal Self-Attention Block示意图" title="图2：Band Attention Block与Temporal Self-Attention Block示意图" style="zoom:50%;"/>
图2：Band Attention Block与Temporal Self-Attention Block示意图</center>



#### 参考文献

Shi, Enze, Sigang Yu, Yanqing Kang, Jinru Wu, Lin Zhao, Dajiang Zhu, Jinglei Lv, Tianming Liu, Xintao Hu, and Shu Zhang. "MEET: A Multi-Band EEG Transformer for Brain States Decoding." IEEE Transactions on Biomedical Engineering (2023).




