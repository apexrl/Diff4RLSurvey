# Diffusion Models for Sequential Decision-Making: A Survey
This repository contains a collection of resources and papers on ***Diffusion Models*** for ***Sequential Decision-Making***.

:rocket: Please check out our survey paper [Diffusion Models for Reinforcement Learning: A Survey](https://arxiv.org/abs/2311.01223)

![image info](./compare.png)

## Table of Contents
- [Diffusion Models for Sequential Decision-Making: A Survey](#diffusion-models-for-sequential-decision-making-a-survey)
  - [Table of Contents](#table-of-contents)
  - [Papers](#papers)
    - [Offline Reinforcement Learning](#offline-reinforcement-learning)
    - [Online Reinforcement Learning](#online-reinforcement-learning)
    - [Imitation Learning](#imitation-learning)
    - [Trajectory Generation](#trajectory-generation)
    - [Data Augmentation](#data-augmentation)
  - [Citation](#citation)

## Papers

### Offline Reinforcement Learning

- **Planning with Diffusion for Flexible Behavior Synthesis**, ICML 2022. [[paper](https://arxiv.org/abs/2205.09991)] [[code](https://github.com/jannerm/diffuser)]

- **Diffusion Policies as an Expressive Policy Class for Offline Reinforcement Learning**, ICLR 2023. [[paper](https://arxiv.org/abs/2208.06193)] [[code](https://github.com/zhendong-wang/diffusion-policies-for-offline-rl)] 

- **Offline Reinforcement Learning via High-fidelity Generative Behavior Modeling**, ICLR 2023. [[paper](https://arxiv.org/abs/2209.14548)] [[code](https://github.com/chendrag/sfbc)]

- **Is Conditional Generative Modeling all you need for Decision-Making?**, ICLR 2023. [[paper](https://arxiv.org/abs/2211.15657)] [[code](https://github.com/xcvil/decision-diffuser/tree/main/code)]

- **AdaptDiffuser: Diffusion Models as Adaptive Self-evolving Planners**, ICML 2023. [[paper](https://arxiv.org/abs/2302.01877)] [[code](https://github.com/Liang-ZX/adaptdiffuser)]

- **Metadiffuser: Diffusion Model as Conditional Planner for Offline Meta-RL**, ICML 2023. [[paper](https://arxiv.org/abs/2305.19923)]

- **Hierarchical Diffusion for Offline Decision Making**, ICML 2023. [[paper](https://openreview.net/forum?id=55kLa7tH9o)] [[code](https://github.com/ewanlee/HDMI)]

- **Contrastive Energy Prediction for Exact Energy-guided Diffusion Sampling in Offline Reinforcement Learning**, ICML 2023. [[paper](https://arxiv.org/abs/2304.12824)] [[code](https://github.com/thu-ml/cep-energy-guided-diffusion)]

- **Language Control Diffusion: Efficiently Scaling through Space, Time, and Tasks**, arXiv 2023. [[paper](https://arxiv.org/abs/2210.15629v2)] [[code](https://github.com/ezhang7423/language-control-diffusion)]

- **IDQL: Implicit Q-Learning as an Actor-Critic Method with Diffusion Policies**, arXiv 2023. [[paper](https://arxiv.org/abs/2304.10573)] [[code](https://github.com/philippe-eecs/idql)]

- **Diffusion Model is an Effective Planner and Data Synthesizer for Multi-Task Reinforcement Learning**, NeurIPS 2023. [[paper](https://arxiv.org/abs/2305.18459)] [[code](https://github.com/tinnerhrhe/MTDiff)]

- **EDGI: Equivariant Diffusion for Planning with Embodied Agents**, NeurIPS 2023. [[paper](https://arxiv.org/abs/2303.12410)]

- **Extracting Reward Functions from Diffusion Models**, NeurIPS 2023. [[paper](https://arxiv.org/abs/2306.01804)]

- **Can Pre-Trained Text-to-Image Models Generate Visual Goals for Reinforcement Learning?**, NeurIPS 2023. [[paper](https://arxiv.org/abs/2307.07837)]

- **Reward-Directed Conditional Diffusion: Provable Distribution Estimation and Reward Improvement**, NeurIPS 2023. [[paper](https://arxiv.org/abs/2307.07055)] [[code](https://github.com/Kaffaljidhmah2/RCGDM/tree/main)]

- **Refining Diffusion Planner for Reliable Behavior Synthesis by Automatic Detection of Infeasible Plans**, NeurIPS 2023. [[paper](https://arxiv.org/abs/2310.19427)] [[code](https://github.com/leekwoon/rgg)]

- **SafeDiffuser: Safe Planning with Diffusion Probabilistic Models**, arXiv 2023. [[paper](https://arxiv.org/abs/2306.00148)]

- **Efficient Diffusion Policies for Offline Reinforcement Learning**, arXiv 2023. [[paper](https://arxiv.org/abs/2305.20081)] [[code](https://github.com/sail-sg/edp)]

- **MADiff: Offline Multi-agent Learning with Diffusion Models**, arXiv 2023. [[paper](https://arxiv.org/abs/2305.17330)] [[code](https://github.com/zbzhu99/madiff)]

- **Beyond Conservatism: Diffusion Policies in Offline Multi-agent Reinforcement Learning**, arXiv 2023. [[paper](https://arxiv.org/abs/2307.01472)]

- **Fighting Uncertainty with Gradients: Offline Reinforcement Learning via Diffusion Score Matching**, CoRL 2023. [[paper](https://arxiv.org/abs/2306.14079)] [[code](https://github.com/hjsuh94/score_po)]

- **Value function estimation using conditional diffusion models for control**, arXiv 2023. [[paper](https://arxiv.org/abs/2306.07290)]

- **Instructed Diffuser with Temporal Condition Guidance for Offline Reinforcement Learning**, arXiv 2023. [[paper](https://arxiv.org/abs/2306.04875)]

- **Diffusion Policies for Out-of-Distribution Generalization in Offline Reinforcement Learning**, arXiv 2023. [[paper](https://arxiv.org/abs/2307.04726)]

- **Diffusion Policies as Multi-Agent Reinforcement Learning Strategies**, ICANN 2023. [[paper](https://link.springer.com/chapter/10.1007/978-3-031-44213-1_30)]

- **DiffCPS: Diffusion Model based Constrained Policy Search for Offline Reinforcement Learning**, arXiv 2023. [[paper](https://arxiv.org/abs/2310.05333)] [[code](https://github.com/felix-thu/DiffCPS)]

- **Score Regularized Policy Optimization through Diffusion Behavior**, ICLR 2024. [[paper](https://arxiv.org/abs/2310.07297)] [[code](https://github.com/thu-ml/srpo)]

- **Adaptive Online Replanning with Diffusion Models**, arXiv 2023. [[paper](https://arxiv.org/abs/2310.09629)]

- **AlignDiff: Aligning Diverse Human Preferences via Behavior-Customisable Diffusion Model**, arXiv 2023. [[paper](https://arxiv.org/abs/2310.02054)] [[code](https://github.com/aligndiff/aligndiff.github.io)]

- **SkillDiffuser: Interpretable Hierarchical Planning via Skill Abstractions in Diffusion-Based Task Execution**, CVPR 2024. [[paper](https://arxiv.org/abs/2312.11598)] [[website](https://skilldiffuser.github.io/)]

- **Learning a Diffusion Model Policy from Rewards vis Q-score Matching**, arXiv 2023. [[paper](https://arxiv.org/abs/2312.11752)]

- **Simple Hierarchical Planning with Diffusion**, ICLR 2024. [[paper](https://arxiv.org/abs/2401.02644)]

- **Reasoning with Latent Diffusion in Offline Reinforcement Learning**, ICLR 2024. [[paper](https://arxiv.org/abs/2309.06599)]

- **Efficient Planning with Latent Diffusion**, ICLR 2024. [[paper](https://arxiv.org/abs/2310.00311)]

- **Contrastive Diffuser: Planning Towards High Return States via Contrastive Learning**, arXiv 2024. [[paper](https://arxiv.org/abs/2402.02772)]

- **DMBP: Diffusion model-based predictor for robust offline reinforcement learning against state observation perturbations**, ICLR 2024. [[paper](https://openreview.net/forum?id=ZULjcYLWKe)] [[code](https://github.com/zhyang2226/DMBP)]

- **Entropy-regularized Diffusion Policy with Q-Ensembles for Offline Reinforcement Learning**, arXiv 2024. [[paper](https://arxiv.org/abs/2402.04080)] [[code](https://github.com/ruoqizzz/entropy-offlineRL)]

- **Diffusion World Model**, arXiv 2024. [[paper](https://arxiv.org/abs/2402.03570)]

- **Diffusion World Models**, OpenReview 2024. [[paper](https://openreview.net/forum?id=bAXmvOLtjA)]

- **Policy-Guided Diffusion**, arXiv 2024. [[paper](https://arxiv.org/abs/2404.06356)] [[code](https://github.com/EmptyJackson/policy-guided-diffusion)]

### Online Reinforcement Learning

- **Policy Representation via Diffusion Probability Model for Reinforcement Learning**, arXiv 2023. [[paper](https://arxiv.org/abs/2305.13122)]

- **Boosting Continuous Control with Consistency Policy**, arXiv 2023. [[paper](https://arxiv.org/abs/2310.06343)]

- **Diffusion Reward: Learning Rewards via Conditional Video Diffusion**, arXiv 2023. [[paper](https://arxiv.org/abs/2312.14134)] [[website](https://diffusion-reward.github.io/)] [[code](https://github.com/TaoHuang13/diffusion_reward)]

- **ATraDiff: Accelerating Online Reinforcement Learning with Imaginary Trajectories**, OpenReview 2024. [[paper](https://openreview.net/forum?id=Ng7OYC3PT8)]

### Imitation Learning

- **Imitating Human Behaviour with Diffusion Models**, ICLR 2023. [[paper](https://arxiv.org/abs/2301.10677)] [[code](https://github.com/microsoft/imitating-human-behaviour-w-diffusion)]

- **Diffusion Policy: Visuomotor Policy Learning via Action Diffusion**, RSS 2023. [[paper](https://arxiv.org/abs/2303.04137)] [[code](https://github.com/real-stanford/diffusion_policy)]

- **Goal-Conditioned Imitation Learning using Score-based Diffusion Policies**, RSS 2023. [[paper](https://arxiv.org/abs/2304.02532)] [[code](https://github.com/intuitive-robots/beso)]

- **To the Noise and Back: Diffusion for Shared Autonomy**, RSS 2023. [[paper](https://arxiv.org/abs/2302.12244)] [[code](https://github.com/ripl/diffusion-for-shared-autonomy)]

- **DALL-E-Bot: Introducing Web-Scale Diffusion Models to Robotics**, RAL 2023. [[paper](https://arxiv.org/abs/2210.02438)]

- **Scaling Up and Distilling Down: Language-Guided Robot Skill Acquisition**, CoRL 2023. [[paper](https://arxiv.org/abs/2307.14535)] [[code](https://github.com/real-stanford/scalingup)]

- **XSkill: Cross Embodiment Skill Discovery**, CoRL 2023. [[paper](https://arxiv.org/abs/2307.09955)]

- **ChainedDiffuser: Unifying Trajectory Diffusion and Keypose Prediction for Robotic Manipulation**, CoRL 2023. [[paper](https://openreview.net/forum?id=W0zgY2mBTA8)] [[code](https://github.com/zhouxian/chained-diffuser)]

- **PlayFusion: Skill Acquisition via Diffusion from Language-Annotated Play**, CoRL 2023. [[paper](https://openreview.net/forum?id=afF8RGcBBP)]

- **Generative Skill Chaining: Long-Horizon Skill Planning with Diffusion Models**, CoRL 2023. [[paper](https://openreview.net/forum?id=HtJE9ly5dT)] [[code](https://github.com/generative-skill-chaining/gsc-code)]

- **Multimodal Diffusion Transformer for Learning from Play**, CoRL 2023. [[paper](https://openreview.net/forum?id=nvtxqMGpn1)]

- **GNFactor: Multi-Task Real Robot Learning with Generalizable Neural Feature Fields**, CoRL 2023. [[paper](https://arxiv.org/abs/2308.16891)] [[code](https://github.com/YanjieZe/GNFactor)]

- **Crossway Diffusion: Improving Diffusion-based Visuomotor Policy via Self-supervised Learning**, arXiv 2023. [[paper](https://arxiv.org/abs/2307.01849)] [[code](https://github.com/lostxine/crossway_diffusion)]

- **Diffusion Co-Policy for Synergistic Human-Robot Collaborative Tasks**, arXiv 2023. [[paper](https://arxiv.org/abs/2305.12171)] [[code](https://github.com/eleyng/diffusion_copolicy)]

- **Compositional Foundation Models for Hierarchical Planning**, NeurIPS 2023. [[paper](https://arxiv.org/abs/2309.08587)] [[code](https://github.com/anuragajay/hip/tree/main)]

- **Generating Behaviorally Diverse Policies with Latent Diffusion Models**, NeurIPS 2023. [[paper](https://arxiv.org/abs/2305.18738)]

- **NoMaD: Goal Masking Diffusion Policies for Navigation and Exploration**, arXiv 2023. [[paper](https://arxiv.org/abs/2310.07896)] [[code](https://github.com/robodhruv/visualnav-transformer)]

- **Zero-Shot Robotic Manipulation with Pretrained Image-Editing Diffusion Models**, arXiv 2023. [[paper](https://arxiv.org/abs/2310.10639)]

- **Imitation Learning from Purified Demonstrations**, arXiv 2023. [[paper](https://arxiv.org/abs/2310.07143)]

- **Planning as In-Painting: A Diffusion-Based Embodied Task Planning Framework for Environments under Uncertainty**, arXiv 2023. [[paper](https://arxiv.org/abs/2312.01097)]

- **Diffusion Meets DAgger: Supercharging Eye-in-hand Imitation Learning**, arXiv 2024. [[paper](https://arxiv.org/abs/2402.17768)]

- **3D Diffusion Policy**, arXiv 2024. [[paper](https://arxiv.org/abs/2403.03954)] [[website](https://3d-diffusion-policy.github.io)] [[code](https://github.com/YanjieZe/3D-Diffusion-Policy)]

- **Large-Scale Actionless Video Pre-Training via Discrete Diffusion for Efficient Policy Learning**, arxiv 2024. [[paper](https://arxiv.org/abs/2402.14407)] [[website](https://video-diff.github.io/)]

- **SculptDiff: Learning Robotic Clay Sculpting from Humans with Goal Conditioned Diffusion Policy**, arXiv 2024. [[paper](https://arxiv.org/abs/2403.10401)] [[website](https://sites.google.com/andrew.cmu.edu/imitation-sculpting/home)] [[code](https://github.com/alison-bartsch/SculptDiff)]

- **Subgoal Diffuser: Coarse-to-fine Subgoal Generation to Guide Model Predictive Control for Robot Manipulation**, ICRA 2024. [[paper](https://arxiv.org/abs/2403.13085)] [[website](https://sites.google.com/view/subgoal-diffuser-mpc)]

- **Hierarchical Diffusion Policy for Kinematics-Aware Multi-Task Robotic Manipulation**, CVPR 2024, [[paper](https://arxiv.org/abs/2403.03890)] [[code](https://github.com/dyson-ai/hdp)] [[website](https://yusufma03.github.io/projects/hdp/)]

- **Diffusion-EDFs: Bi-equivariant Denoising Generative Modeling on SE(3) for Visual Robotic Manipulation**, CVPR 2024, [[paper](https://arxiv.org/abs/2309.02685)] [[code](https://github.com/tomato1mule/diffusion_edf)] [[website](https://sites.google.com/view/diffusion-edfs)]

### Trajectory Generation

- **MotionDiffuse: Text-Driven Human Motion Generation with Diffusion Model**, arXiv 2022. [[paper](https://arxiv.org/abs/2208.15001)] [[code](https://github.com/mingyuan-zhang/MotionDiffuse)]
  
- **Human Motion Diffusion Model**, ICLR 2023. [[paper](https://arxiv.org/abs/2209.14916)] [[code](https://github.com/guytevet/motion-diffusion-model)]
  
- **Executing your Commands via Motion Diffusion in Latent Space**, CVPR 2023. [[paper](https://arxiv.org/abs/2212.04048)] [[code](https://github.com/chenfengye/motion-latent-diffusion)]
  
- **MoFusion: A Framework for Denoising-Diffusion-based Motion Synthesis**, CVPR 2023. [[paper](https://arxiv.org/abs/2212.04495)] [[code](https://github.com/OFA-Sys/MoFusion)]
  
- **ReMoDiffuse: Retrieval-Augmented Motion Diffusion Model**, ICCV 2023. [[paper](https://arxiv.org/abs/2304.01116)] [[code](https://github.com/mingyuan-zhang/ReMoDiffuse)]
  
- **MotionDiffuser: Controllable Multi-Agent Motion Prediction using Diffusion**, CVPR 2023. [[paper](https://arxiv.org/abs/2306.03083)]

- **Learning Universal Policies via Text-Guided Video Generation**, NeurIPS 2023. [[paper](https://arxiv.org/abs/2310.08576)]

- **EquiDiff: A Conditional Equivariant Diffusion Model For Trajectory Prediction**, arXiv 2023. [[paper](https://arxiv.org/abs/2308.06564)]

- **Motion Planning Diffusion: Learning and Planning of Robot Motions with Diffusion Models**, IROS 2023. [[paper](https://arxiv.org/abs/2308.01557)] [[code](https://github.com/jacarvalho/mpd-public)]

- **EDMP: Ensemble-of-costs-guided Diffusion for Motion Planning**, arXiv 2023. [[paper](https://arxiv.org/abs/2309.11414)] [[code](https://github.com/vishal-2000/EDMP)]

- **Sampling Constrained Trajectories Using Composable Diffusion Models**, IROS 2023. [[paper](https://openreview.net/forum?id=UAylEpIMNE)]

- **DiMSam: Diffusion Models as Samplers for Task and Motion Planning under Partial Observability**, arXiv 2023. [[paper](https://arxiv.org/abs/2306.13196)]

- **Conditioned Score-Based Models for Learning Collision-Free Trajectory Generation**, NeurIPSW 2022. [[paper](https://openreview.net/forum?id=4Vqu4N1jjrx)]

- **Video Language Planning**, arXiv 2023. [[paper](https://arxiv.org/abs/2310.10625)] [[code](https://github.com/video-language-planning/vlp_code)]
  
- **Learning to Act from Actionless Video through Dense Correspondences**, arXiv 2023. [[paper](https://arxiv.org/abs/2310.08576)] [[code](https://github.com/flow-diffusion/AVDC)]
  
- **Learning Interactive Real-World Simulators**, arXiv 2023. [[paper](https://arxiv.org/abs/2310.06114)]

- **DNAct: Diffusion Guided Multi-Task 3D Policy Learning**, arXiv 2024. [[paper](https://arxiv.org/abs/2403.04115)] [[website](https://dnact.github.io/)]

- **Single Motion Diffusion**, ICLR 2024, [[paper](https://arxiv.org/abs/2302.05905)] [[code](https://github.com/SinMDM/SinMDM)] [[website](https://sinmdm.github.io/SinMDM-page/)]

- **READ: Retrieval-Enhanced Asymmetric Diffusion for Motion Planning**, CVPR 2024, [[paper](https://openaccess.thecvf.com/content/CVPR2024/html/Oba_READ_Retrieval-Enhanced_Asymmetric_Diffusion_for_Motion_Planning_CVPR_2024_paper.html)] [[code](https://github.com/Obat2343/READ)]

### Data Augmentation

- **Scaling Robot Learning with Semantically Imagined Experience**, RSS 2023. [[paper](https://arxiv.org/abs/2302.11550)]

- **GenAug: Retargeting behaviors to unseen situations via Generative Augmentation**, RSS 2023. [[paper](https://arxiv.org/abs/2302.06671)] [[code](https://github.com/genaug/genaug)]

- **Synthetic Experience Replay**, NeurIPS 2023. [[paper](https://arxiv.org/abs/2303.06614)] [[code](https://github.com/conglu1997/SynthER)]

- **World Models via Policy-Guided Trajectory Diffusion**, arXiv 2023. [[paper](https://arxiv.org/abs/2312.08533)]

- **Distilling Conditional Diffusion Models for Offline Reinforcement Learning through Trajectory Stitching**, arXiv 2024. [[paper](https://arxiv.org/abs/2402.00807)]

- **DiffStitch: Boosting Offline Reinforcement Learning with Diffusion-based Trajectory Stitching**, arXiv 2024. [[paper](https://arxiv.org/abs/2402.02439)]

- **Flow to Better: Offline Preference-based Reinforcement Learning via Preferred Trajectory Generation**, ICLR 2024. [[paper](https://openreview.net/forum?id=EG68RSznLT)] [[code](https://github.com/Zzl35/flow-to-better)]

## Citation
```
@article{zhu2023diffusion,
  title={Diffusion Models for Reinforcement Learning: A Survey},
  author={Zhu, Zhengbang and Zhao, Hanye and He, Haoran and Zhong, Yichao and Zhang, Shenyu and Yu, Yong and Zhang, Weinan},
  journal={arXiv preprint arXiv:2311.01223},
  year={2023}
}
```
