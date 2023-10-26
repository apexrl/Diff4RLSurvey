# awesome-diffusion-models-for-rl
This repository contains a collection of resources and papers on ***Diffusion Models*** for ***RL***.

[TOC]

## Papers

### Offline Reinforcement Learning

- **Planning with diffusion for flexible behavior synthesis**

  Michael Janner, Yilun Du, Joshua B. Tenenbaum, Sergey Levine

  ICML 2022

  [paper](https://arxiv.org/abs/2205.09991) / [code](https://github.com/jannerm/diffuser)

- **Diffusion policies as an expressive policy class for offline reinforcement learning**
  
  Zhendong Wang, Jonathan J Hunt, Mingyuan Zhou
  
  ICLR 2023
  
  [paper](https://arxiv.org/abs/2208.06193) / [code](https://github.com/zhendong-wang/diffusion-policies-for-offline-rl) 
  
- **Offline reinforcement learning via high-fidelity generative behavior modeling**

  Huayu Chen, Cheng Lu, Chengyang Ying, Hang Su, Jun Zhu
  
  ICLR 2023
  
  [paper](https://arxiv.org/abs/2209.14548) / [code](https://github.com/chendrag/sfbc)
  
- **Is conditional generative modeling all you need for decisionmaking**

  Anurag Ajay, Yilun Du, Abhi Gupta, Joshua B. Tenenbaum, T. Jaakkola, Pulkit Agrawal
  
  ICLR 2023
  
  [paper](https://arxiv.org/abs/2211.15657) / [code](https://github.com/xcvil/decision-diffuser/tree/main/code)
  
- **AdaptDiffuser: Diffusion Models as Adaptive Self-evolving Planners

  Zhixuan Liang, Yao Mu, Mingyu Ding, Fei Ni, Masayoshi Tomizuka, Ping Luo
  
  [paper](https://arxiv.org/abs/2302.01877) / [code](https://github.com/Liang-ZX/adaptdiffuser)
  
- **Metadiffuser: Diffusion Model as Conditional Planner for Offline Meta-RL**

  Fei Ni, Jianye Hao, Yao Mu, Yifu Yuan, Yan Zheng, Bin Wang, Zhixuan Liang
  
  ICML 2023
  
  [paper](https://arxiv.org/abs/2305.19923)

- **Hierarchical Diffusion for Offline Decision Making**

  Wenhao Li, Xiangfeng Wang, Bo Jin, Hongyuan Zha.
  
  ICML 2023
  
  [paper](https://openreview.net/forum?id=55kLa7tH9o) / [code](https://github.com/ewanlee/HDMI)
  
- **Contrastive Energy Prediction for Exact Energy-guided Diffusion Sampling in Offline Reinforcement Learning**

  Cheng Lu, Huayu Chen, Jianfei Chen, Hang Su, Chongxuan Li, Jun Zhu
  
  ICML 2023
  
  [paper](https://arxiv.org/abs/2304.12824) / [code](https://github.com/thu-ml/cep-energy-guided-diffusion)
  
- **Diffusion Model is an Effective Planner and Data Synthesizer for Multi-Task Reinforcement Learning**

  Haoran He, Chenjia Bai, Kang Xu, Zhuoran Yang, Weinan Zhang, Dong Wang, Bin Zhao, Xuelong Li
  
  NeurIPS 2023
  
  [paper](https://arxiv.org/abs/2305.18459) / [code](https://github.com/tinnerhrhe/MTDiff)
  
- **SafeDiffuser: Safe Planning with Diffusion Probabilistic Models**

  Wei Xiao, Tsun-Hsuan Wang, Chuang Gan, Daniela Rus
  
  arXiv 2023
  
  [paper](https://arxiv.org/abs/2306.00148)
  
- **MADiff: Offline Multi-agent Learning with Diffusion Models**
  
  Zhengbang Zhu, Minghuan Liu, Liyuan Mao, Bingyi Kang, Minkai Xu, Yong Yu, Stefano Ermon, Weinan Zhang
  
  arXiv 2023
  
  [paper](https://arxiv.org/abs/2305.17330)
  
- **Beyond Conservatism: Diffusion Policies in Offline Multi-agent Reinforcement Learning**

  Zhuoran Li, Ling Pan, Longbo Huang
  
  arXiv 2023
  
  [paper](https://arxiv.org/abs/2307.01472)
  
- **Instructed Diffuser with Temporal Condition Guidance for Offline Reinforcement Learning**

  Jifeng Hu, Yanchao Sun, Sili Huang, SiYuan Guo, Hechang Chen, Li Shen, Lichao Sun, Yi Chang, Dacheng Tao
  
  arXiv 2023
  
  [paper](https://arxiv.org/abs/2306.04875)
  
- **Diffusion Policies for Out-of-Distribution Generalization in Offline Reinforcement Learning**

  Suzan Ece Ada, Erhan Oztop, Emre Ugur
  
  arXiv 2023
  
  [paper](https://arxiv.org/abs/2307.04726)
  
- **DiffCPS: Diffusion Model based Constrained Policy Search for Offline Reinforcement Learning**

  Longxiang He, Linrui Zhang, Junbo Tan, Xueqian Wang
  
  arXiv 2023
  
  [paper](https://arxiv.org/abs/2310.05333) / [code](https://github.com/felix-thu/DiffCPS)
  
- **AlignDiff: Aligning Diverse Human Preferences via Behavior-Customisable Diffusion Model**

  Zibin Dong, Yifu Yuan, Jianye Hao, Fei Ni, Yao Mu, Yan Zheng, Yujing Hu, Tangjie Lv, Changjie Fan, Zhipeng Hu
  
  arXiv 2023
  
  [paper](https://arxiv.org/abs/2310.02054) / [code](https://github.com/aligndiff/aligndiff.github.io)
  
- **Boosting Continuous Control with Consistency Policy**

  Yuhui Chen, Haoran Li, Dongbin Zhao
  
  arXIv 2023
  
  [paper](https://arxiv.org/abs/2310.06343)
### Imitation Learning

- **Imitating Human Behaviour with Diffusion Models**

  Tim Pearce, Tabish Rashid, Anssi Kanervisto, Dave Bignell, Mingfei Sun, Raluca Georgescu, Sergio Valcarcel Macua, Shan Zheng Tan, Ida Momennejad, Katja Hofmann, Sam Devlin**
  
  ICLR 2023
  
  [paper](https://arxiv.org/abs/2301.10677) / [code](https://github.com/microsoft/imitating-human-behaviour-w-diffusion)

- **Diffusion Policy: Visuomotor Policy Learning via Action Diffusion**

  Cheng Chi, Siyuan Feng, Yilun Du, Zhenjia Xu, Eric Cousineau, Benjamin Burchfiel, Shuran Song
  
  RSS 2023
  
  [paper](https://arxiv.org/abs/2303.04137) / [code](https://github.com/real-stanford/diffusion_policy)
  
- **Goal-Conditioned Imitation Learning using Score-based Diffusion Policies**

  Moritz Reuss, Maximilian Li, Xiaogang Jia, Rudolf Lioutikov
  
  RSS 2023
  
  [paper](https://arxiv.org/abs/2304.02532) / [code](https://github.com/intuitive-robots/beso)
  
- **Generating Behaviorally Diverse Policies with Latent Diffusion Models**

  Shashank Hegde, Sumeet Batra, K. R. Zentner, Gaurav S. Sukhatme
  
  NeurIPS 2023
  
  [paper](https://arxiv.org/abs/2305.18738)

- **NoMaD: Goal Masking Diffusion Policies for Navigation and Exploration**

  Ajay Sridhar, Dhruv Shah, Catherine Glossop, Sergey Levine
  
  arXiv 2023
  
  [paper](https://arxiv.org/abs/2310.07896) / [code](https://github.com/robodhruv/visualnav-transformer)
  
### Trajectory Generation

- **MotionDiffuse: Text-Driven Human Motion Generation with Diffusion Model**
  
  Mingyuan Zhang, Zhongang Cai, Liang Pan, Fangzhou Hong, Xinying Guo, Lei Yang, Ziwei Liu
  
  arXiv 2022
  
  [paper](https://arxiv.org/abs/2208.15001) / [code](https://github.com/mingyuan-zhang/MotionDiffuse)
  
- **Human Motion Diffusion Model**

  Guy Tevet, Sigal Raab, Brian Gordon, Yonatan Shafir, Daniel Cohen-Or, Amit H. Bermano
  
  ICLR 2023
  
  [paper](https://arxiv.org/abs/2209.14916) / [code](https://github.com/guytevet/motion-diffusion-model)
  
- **Executing your Commands via Motion Diffusion in Latent Space**
  
  Xin Chen, Biao Jiang, Wen Liu, Zilong Huang, Bin Fu, Tao Chen, Jingyi Yu, Gang Yu
  
  CVPR 2023
  
  [paper](https://arxiv.org/abs/2212.04048) / [code](https://github.com/chenfengye/motion-latent-diffusion)
- **MoFusion: A Framework for Denoising-Diffusion-based Motion Synthesis**

  Rishabh Dabral, Muhammad Hamza Mughal, Vladislav Golyanik, Christian Theobalt
  
  CVPR 2023
  
  [paper](https://arxiv.org/abs/2212.04495) / [code](https://github.com/OFA-Sys/MoFusion)
  
- **ReMoDiffuse: Retrieval-Augmented Motion Diffusion Model**
  
  Mingyuan Zhang, Xinying Guo, Liang Pan, Zhongang Cai, Fangzhou Hong, Huirong Li, Lei Yang, Ziwei Liu
  
  ICCV 2023
  
  [paper](https://arxiv.org/abs/2304.01116) / [code](https://github.com/mingyuan-zhang/ReMoDiffuse)
  
- **MotionDiffuser: Controllable Multi-Agent Motion Prediction using Diffusion**

  Chiyu Max Jiang, Andre Cornman, Cheolho Park, Ben Sapp, Yin Zhou, Dragomir Anguelov
  
  CVPR 2023
  
  [paper](https://arxiv.org/abs/2306.03083) / [code]()
  
- **Learning Universal Policies via Text-Guided Video Generation**

  Yilun Du, Mengjiao Yang, Bo Dai, Hanjun Dai, Ofir Nachum, Joshua B. Tenenbaum, Dale Schuurmans, Pieter Abbeel
  
  NeurIPS 2023
  
  [paper](https://arxiv.org/abs/2310.08576)

- **Video Language Planning**

  Yilun Du, Mengjiao Yang, Pete Florence, Fei Xia, Ayzaan Wahid, Brian Ichter, Pierre Sermanet, Tianhe Yu, Pieter Abbeel, Joshua B. Tenenbaum, Leslie Kaelbling, Andy Zeng, Jonathan Tompson
  
  arXiv 2023
  
  [paper](https://arxiv.org/abs/2310.10625) / [code](https://github.com/video-language-planning/vlp_code)
  
- **Learning to Act from Actionless Video through Dense Correspondences**

  Po-Chen Ko, Jiayuan Mao, Yilun Du, Shao-Hua Sun, Joshua B. Tenenbaum
  
  arXiv 2023
  
  [paper](https://arxiv.org/abs/2310.08576) / [code](https://github.com/flow-diffusion/AVDC)
  
- **Learning Interactive Real-World Simulators**

  Mengjiao Yang, Yilun Du, Kamyar Ghasemipour, Jonathan Tompson, Dale Schuurmans, Pieter Abbeel
  
  arXiv 2023
  
  [paper](https://arxiv.org/abs/2310.06114)

### Data Augmentation

- **Scaling Robot Learning with Semantically Imagined Experience**

  Tianhe Yu, Ted Xiao, Austin Stone, Jonathan Tompson, Anthony Brohan, Su Wang, Jaspiar Singh, Clayton Tan, Dee M, Jodilyn Peralta, Brian Ichter, Karol Hausman, Fei Xia
  
  RSS 2023
  
  [paper](https://arxiv.org/abs/2302.11550)
  
- **GenAug: Retargeting behaviors to unseen situations via Generative Augmentation**

  Zoey Chen, Sho Kiami, Abhishek Gupta, Vikash Kumar
  
  RSS 2023
  
  [paper](https://arxiv.org/abs/2302.06671) / [code](https://github.com/genaug/genaug)
  
- **Synthetic Experience Replay**

  Cong Lu, Philip J. Ball, Yee Whye Teh, Jack Parker-Holder
  
  NeurIPS 2023
  
  [paper](https://arxiv.org/abs/2303.06614) / [code](https://github.com/conglu1997/SynthER)
