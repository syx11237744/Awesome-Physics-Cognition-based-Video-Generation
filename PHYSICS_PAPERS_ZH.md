# 物理相关论文导读（中文）

本文档从 `README.md` 的论文列表中，筛选标题明确涉及 physics/physical/Phys、力、重力、牛顿规律、因果、仿真、动力学、一致性、真实感、物理常识等关键词的条目，并按原仓库分类整理。每条简介基于论文题名、仓库分类与公开条目元信息撰写，便于快速了解其研究重点。

> 共整理 168 篇/项论文条目；Workshop 条目未计入本文档。

## 目录

- [Surveys](#surveys)
- [Basic Schematic Perception for Generation](#basic-schematic-perception-for-generation)
- [Passive Cognition of Physical Knowledge for Generation](#passive-cognition-of-physical-knowledge-for-generation)
- [Active Cognition for World Simulation](#active-cognition-for-world-simulation)
- [Datasets, Benchmarks and Metrics](#datasets-benchmarks-and-metrics)
- [VLMs, LLMs, MLLMs on Physical Understanding](#vlms-llms-mllms-on-physical-understanding)
- [Benchmarks](#benchmarks)

## Surveys

### 1. [Simulating the Visual World with Artificial Intelligence: A Roadmap](https://arxiv.org/abs/2511.08585)

- **时间/会议**：Nov., 2025
- **README 位置**：L49
- **简介**：综述类工作，适合作为该方向的入口。

### 2. [Aligning Perception, Reasoning, Modeling and Interaction: A Survey on Physical AI](https://arxiv.org/abs/2510.04978)

- **时间/会议**：Oct., 2025
- **README 位置**：L50
- **简介**：综述类工作，适合作为该方向的入口，关注因果、常识和直觉物理推理。

### 3. [A Survey of Interactive Generative Video](https://arxiv.org/abs/2504.21853)

- **时间/会议**：Apr., 2025
- **README 位置**：L51
- **简介**：综述类工作，适合作为该方向的入口。

### 4. [Digital Gene: Learning about the Physical World through Analytic Concepts](https://arxiv.org/abs/2504.04170)

- **时间/会议**：Apr., 2025
- **README 位置**：L52
- **简介**：综述类工作，适合作为该方向的入口。

### 5. [Simulating the Real World: A Unified Survey of Multimodal Generative Models](https://arxiv.org/abs/2503.04641)

- **时间/会议**：Mar., 2025
- **README 位置**：L53
- **简介**：综述类工作，适合作为该方向的入口，强调世界模型、仿真或真实世界动态。

### 6. [Grounding Creativity in Physics: A Brief Survey of Physical Priors in AIGC](https://arxiv.org/abs/2502.07007)

- **时间/会议**：Feb., 2025
- **README 位置**：L54
- **简介**：综述类工作，适合作为该方向的入口。

### 7. [Generative Physical AI in Vision: A Survey](https://arxiv.org/abs/2501.10928)

- **时间/会议**：Jan., 2025
- **README 位置**：L55
- **简介**：综述类工作，适合作为该方向的入口。

### 8. [Physics-Informed Computer Vision: A Review and Perspectives](https://dl.acm.org/doi/full/10.1145/3689037)

- **时间/会议**：ACM Computing Surveys, 2024
- **README 位置**：L56
- **简介**：综述类工作，适合作为该方向的入口。

## Basic Schematic Perception for Generation

### 1. [ReVision: High-Quality, Low-Cost Video Generation with Explicit 3D Physics Modeling for Complex Motion and Interaction](https://arxiv.org/abs/2504.21855)

- **时间/会议**：Apr., 2025
- **README 位置**：L72
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；强调三维/四维场景、几何一致性或动态重建；突出力、重力、运动轨迹、牛顿动力学或物理规律。

### 2. [Towards Physical Understanding in Video Generation: A 3D Point Regularization Approach](https://arxiv.org/abs/2502.03639)

- **时间/会议**：Feb, 2025
- **README 位置**：L74
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；强调三维/四维场景、几何一致性或动态重建；关注因果、常识和直觉物理推理。

### 3. [Generative Photography: Scene-Consistent Camera Control for Realistic Text-to-Image Synthesis](https://arxiv.org/abs/2412.02168)

- **时间/会议**：CVPR, 2025
- **README 位置**：L78
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，目标是提升物理一致性、连贯性和真实感。

### 4. [InterDyn: Controllable Interactive Dynamics with Video Diffusion Models](https://arxiv.org/abs/2412.11785)

- **时间/会议**：Dec., 2024,CVPR 25
- **README 位置**：L85
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；突出力、重力、运动轨迹、牛顿动力学或物理规律。

### 5. [Motion Dreamer: Realizing Physically Coherent Video Generation through Scene-Aware Motion Reasoning](https://arxiv.org/abs/2412.00547)

- **时间/会议**：Nov., 2024.
- **README 位置**：L88
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；突出力、重力、运动轨迹、牛顿动力学或物理规律；关注因果、常识和直觉物理推理。

### 6. [AnimateAnything: Consistent and Controllable Animation for Video Generation](https://arxiv.org/abs/2411.10836)

- **时间/会议**：Nov., 2024
- **README 位置**：L89
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；目标是提升物理一致性、连贯性和真实感。

### 7. [InTraGen: Trajectory-controlled Video Generation for Object Interactions](https://arxiv.org/abs/2411.16804)

- **时间/会议**：Nov., 2024
- **README 位置**：L90
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；突出力、重力、运动轨迹、牛顿动力学或物理规律。

### 8. [LumiSculpt: A Consistency Lighting Control Network for Video Generation](https://arxiv.org/abs/2410.22979)

- **时间/会议**：Oct., 2024
- **README 位置**：L92
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；目标是提升物理一致性、连贯性和真实感。

### 9. [UniAnimate: Taming Unified Video Diffusion Models for Consistent Human Image Animation](https://arxiv.org/abs/2406.01188)

- **时间/会议**：Jun., 2024
- **README 位置**：L94
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；目标是提升物理一致性、连贯性和真实感。

### 10. [Image Conductor: Precision Control for Interactive Video Synthesis](https://arxiv.org/abs/2406.15339)

- **时间/会议**：Jun., 2024
- **README 位置**：L95
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束。

### 11. [Generative Image Dynamics](https://openaccess.thecvf.com/content/CVPR2024/html/Li_Generative_Image_Dynamics_CVPR_2024_paper.html)

- **时间/会议**：CVPR, 2024, Best Paper Award
- **README 位置**：L100
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，突出力、重力、运动轨迹、牛顿动力学或物理规律。

### 12. [Animate Anyone: Consistent and Controllable Image-to-Video Synthesis for Character Animation](https://arxiv.org/abs/2311.17117)

- **时间/会议**：CVPR, 2024
- **README 位置**：L106
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向图像到视频/单图驱动生成；目标是提升物理一致性、连贯性和真实感。

### 13. [Motion-I2V: Consistent and Controllable Image-to-Video Generation with Explicit Motion Modeling](https://arxiv.org/abs/2401.15977)

- **时间/会议**：SIGGRAPH, 2024
- **README 位置**：L108
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；面向图像到视频/单图驱动生成；突出力、重力、运动轨迹、牛顿动力学或物理规律；目标是提升物理一致性、连贯性和真实感。

## Passive Cognition of Physical Knowledge for Generation

### 1. [TelePhysics: Physics-Grounded Multi-Object Scene Generation from a Single Image with Real-Time Interaction](https://arxiv.org/abs/2605.20290)

- **时间/会议**：May, 2026
- **README 位置**：L119
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向图像到视频/单图驱动生成。

### 2. [PhysVid: Physics Aware Local Conditioning for Generative Video Models](https://arxiv.org/abs/2603.26285)

- **时间/会议**：CVPR 2026
- **README 位置**：L120
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束。

### 3. [MotionPhysics: Learnable Motion Distillation for Text-Guided Simulation](https://arxiv.org/abs/2601.00504)

- **时间/会议**：AAAI, 2026
- **README 位置**：L121
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调世界模型、仿真或真实世界动态；突出力、重力、运动轨迹、牛顿动力学或物理规律。

### 4. [Phys4D: Fine-Grained Physics-Consistent 4D Modeling from Video Diffusion](https://arxiv.org/abs/2603.03485)

- **时间/会议**：Mar., 2026
- **README 位置**：L122
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；强调三维/四维场景、几何一致性或动态重建；目标是提升物理一致性、连贯性和真实感。

### 5. [PhysAlign: Physics-Coherent Image-to-Video Generation through Feature and 3D Representation Alignment](https://arxiv.org/abs/2603.13770)

- **时间/会议**：Mar., 2026
- **README 位置**：L123
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；面向图像到视频/单图驱动生成；强调三维/四维场景、几何一致性或动态重建。

### 6. [Physical Simulator In-the-Loop Video Generation](https://arxiv.org/abs/2603.06408)

- **时间/会议**：CVPR, 2026
- **README 位置**：L124
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；强调世界模型、仿真或真实世界动态。

### 7. [PhysVideo: Physically Plausible Video Generation with Cross-View Geometry Guidance](https://arxiv.org/abs/2603.18639)

- **时间/会议**：Mar., 2026
- **README 位置**：L125
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；强调三维/四维场景、几何一致性或动态重建；目标是提升物理一致性、连贯性和真实感。

### 8. [Chain of Event-Centric Causal Thought for Physically Plausible Video Generation](https://arxiv.org/abs/2603.09094)

- **时间/会议**：CVPR, 2026
- **README 位置**：L126
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；关注因果、常识和直觉物理推理；目标是提升物理一致性、连贯性和真实感。

### 9. [RealWonder: Real-Time Physical Action-Conditioned Video Generation](https://arxiv.org/abs/2603.05449)

- **时间/会议**：Mar., 2026
- **README 位置**：L127
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型。

### 10. [Goal Force: Teaching Video Models To Accomplish Physics-Conditioned Goals](https://arxiv.org/abs/2601.05848)

- **时间/会议**：CVPR, 2026
- **README 位置**：L128
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，突出力、重力、运动轨迹、牛顿动力学或物理规律。

### 11. [PI-Light: Physics-Inspired Diffusion for Full-Image Relighting](https://arxiv.org/abs/2601.22135)

- **时间/会议**：ICLR 2026
- **README 位置**：L129
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束。

### 12. [VDAWorld: World Modelling via VLM-Directed Abstraction and Simulation](https://arxiv.org/abs/2512.11061)

- **时间/会议**：Dec., 2025
- **README 位置**：L132
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调世界模型、仿真或真实世界动态；结合视觉语言模型/大语言模型进行推理、规划或评估。

### 13. [Bootstrapping Physics-Grounded Video Generation through VLM-Guided Iterative Self-Refinement](https://arxiv.org/abs/2511.20280)

- **时间/会议**：ICCV 2025 Physics-IQ Challenge Third Place
- **README 位置**：L133
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；结合视觉语言模型/大语言模型进行推理、规划或评估。

### 14. [ProPhy: Progressive Physical Alignment for Dynamic World Simulation](https://arxiv.org/pdf/2512.05564)

- **时间/会议**：Dec., 2025
- **README 位置**：L134
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调世界模型、仿真或真实世界动态。

### 15. [Planning with Sketch-Guided Verification for Physics-Aware Video Generation](http://arxiv.org/abs/2511.17450)

- **时间/会议**：Nov., 2025
- **README 位置**：L135
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型。

### 16. [CP4D: Compositional physics-aware 4D scene generation](https://openreview.net/forum?id=5qd7V5TNGV)

- **时间/会议**：Oct., 2025
- **README 位置**：L137
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调三维/四维场景、几何一致性或动态重建。

### 17. [3DPhysVideo: 3D Scene Reconstruction and Physical Animation Leveraging a Video Generation Model via Consistency-Guided Flow SDE](https://openreview.net/forum?id=8TgzLrWgrk)

- **时间/会议**：Oct., 2025
- **README 位置**：L138
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；强调三维/四维场景、几何一致性或动态重建；目标是提升物理一致性、连贯性和真实感。

### 18. [PhyMAGIC: Physical Motion-Aware Generative Inference with Confidence-guided LLM](https://openreview.net/attachment?id=nruZar3Aaz&name=pdf)

- **时间/会议**：Oct., 2025
- **README 位置**：L139
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，结合视觉语言模型/大语言模型进行推理、规划或评估；突出力、重力、运动轨迹、牛顿动力学或物理规律。

### 19. [DiffuPhyGS: Text-to-Video Generation with 3D Gaussians and Learnable Physical Properties via Diffusion Priors](https://openreview.net/forum?id=mq43BAAos0)

- **时间/会议**：Oct., 2025
- **README 位置**：L140
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；强调三维/四维场景、几何一致性或动态重建。

### 20. [Fracture-GS: Dynamic Fracture Simulation with Physics-Integrated Gaussian Splatting](https://openreview.net/forum?id=zcAwK50ft0)

- **时间/会议**：Oct., 2025
- **README 位置**：L141
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调三维/四维场景、几何一致性或动态重建；强调世界模型、仿真或真实世界动态；涉及材料、流体、毛发、断裂或弹性等细粒度物理现象。

### 21. [PhyScensis: Physics-Augmented LLM Agents for Complex Physical Scene Generation](https://openreview.net/forum?id=aCVfhY4Qen)

- **时间/会议**：Oct., 2025
- **README 位置**：L142
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，结合视觉语言模型/大语言模型进行推理、规划或评估。

### 22. [Learning to Generate Object Interactions with Physics-Guided Video Diffusion](https://arxiv.org/abs/2510.02284)

- **时间/会议**：Oct., 2025
- **README 位置**：L143
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型。

### 23. [CONTROLHAIR: Physically-based Video Diffusion for Controllable Dynamic Hair Rendering](https://www.arxiv.org/abs/2509.21541)

- **时间/会议**：Sep., 2025
- **README 位置**：L144
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；涉及材料、流体、毛发、断裂或弹性等细粒度物理现象。

### 24. [NewtonGen: Physics-Consistent and Controllable Text-to-Video Generation via Neural Newtonian Dynamics](https://arxiv.org/abs/2509.21309)

- **时间/会议**：Sep., 2025
- **README 位置**：L145
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；突出力、重力、运动轨迹、牛顿动力学或物理规律；目标是提升物理一致性、连贯性和真实感。

### 25. [PIRF: Physics-Informed Reward Fine-Tuning for Diffusion Models](https://arxiv.org/abs/2509.20570)

- **时间/会议**：Sep., 2025
- **README 位置**：L146
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束。

### 26. [PhysCtrl: Generative Physics for Controllable and Physics-Grounded Video Generation](https://cwchenwang.github.io/physctrl/static/pdfs/paper.pdf)

- **时间/会议**：NeurIPS, 2025
- **README 位置**：L147
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型。

### 27. [PhysGM: Large Physical Gaussian Model for Feed-Forward 4D Synthesis](https://arxiv.org/abs/2508.13911)

- **时间/会议**：Aug., 2025
- **README 位置**：L148
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调三维/四维场景、几何一致性或动态重建。

### 28. [Physics-Grounded Motion Forecasting via Equation Discovery for Trajectory-Guided Image-to-Video Generation](https://arxiv.org/abs/2507.06830)

- **时间/会议**：Jul., 2025
- **README 位置**：L149
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；面向图像到视频/单图驱动生成；突出力、重力、运动轨迹、牛顿动力学或物理规律。

### 29. [Dreamland: Controllable World Creation with Simulator and Generative Models](https://arxiv.org/abs/2506.08006)

- **时间/会议**：Jun., 2025
- **README 位置**：L150
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调世界模型、仿真或真实世界动态。

### 30. [Vid2Sim: Generalizable, Video-based Reconstruction of Appearance, Geometry and Physics for Mesh-free Simulation](https://arxiv.org/abs/2506.06440)

- **时间/会议**：Jun., 2025, CVPR
- **README 位置**：L151
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调三维/四维场景、几何一致性或动态重建；强调世界模型、仿真或真实世界动态。

### 31. [Physics-Guided Motion Loss for Video Generation Model](https://arxiv.org/abs/2506.02244)

- **时间/会议**：Jun., 2025
- **README 位置**：L152
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；突出力、重力、运动轨迹、牛顿动力学或物理规律。

### 32. [Think Before You Diffuse: LLMs-Guided Physics-Aware Video Generation](https://arxiv.org/abs/2505.21653)

- **时间/会议**：May, 2025
- **README 位置**：L153
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；结合视觉语言模型/大语言模型进行推理、规划或评估。

### 33. [Force Prompting: Video Generation Models Can Learn and Generalize Physics-based Control Signals](https://arxiv.org/abs/2505.19386)

- **时间/会议**：May, 2025
- **README 位置**：L154
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；突出力、重力、运动轨迹、牛顿动力学或物理规律。

### 34. [UniPhy: Learning a Unified Constitutive Model for Inverse Physics Simulation](https://arxiv.org/abs/2505.16971)

- **时间/会议**：May, 2025, CVPR
- **README 位置**：L157
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调世界模型、仿真或真实世界动态。

### 35. [FinePhys: Fine-grained Human Action Generation by Explicitly Incorporating Physical Laws for Effective Skeletal Guidance](https://arxiv.org/abs/2505.13437)

- **时间/会议**：May, 2025, CVPR
- **README 位置**：L158
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，突出力、重力、运动轨迹、牛顿动力学或物理规律。

### 36. [Generating Physically Stable and Buildable LEGO Designs from Text](https://www.arxiv.org/abs/2505.05469)

- **时间/会议**：May, 2025
- **README 位置**：L159
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束。

### 37. [Reasoning Physical Video Generation with Diffusion Timestep Tokens via Reinforcement Learning](https://arxiv.org/abs/2504.15932)

- **时间/会议**：Apr., 2025
- **README 位置**：L161
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；突出力、重力、运动轨迹、牛顿动力学或物理规律；关注因果、常识和直觉物理推理。

### 38. [VLIPP: Towards Physically Plausible Video Generation with Vision and Language Informed Physical Prior](https://arxiv.org/abs/2503.23368)

- **时间/会议**：Mar., 2025
- **README 位置**：L162
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；目标是提升物理一致性、连贯性和真实感。

### 39. [RainyGS: Efficient Rain Synthesis with Physically-Based Gaussian Splatting](https://arxiv.org/abs/2503.21442)

- **时间/会议**：Mar., 2025; CVPR, 2025
- **README 位置**：L164
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调三维/四维场景、几何一致性或动态重建。

### 40. [PhysGen3D: Crafting a Miniature Interactive World from a Single Image](https://arxiv.org/abs/2503.20746)

- **时间/会议**：Mar., 2025; CVPR, 2025
- **README 位置**：L165
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向图像到视频/单图驱动生成；强调三维/四维场景、几何一致性或动态重建。

### 41. [AccidentSim: Generating Physically Realistic Vehicle Collision Videos from Real-World Accident Reports](https://arxiv.org/abs/2503.20654)

- **时间/会议**：Mar., 2025
- **README 位置**：L166
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，目标是提升物理一致性、连贯性和真实感。

### 42. [Synthetic Video Enhances Physical Fidelity in Video Synthesis](https://www.arxiv.org/abs/2503.20822)

- **时间/会议**：Mar., 2025
- **README 位置**：L167
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束。

### 43. [PhysTwin: Physics-Informed Reconstruction and Simulation of Deformable Objects from Videos](https://arxiv.org/abs/2503.17973)

- **时间/会议**：Mar., 2025
- **README 位置**：L168
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调三维/四维场景、几何一致性或动态重建；强调世界模型、仿真或真实世界动态。

### 44. [PhysAnimator: Physics-Guided Generative Cartoon Animation](https://arxiv.org/abs/2501.16550)

- **时间/会议**：Jan., 2025
- **README 位置**：L170
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束。

### 45. [OmniPhysGS: 3D Constitutive Gaussians for General Physics-Based Dynamics Generation](https://openreview.net/forum?id=9HZtP6I5lv)

- **时间/会议**：ICLR, 2025
- **README 位置**：L171
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调三维/四维场景、几何一致性或动态重建；突出力、重力、运动轨迹、牛顿动力学或物理规律。

### 46. [AutoVFX: Physically Realistic Video Editing from Natural Language Instructions](https://arxiv.org/abs/2411.02394)

- **时间/会议**：3DV, 2025
- **README 位置**：L172
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，目标是提升物理一致性、连贯性和真实感。

### 47. [Unleashing the potential of multi-modal foundation models and video diffusion for 4d dynamic physical scene simulation](https://arxiv.org/abs/2411.14423)

- **时间/会议**：CVPR, 2025
- **README 位置**：L174
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；强调三维/四维场景、几何一致性或动态重建；强调世界模型、仿真或真实世界动态。

### 48. [FluidNexus: 3D Fluid Reconstruction and Prediction from a Single Video](https://arxiv.org/abs/2503.04720)

- **时间/会议**：CVPR, 2025
- **README 位置**：L175
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调三维/四维场景、几何一致性或动态重建；涉及材料、流体、毛发、断裂或弹性等细粒度物理现象。

### 49. [DreamPhysics: Learning Physical Properties of Dynamic 3D Gaussians with Video Diffusion Priors](https://arxiv.org/abs/2406.01476)

- **时间/会议**：AAAI, 2025
- **README 位置**：L177
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；强调三维/四维场景、几何一致性或动态重建。

### 50. [GauSim: Registering Elastic Objects into Digital World by Gaussian Simulator](https://arxiv.org/abs/2412.17804)

- **时间/会议**：Dec., 2024
- **README 位置**：L178
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调三维/四维场景、几何一致性或动态重建；强调世界模型、仿真或真实世界动态；涉及材料、流体、毛发、断裂或弹性等细粒度物理现象。

### 51. [GaussianProperty: Integrating Physical Properties to 3D Gaussians with LMMs](https://arxiv.org/abs/2412.11258)

- **时间/会议**：Dec., 2024
- **README 位置**：L179
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调三维/四维场景、几何一致性或动态重建。

### 52. [Phys4DGen: A Physics-Driven Framework for Controllable and Efficient 4D Content Generation from a Single Image](https://arxiv.org/abs/2411.16800)

- **时间/会议**：Nov., 2024
- **README 位置**：L180
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向图像到视频/单图驱动生成；强调三维/四维场景、几何一致性或动态重建。

### 53. [Teaching Video Diffusion Model with Latent Physical Phenomenon Knowledge](https://arxiv.org/abs/2411.11343)

- **时间/会议**：Nov., 2024
- **README 位置**：L181
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型。

### 54. [Llmphy: Complex physical reasoning using large language models and world models](https://arxiv.org/abs/2411.08027)

- **时间/会议**：Nov., 2024
- **README 位置**：L182
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调世界模型、仿真或真实世界动态；结合视觉语言模型/大语言模型进行推理、规划或评估；关注因果、常识和直觉物理推理。

### 55. [Automated 3D Physical Simulation of Open-world Scene with Gaussian Splatting](https://arxiv.org/abs/2411.12789)

- **时间/会议**：Nov., 2024
- **README 位置**：L183
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调三维/四维场景、几何一致性或动态重建；强调世界模型、仿真或真实世界动态。

### 56. [Enhancing Sketch Animation: Text-to-Video Diffusion Models with Temporal Consistency and Rigidity Constraints](https://arxiv.org/abs/2411.19381)

- **时间/会议**：Nov., 2024
- **README 位置**：L184
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；目标是提升物理一致性、连贯性和真实感。

### 57. [PhysMotion: Physics-Grounded Dynamics From a Single Image](https://arxiv.org/abs/2411.17189)

- **时间/会议**：Nov., 2024
- **README 位置**：L185
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向图像到视频/单图驱动生成；突出力、重力、运动轨迹、牛顿动力学或物理规律。

### 58. [Trans4D: Realistic Geometry-Aware Transition for Compositional Text-to-4D Synthesis](https://arxiv.org/abs/2410.07155)

- **时间/会议**：Oct., 2024
- **README 位置**：L186
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调三维/四维场景、几何一致性或动态重建；目标是提升物理一致性、连贯性和真实感。

### 59. [Phy124: Fast Physics-Driven 4D Content Generation from a Single Image](https://arxiv.org/abs/2409.07179)

- **时间/会议**：Sep., 2024
- **README 位置**：L187
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向图像到视频/单图驱动生成；强调三维/四维场景、几何一致性或动态重建。

### 60. [Physics3D: Learning Physical Properties of 3D Gaussians via Video Diffusion](https://arxiv.org/abs/2406.04338)

- **时间/会议**：Jun., 2024
- **README 位置**：L189
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；强调三维/四维场景、几何一致性或动态重建。

### 61. [Sync4D: Video Guided Controllable Dynamics for Physics-Based 4D Generation](https://arxiv.org/abs/2405.16849)

- **时间/会议**：May., 2024
- **README 位置**：L190
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调三维/四维场景、几何一致性或动态重建；突出力、重力、运动轨迹、牛顿动力学或物理规律。

### 62. [ElastoGen: 4D Generative Elastodynamics](https://arxiv.org/abs/2405.15056)

- **时间/会议**：May, 2024
- **README 位置**：L191
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调三维/四维场景、几何一致性或动态重建；突出力、重力、运动轨迹、牛顿动力学或物理规律。

### 63. [MotionCraft: Physics-based Zero-Shot Video Generation](https://arxiv.org/abs/2405.13557)

- **时间/会议**：Nips, 2024
- **README 位置**：L192
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；突出力、重力、运动轨迹、牛顿动力学或物理规律。

### 64. [PhysGen: Rigid-Body Physics-Grounded Image-to-Video Generation](https://arxiv.org/abs/2409.18964)

- **时间/会议**：ECCV, 2024
- **README 位置**：L193
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；面向图像到视频/单图驱动生成。

### 65. [PhysDreamer: Physics-Based Interaction with 3D Objects via Video Generation](https://link.springer.com/chapter/10.1007/978-3-031-72627-9_22)

- **时间/会议**：ECCV, 2024 Oral
- **README 位置**：L194
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；强调三维/四维场景、几何一致性或动态重建。

### 66. [Video2Game: Real-time, Interactive, Realistic and Browser-Compatible Environment from a Single Video](https://arxiv.org/abs/2404.09833)

- **时间/会议**：CVPR, 2024
- **README 位置**：L195
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，目标是提升物理一致性、连贯性和真实感。

### 67. [PIE-NeRF: Physics-based Interactive Elastodynamics with NeRF](https://openaccess.thecvf.com/content/CVPR2024/html/Feng_PIE-NeRF_Physics-based_Interactive_Elastodynamics_with_NeRF_CVPR_2024_paper.html)

- **时间/会议**：CVPR, 2024
- **README 位置**：L196
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，突出力、重力、运动轨迹、牛顿动力学或物理规律。

### 68. [VR-GS: A Physical Dynamics-Aware Interactive Gaussian Splatting System in Virtual Reality](https://dl.acm.org/doi/10.1145/3641519.3657448)

- **时间/会议**：SIGGRAPH, 2024
- **README 位置**：L197
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调三维/四维场景、几何一致性或动态重建；突出力、重力、运动轨迹、牛顿动力学或物理规律。

### 69. [PhysGaussian: Physics-Integrated 3D Gaussians for Generative Dynamics](https://arxiv.org/abs/2311.12198)

- **时间/会议**：CVPR, 2024
- **README 位置**：L198
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调三维/四维场景、几何一致性或动态重建；突出力、重力、运动轨迹、牛顿动力学或物理规律。

### 70. [Feature Splatting: Language-Driven Physics-Based Scene Synthesis and Editing](https://link.springer.com/chapter/10.1007/978-3-031-72940-9_21?fromPaywallRec=true)

- **时间/会议**：ECCV, 2024
- **README 位置**：L199
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束。

### 71. [Neural Material Adaptor for Visual Grounding of Intrinsic Dynamics](https://arxiv.org/abs/2410.08257)

- **时间/会议**：NIPS, 2024
- **README 位置**：L200
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，突出力、重力、运动轨迹、牛顿动力学或物理规律；涉及材料、流体、毛发、断裂或弹性等细粒度物理现象。

### 72. [GPT4Motion: Scripting Physical Motions in Text-to-Video Generation via Blender-Oriented GPT Planning](https://openaccess.thecvf.com/content/CVPR2024W/PBDL/html/Lv_GPT4Motion_Scripting_Physical_Motions_in_Text-to-Video_Generation_via_Blender-Oriented_GPT_CVPRW_2024_paper.html)

- **时间/会议**：CVPR, 2024, workshop
- **README 位置**：L204
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；突出力、重力、运动轨迹、牛顿动力学或物理规律。

### 73. [Learning Neural Constitutive Laws From Motion Observations for Generalizable PDE Dynamics](https://proceedings.mlr.press/v202/ma23a.html)

- **时间/会议**：ICML, 2023
- **README 位置**：L206
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，突出力、重力、运动轨迹、牛顿动力学或物理规律。

### 74. [Pac-nerf: Physics Augmented Continuum Neural Radiance Fields for Geometry-Agnostic System Identification](https://openreview.net/forum?id=tVkrbkz42vc)

- **时间/会议**：ICLR, 2023, Spotlight
- **README 位置**：L207
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调三维/四维场景、几何一致性或动态重建。

## Active Cognition for World Simulation

### 1. [Toward Physically Consistent Driving Video World Models under Challenging Trajectories](https://arxiv.org/abs/2603.24506)

- **时间/会议**：Mar., 2026
- **README 位置**：L213
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调世界模型、仿真或真实世界动态；服务于机器人、自动驾驶或具身智能场景；目标是提升物理一致性、连贯性和真实感。

### 2. [PhyPrompt: RL-based Prompt Refinement for Physically Plausible Text-to-Video Generation](https://arxiv.org/abs/2603.03505)

- **时间/会议**：Mar., 2026
- **README 位置**：L214
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；目标是提升物理一致性、连贯性和真实感。

### 3. [Can vision language models learn intuitive physics from interaction?](https://arxiv.org/abs/2602.06033)

- **时间/会议**：Feb., 2026
- **README 位置**：L216
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，结合视觉语言模型/大语言模型进行推理、规划或评估。

### 4. [Inference-time Physics Alignment of Video Generative Models with Latent World Models](https://arxiv.org/abs/2601.10553)

- **时间/会议**：PhysicsIQ Challenge, ICCV 2025
- **README 位置**：L217
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调世界模型、仿真或真实世界动态。

### 5. [PhysRVG: Physics-Aware Unified Reinforcement Learning for Video Generative Models](https://www.arxiv.org/abs/2601.11087)

- **时间/会议**：Jan., 2026
- **README 位置**：L218
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，突出力、重力、运动轨迹、牛顿动力学或物理规律。

### 6. [Improving the Physics of Video Generation with VJEPA-2 Reward Signal](https://arxiv.org/abs/2510.21840)

- **时间/会议**：PhysicsIQ Challenge, ICCV 2025
- **README 位置**：L219
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型。

### 7. [What about gravity in video generation? Post-Training Newton’s Laws with Verifiable Rewards](https://arxiv.org/pdf/2512.00425)

- **时间/会议**：Nov., 2025
- **README 位置**：L220
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；突出力、重力、运动轨迹、牛顿动力学或物理规律。

### 8. [PhysCorr: Dual-Reward DPO for Physics-Constrained Text-to-Video Generation with Automated Preference Selection](https://arxiv.org/abs/2511.03997)

- **时间/会议**：NoV,. 2025
- **README 位置**：L221
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型。

### 9. [World Simulation with Video Foundation Models for Physical AI](https://arxiv.org/abs/2511.00062)

- **时间/会议**：Oct., 2025
- **README 位置**：L222
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调世界模型、仿真或真实世界动态。

### 10. [PhysMaster: Mastering Physical Representation for Video Generation via Reinforcement Learning](https://openreview.net/forum?id=CG2VPDZkwM)

- **时间/会议**：Oct., 2025
- **README 位置**：L223
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；突出力、重力、运动轨迹、牛顿动力学或物理规律。

### 11. [PhysWorld: From Real Videos to World Models of Deformable Objects via Physics-Aware Demonstration Synthesis](https://openreview.net/forum?id=dggfgPzGFW)

- **时间/会议**：Oct., 2025
- **README 位置**：L224
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调世界模型、仿真或真实世界动态。

### 12. [Enhancing Physical Plausibility in Video Generation by Reasoning the Implausibility](https://www.arxiv.org/abs/2509.24702)

- **时间/会议**：Sep., 2025
- **README 位置**：L225
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；关注因果、常识和直觉物理推理。

### 13. [Hierarchical Fine-grained Preference Optimization for Physically Plausible Video Generation](https://arxiv.org/abs/2508.10858)

- **时间/会议**：Aug., 2025
- **README 位置**：L226
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；目标是提升物理一致性、连贯性和真实感。

### 14. [Matrix-Game: Interactive World Foundation Model](https://arxiv.org/abs/2506.18701)

- **时间/会议**：Jun., 2025
- **README 位置**：L228
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束。

### 15. [RoboScape: Physics-informed Embodied World Model](https://arxiv.org/abs/2506.23135)

- **时间/会议**：Jun., 2025
- **README 位置**：L229
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调世界模型、仿真或真实世界动态；服务于机器人、自动驾驶或具身智能场景。

### 16. [RDPO: Real Data Preference Optimization for Physics Consistency Video Generation](https://arxiv.org/abs/2506.18655)

- **时间/会议**：Jun., 2025
- **README 位置**：L230
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；目标是提升物理一致性、连贯性和真实感。

### 17. [VideoREPA: Learning Physics for Video Generation through Relational Alignment with Foundation Models](https://arxiv.org/abs/2505.23656)

- **时间/会议**：May, 2025
- **README 位置**：L232
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型。

### 18. [Learning World Models for Interactive Video Generation](https://arxiv.org/html/2505.21996v1)

- **时间/会议**：May, 2025
- **README 位置**：L233
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；强调世界模型、仿真或真实世界动态。

### 19. [MirrorVerse: Pushing Diffusion Models to Realistically Reflect the World](https://arxiv.org/abs/2504.15397)

- **时间/会议**：CVPR, 2025
- **README 位置**：L235
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，目标是提升物理一致性、连贯性和真实感。

### 20. [Pisa experiments: Exploring physics post-training for video diffusion models by watching stuff drop](https://arxiv.org/abs/2503.09595)

- **时间/会议**：Mar., 2025
- **README 位置**：L239
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型。

### 21. [Wisa: World simulator assistant for physics-aware text-to-video generation](https://arxiv.org/abs/2503.08153)

- **时间/会议**：Mar., 2025
- **README 位置**：L240
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；强调世界模型、仿真或真实世界动态。

### 22. [Do generative video models learn physical principles from watching videos?](https://arxiv.org/abs/2501.09038)

- **时间/会议**：Jan., 2025
- **README 位置**：L242
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束。

### 23. [Cosmos world foundation model platform for physical ai](https://arxiv.org/abs/2501.03575)

- **时间/会议**：Jan., 2025
- **README 位置**：L243
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束。

### 24. [Phyt2v: Llm-guided iterative self-refinement for physics-grounded text-to-video generation](https://arxiv.org/abs/2412.00596)

- **时间/会议**：CVPR, 2025
- **README 位置**：L245
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；结合视觉语言模型/大语言模型进行推理、规划或评估。

### 25. [MagicTime: Time-lapse Video Generation Models as Metamorphic Simulators](https://arxiv.org/abs/2404.05014)

- **时间/会议**：TPAMI, 2025
- **README 位置**：L247
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；强调世界模型、仿真或真实世界动态。

### 26. [Improving Dynamic Object Interactions in Text-to-Video Generation with AI Feedback](https://arxiv.org/abs/2412.02617)

- **时间/会议**：Dec., 2024
- **README 位置**：L249
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型。

### 27. [Physical informed driving world model](https://arxiv.org/abs/2412.08410)

- **时间/会议**：Dec., 2024
- **README 位置**：L250
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调世界模型、仿真或真实世界动态；服务于机器人、自动驾驶或具身智能场景。

### 28. [How far is video generation from world model: A physical law perspective](https://arxiv.org/abs/2411.02385)

- **时间/会议**：Nov., 2024
- **README 位置**：L251
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；强调世界模型、仿真或真实世界动态；突出力、重力、运动轨迹、牛顿动力学或物理规律。

### 29. [Video generation models as world simulators](https://arxiv.org/abs/2410.18072)

- **时间/会议**：Oct., 2024
- **README 位置**：L252
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，面向文本到视频或视频扩散模型；强调世界模型、仿真或真实世界动态。

### 30. [Gen-drive: Enhancing diffusion generative driving policies with reward modeling and reinforcement learning fine-tuning](https://arxiv.org/abs/2410.05582)

- **时间/会议**：Oct, 2024
- **README 位置**：L254
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，服务于机器人、自动驾驶或具身智能场景；突出力、重力、运动轨迹、牛顿动力学或物理规律。

### 31. [Genie: ¨ Generative interactive environments](https://arxiv.org/abs/2402.15391)

- **时间/会议**：Feb., 2024
- **README 位置**：L259
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束。

### 32. [Learning interactive real-world simulators](https://arxiv.org/abs/2310.06114)

- **时间/会议**：ICLR, 2024, Outstanding Paper Award
- **README 位置**：L261
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调世界模型、仿真或真实世界动态。

### 33. [Physically embodied gaussian splatting: A visually learnt and physically grounded 3d representation for robotics](https://openreview.net/forum?id=AEq0onGrN2&noteId=AEq0onGrN2)

- **时间/会议**：CoRL, 2024
- **README 位置**：L262
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调三维/四维场景、几何一致性或动态重建；服务于机器人、自动驾驶或具身智能场景。

## Datasets, Benchmarks and Metrics

### 1. [PhysInOne: Visual Physics Learning and Reasoning in One Suite](https://arxiv.org/abs/2604.09415)

- **时间/会议**：CVPR, 2026
- **README 位置**：L270
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，关注因果、常识和直觉物理推理。

### 2. [Physion-Eval: Evaluating Physical Realism in Generated Video via Human Reasoning](https://arxiv.org/abs/2603.19607)

- **时间/会议**：Mar., 2026
- **README 位置**：L271
- **简介**：评测/数据集类工作，关注如何度量模型的物理理解或生成真实性，关注因果、常识和直觉物理推理；目标是提升物理一致性、连贯性和真实感。

### 3. [VisPhyWorld: Probing Physical Reasoning via Code-Driven Video Reconstruction](https://arxiv.org/abs/2602.13294)

- **时间/会议**：Feb., 2026
- **README 位置**：L272
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调三维/四维场景、几何一致性或动态重建；关注因果、常识和直觉物理推理。

### 4. [LikePhys: Evaluating Intuitive Physics Understanding in Video Diffusion Models via Likelihood Preference](https://arxiv.org/abs/2510.11512)

- **时间/会议**：Oct., 2025
- **README 位置**：L278
- **简介**：评测/数据集类工作，关注如何度量模型的物理理解或生成真实性，面向文本到视频或视频扩散模型；关注因果、常识和直觉物理推理。

### 5. [CoPhyBench: Benchmarking Physical Reasoning from Conditional Video Observation](https://openreview.net/forum?id=rDiKG1xlDV)

- **时间/会议**：Oct., 2025
- **README 位置**：L279
- **简介**：评测/数据集类工作，关注如何度量模型的物理理解或生成真实性，关注因果、常识和直觉物理推理。

### 6. [Cosmos-Eval: Towards Explainable Evaluation of Physics and Semantics in Text-to-Video Models](https://openreview.net/forum?id=KdYKSOY9MP)

- **时间/会议**：Oct., 2025
- **README 位置**：L280
- **简介**：评测/数据集类工作，关注如何度量模型的物理理解或生成真实性，面向文本到视频或视频扩散模型。

### 7. [TRAVL: A Recipe for Making Video-Language Models Better Judges of Physics Implausibility](http://arxiv.org/abs/2510.07550)

- **时间/会议**：Oct., 2025
- **README 位置**：L282
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，结合视觉语言模型/大语言模型进行推理、规划或评估。

### 8. [Does Physics Knowledge Emerge in Frontier Models?](https://www.arxiv.org/abs/2510.06251)

- **时间/会议**：Oct., 2025
- **README 位置**：L283
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束。

### 9. [Can Your Model Separate Yolks with a Water Bottle? Benchmarking Physical Commonsense Understanding in Video Generation Model](https://arxiv.org/abs/2507.15824)

- **时间/会议**：Jul., 2025
- **README 位置**：L285
- **简介**：评测/数据集类工作，关注如何度量模型的物理理解或生成真实性，面向文本到视频或视频扩散模型；关注因果、常识和直觉物理推理。

### 10. [PhyWorldBench: A Comprehensive Evaluation of Physical Realism in Text-to-Video Models](https://arxiv.org/abs/2507.13428)

- **时间/会议**：Jul., 2025
- **README 位置**：L286
- **简介**：评测/数据集类工作，关注如何度量模型的物理理解或生成真实性，面向文本到视频或视频扩散模型；目标是提升物理一致性、连贯性和真实感。

### 11. [GenWorld: Towards Detecting AI-generated Real-world Simulation Videos](https://arxiv.org/abs/2506.10975)

- **时间/会议**：Jun., 2025
- **README 位置**：L288
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，强调世界模型、仿真或真实世界动态。

### 12. [IntPhys 2: Benchmarking Intuitive Physics Understanding In Complex Synthetic Environments](https://arxiv.org/abs/2506.09849)

- **时间/会议**：Jun., 2025
- **README 位置**：L289
- **简介**：评测/数据集类工作，关注如何度量模型的物理理解或生成真实性，关注因果、常识和直觉物理推理。

### 13. [PhysGaia: A Physics-Aware Dataset of Multi-Body Interactions for Dynamic Novel View Synthesis](https://arxiv.org/abs/2506.02794)

- **时间/会议**：Jun., 2025
- **README 位置**：L291
- **简介**：评测/数据集类工作，关注如何度量模型的物理理解或生成真实性。

### 14. [Seeing is Not Reasoning: MVPBench for Graph-based Evaluation of Multi-path Visual Physical CoT](https://arxiv.org/abs/2505.24182)

- **时间/会议**：May, 2025
- **README 位置**：L292
- **简介**：评测/数据集类工作，关注如何度量模型的物理理解或生成真实性，关注因果、常识和直觉物理推理。

### 15. [Universal Visuo-Tactile Video Understanding for Embodied Interaction](https://arxiv.org/abs/2505.22566)

- **时间/会议**：May, 2025
- **README 位置**：L293
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，服务于机器人、自动驾驶或具身智能场景；关注因果、常识和直觉物理推理。

### 16. [T2VPhysBench: A First-Principles Benchmark for Physical Consistency in Text-to-Video Generation](https://arxiv.org/abs/2505.00337)

- **时间/会议**：May, 2025
- **README 位置**：L294
- **简介**：评测/数据集类工作，关注如何度量模型的物理理解或生成真实性，面向文本到视频或视频扩散模型；目标是提升物理一致性、连贯性和真实感。

### 17. [Morpheus: Benchmarking Physical Reasoning of Video Generative Models with Real Physical Experiments](https://arxiv.org/abs/2504.02918)

- **时间/会议**：Apr., 2025
- **README 位置**：L296
- **简介**：评测/数据集类工作，关注如何度量模型的物理理解或生成真实性，关注因果、常识和直觉物理推理。

### 18. [HOIGen-1M: A Large-scale Dataset for Human-Object Interaction Video Generation](https://arxiv.org/abs/2503.23715)

- **时间/会议**：Mar., 2025; CVPR, 2025
- **README 位置**：L298
- **简介**：评测/数据集类工作，关注如何度量模型的物理理解或生成真实性，面向文本到视频或视频扩散模型。

### 19. [VideoPhy-2: A Challenging Action-Centric Physical Commonsense Evaluation in Video Generation](https://arxiv.org/abs/2503.06800)

- **时间/会议**：Mar., 2025
- **README 位置**：L303
- **简介**：评测/数据集类工作，关注如何度量模型的物理理解或生成真实性，面向文本到视频或视频扩散模型；关注因果、常识和直觉物理推理。

### 20. [A physical coherence benchmark for evaluating video generation models via optical flow-guided frame prediction](https://www.arxiv.org/abs/2502.05503)

- **时间/会议**：Feb., 2025
- **README 位置**：L304
- **简介**：评测/数据集类工作，关注如何度量模型的物理理解或生成真实性，面向文本到视频或视频扩散模型；目标是提升物理一致性、连贯性和真实感。

### 21. [PhysGame: Uncovering Physical Commonsense Violations in Gameplay Videos](https://arxiv.org/abs/2412.01800)

- **时间/会议**：Dec., 2024
- **README 位置**：L307
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，关注因果、常识和直觉物理推理。

### 22. [What You See Is What Matters: A Novel Visual and Physics-Based Metric for Evaluating Video Generation Quality](https://arxiv.org/abs/2411.13609)

- **时间/会议**：Nov., 2024
- **README 位置**：L309
- **简介**：评测/数据集类工作，关注如何度量模型的物理理解或生成真实性，面向文本到视频或视频扩散模型。

### 23. [Towards world simulator: Crafting physical commonsense-based benchmark for video generation](https://arxiv.org/abs/2410.05363)

- **时间/会议**：Oct., 2024
- **README 位置**：L310
- **简介**：评测/数据集类工作，关注如何度量模型的物理理解或生成真实性，面向文本到视频或视频扩散模型；强调世界模型、仿真或真实世界动态；关注因果、常识和直觉物理推理。

### 24. [WorldSimBench: Towards Video Generation Models as World Simulators](https://arxiv.org/abs/2410.18072)

- **时间/会议**：Oct., 2024
- **README 位置**：L311
- **简介**：评测/数据集类工作，关注如何度量模型的物理理解或生成真实性，面向文本到视频或视频扩散模型；强调世界模型、仿真或真实世界动态。

### 25. [Phybench: A physical commonsense benchmark for evaluating text-to-image model](https://arxiv.org/abs/2406.11802)

- **时间/会议**：Jun., 2024
- **README 位置**：L312
- **简介**：评测/数据集类工作，关注如何度量模型的物理理解或生成真实性，关注因果、常识和直觉物理推理。

### 26. [Videophy: Evaluating physical commonsense for video generation](https://arxiv.org/abs/2406.03520)

- **时间/会议**：Jun., 2024
- **README 位置**：L313
- **简介**：评测/数据集类工作，关注如何度量模型的物理理解或生成真实性，面向文本到视频或视频扩散模型；关注因果、常识和直觉物理推理。

### 27. [Physion++: Evaluating physical scene understanding that requires online inference of different physical properties](https://arxiv.org/abs/2306.15668)

- **时间/会议**：Nips, 2023
- **README 位置**：L315
- **简介**：评测/数据集类工作，关注如何度量模型的物理理解或生成真实性，关注因果、常识和直觉物理推理。

### 28. [Craft: A benchmark for causal reasoning about forces and interactions](https://arxiv.org/abs/2012.04293)

- **时间/会议**：ACL, 2022
- **README 位置**：L316
- **简介**：评测/数据集类工作，关注如何度量模型的物理理解或生成真实性，突出力、重力、运动轨迹、牛顿动力学或物理规律；关注因果、常识和直觉物理推理。

### 29. [Physion: Evaluating physical prediction from vision in humans and machines](https://arxiv.org/abs/2106.08261)

- **时间/会议**：Nips, 2021
- **README 位置**：L317
- **简介**：评测/数据集类工作，关注如何度量模型的物理理解或生成真实性。

## VLMs, LLMs, MLLMs on Physical Understanding

### 1. [Can vision language models learn intuitive physics from interaction?](https://openreview.net/forum?id=XdLgOm5giq)

- **时间/会议**：Oct., 2025
- **README 位置**：L324
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，结合视觉语言模型/大语言模型进行推理、规划或评估。

### 2. [Beyond Static Vision: Scene Dynamic Field Unlocks Intuitive Physics Understanding in Multi-modal Large Language Models](https://openreview.net/forum?id=Ax02eR2c3d)

- **时间/会议**：Oct., 2025
- **README 位置**：L325
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，结合视觉语言模型/大语言模型进行推理、规划或评估；关注因果、常识和直觉物理推理。

### 3. [Inferring Dynamic Physical Properties from Video Foundation Models](https://arxiv.org/abs/2510.02311)

- **时间/会议**：Oct., 2025
- **README 位置**：L327
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束。

### 4. [SlotPi: Physics-informed Object-centric Reasoning Models](https://arxiv.org/abs/2506.10778)

- **时间/会议**：Jun., 2025
- **README 位置**：L328
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，关注因果、常识和直觉物理推理。

### 5. [PhyBlock: A Progressive Benchmark for Physical Understanding and Planning via 3D Block Assembly](https://arxiv.org/abs/2506.08708)

- **时间/会议**：Jun., 2025
- **README 位置**：L329
- **简介**：评测/数据集类工作，关注如何度量模型的物理理解或生成真实性，强调三维/四维场景、几何一致性或动态重建；关注因果、常识和直觉物理推理。

## Benchmarks

### 1. [How Far Are Vision-Language Models from Constructing the Real World? A Benchmark for Physical Generative Reasoning](https://arxiv.org/abs/2603.24866)

- **时间/会议**：Mar., 2026
- **README 位置**：L335
- **简介**：评测/数据集类工作，关注如何度量模型的物理理解或生成真实性，强调世界模型、仿真或真实世界动态；结合视觉语言模型/大语言模型进行推理、规划或评估；关注因果、常识和直觉物理推理。

### 2. [A Shortcut-aware Video-QA Benchmark for Physical Understanding via Minimal Video Pairs](https://www.arxiv.org/abs/2506.09987)

- **时间/会议**：Jun., 2025
- **README 位置**：L336
- **简介**：评测/数据集类工作，关注如何度量模型的物理理解或生成真实性，关注因果、常识和直觉物理推理。

### 3. [Scaling Physical Reasoning with the PHYSICS Dataset](https://arxiv.org/abs/2506.00022)

- **时间/会议**：May., 2025
- **README 位置**：L337
- **简介**：评测/数据集类工作，关注如何度量模型的物理理解或生成真实性，关注因果、常识和直觉物理推理。

### 4. [CausalVQA: A Physically Grounded Causal Reasoning Benchmark for Video Models](https://arxiv.org/abs/2506.09943)

- **时间/会议**：Jun., 2025
- **README 位置**：L338
- **简介**：评测/数据集类工作，关注如何度量模型的物理理解或生成真实性，关注因果、常识和直觉物理推理。

### 5. [PhyX: Does Your Model Have the "Wits" for Physical Reasoning?](https://arxiv.org/abs/2505.15929v2)

- **时间/会议**：May, 2025
- **README 位置**：L340
- **简介**：方法类工作，关注在生成或世界建模中注入物理约束，关注因果、常识和直觉物理推理。

### 6. [Bridging the Reality Gap: A Benchmark for Physical Reasoning in General World Models with Various Physical Phenomena beyond Mechanics](https://openreview.net/pdf?id=vsYt8UHGzI)

- **时间/会议**：Nov., 2024
- **README 位置**：L341
- **简介**：评测/数据集类工作，关注如何度量模型的物理理解或生成真实性，强调世界模型、仿真或真实世界动态；关注因果、常识和直觉物理推理。
