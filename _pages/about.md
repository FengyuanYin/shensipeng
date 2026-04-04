---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
- **我是武汉大学国家网络安全学院的在读硕士研究生，我目前的研究领域是2D数字人的隐私保护。**

###  教育背景
- **2020.09-2024.07**  
  东北大学 沈阳
- **2024.09-2027.07**  
 武汉大学 武汉

### 实习
- **浙江同花顺云软件有限公司** 
- ** AIGC算法实习生** 
- 针对基于diffusion模型推理时间长,显存占用大的问题.构建基于GAN的端到端唇形同步生成框架.模型利用视频生成大模型数据和大规模真实数据进行训练,在训练的第一阶段构建lipsync模型在面对正脸位置的唇同步和人脸重构能力.在第二阶段针对不同的输入,利用多个分类器检测侧脸极端角,婴儿,遮挡等特殊情况,分别使用不同的数据集进一步微调. 由于GAN模型的训练不稳定和模式崩塌问题,在侧脸模型训练时构建极端角均匀采样的优化策略，在不损失模型原先性能的基础上提升了侧脸生成的质量.

### 项目经历
- **基于扩散模型的音频驱动唇形同步生成系统**
- 针对lipsync中GAN模型难以适配大规模数据集,易发生模式崩塌与训练不稳定的问题,构建基于Stable Diffusion的端到端唇形同步生成框架.采用估计采样策略,实现视频帧的单步扩散生成,显著提升模型收敛效率.设计 StableSyncNet 监督架构,强化音画同步精度,效果优于 Wav2Lip.引入自监督视觉模型 VideoMAE-v2,提升视频时序一致性.同时采用课程学习策略分阶段训练,缓解多任务学习难度.实验结果表明,该方法在SSIM\\,FVD,FID,LMD等指标上超越 Wav2Lip,DiffSync,MuseTalk等SOTA方案.

### 出版物
- **ErasableMask: A Robust and Erasable Privacy Protection Scheme against Black-box Face Recognition Models**  
  **Sipeng Shen†**, Yunming Zhang†, Dengpan Ye*, Xiuwen Shi, Long Tang, Haoran Duan, Yueyun Shang, Zhihong Tian — *IEEE Transactions on Multimedia*, 2025 (Accepted).

- **Three-in-One: Robust Enhanced Universal Transferable Anti-Facial Retrieval in Online Social Networks**  
  Yunna Lv, Long Tang, Dengpan Ye, Jiacheng Deng, Yiheng He, and **Sipeng Shen** — *IEEE Transactions on Information Forensics and Security*, 2025 (Accepted).

- **StyleMark: A Robust Watermarking Method for Art Style Images Against Black-Box Arbitrary Style Transfer**  
  Yunming Zhang, Dengpan Ye, **Sipeng Shen**, Jun Wang, Caiyun Xie — *IEEE Transactions on Information Forensics and Security*, 2025 (Accepted).

- **Double Privacy Guard: Robust Traceable Adversarial Watermarking against Face Recognition**  
**Under Review.

### 荣誉及获奖
- **国家奖学金**
- **东北大学一等奖学金**
- **东北大学优秀学生**

### 公益
- **Pattern Recognition 审稿人.**
