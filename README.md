# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2025-07-12 00:58:27

## 📰 Latest Updates

🔧 **[2025-06-26] HTTP 301 Redirect Issue Completely Resolved!** 
- Implemented multi-layer fallback strategy to thoroughly solve network compatibility issues

🔧 **[2025-06-26] Configurable Search Keywords Feature Added!**
- You can now customize search keywords by modifying `data/search_config.json`
- Support for different search scopes: abstract-only, title-only, or both
- Flexible keyword configuration for targeted paper collection

- View detailed updates: [News.md](News.md) 📋

---

## Categories

- [3DGS Surveys](#3dgs-surveys) (18 papers) - Survey papers and benchmarks about 3D Gaussian Splatting
- [Acceleration](#acceleration) (278 papers) - Papers about speeding up rendering or training
- [Applications](#applications) (995 papers) - Papers about specific applications
- [Avatar Generation](#avatar-generation) (329 papers) - Papers about human avatar generation
- [Dynamic Scene](#dynamic-scene) (402 papers) - Papers about dynamic scene reconstruction and rendering
- [Few-shot](#few-shot) (69 papers) - Papers about few-shot or sparse view reconstruction
- [Geometry Reconstruction](#geometry-reconstruction) (315 papers) - Papers about 3D geometry reconstruction
- [Large Scene](#large-scene) (65 papers) - Papers about large-scale scene reconstruction
- [Model Compression](#model-compression) (397 papers) - Papers about model compression and optimization
- [Quality Enhancement](#quality-enhancement) (163 papers) - Papers focusing on improving rendering quality
- [Ray Tracing](#ray-tracing) (15 papers) - Papers about ray tracing and ray casting in Gaussian Splatting
- [Relighting](#relighting) (108 papers) - Papers about relighting and illumination effects in Gaussian Splatting
- [SLAM](#slam) (157 papers) - Papers about SLAM using Gaussian Splatting
- [Scene Understanding](#scene-understanding) (188 papers) - Papers about scene understanding and semantic analysis



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### 3DGS Surveys

- **[3D Gaussian Splatting for Fine-Detailed Surface Reconstruction in
  Large-Scale Scene](https://arxiv.org/abs/2506.17636v1)**  
  Authors: Shihan Chen, Zhaojin Li, Zeyu Chen, Qingsong Yan, Gaoyang Shen, Ran Duan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.17636v1.pdf)  
  Keywords: dynamic, high-fidelity, face, autonomous driving, outdoor, efficient, ar, gaussian splatting, survey, 3d gaussian, nerf  
- **[R3eVision: A Survey on Robust Rendering, Restoration, and Enhancement
  for 3D Low-Level Vision](https://arxiv.org/abs/2506.16262v2)**  
  Authors: Weeyoung Kwon, Jeahun Sung, Minkyu Jeon, Chanho Eom, Jihyong Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.16262v2.pdf)  
  Keywords: 3d reconstruction, high-fidelity, robotics, autonomous driving, neural rendering, gaussian splatting, ar, vr, survey, 3d gaussian, nerf  
- **[From Flight to Insight: Semantic 3D Reconstruction for Aerial Inspection
  via Gaussian Splatting and Language-Guided Segmentation](https://arxiv.org/abs/2505.17402v1)**  
  Authors: Mahmoud Chick Zaouali, Todd Charter, Homayoun Najjaran  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.17402v1.pdf)  
  Keywords: 3d reconstruction, high-fidelity, understanding, segmentation, outdoor, efficient, neural rendering, gaussian splatting, ar, semantic, survey, 3d gaussian  
- **[Is Semantic SLAM Ready for Embedded Systems ? A Comparative Survey](https://arxiv.org/abs/2505.12384v1)**  
  Authors: Calvin Galagain, Martyna Poreba, François Goulette  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.12384v1.pdf)  
  Keywords: segmentation, efficient, ar, gaussian splatting, localization, semantic, survey, slam, 3d gaussian, mapping, nerf  
- **[Advances in Radiance Field for Dynamic Scene: From Neural Field to
  Gaussian Field](https://arxiv.org/abs/2505.10049v2)**  
  Authors: Jinlong Fan, Xuepu Zeng, Jing Zhang, Mingming Gong, Yuxiang Yang, Dacheng Tao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.10049v2.pdf)  
  Keywords: dynamic, body, motion, understanding, ar, gaussian splatting, survey, 3d gaussian, 4d  
- **[A Survey of 3D Reconstruction with Event Cameras](https://arxiv.org/abs/2505.08438v2)**  
  Authors: Chuanzhi Xu, Haoxian Zhou, Langyi Chen, Haodong Chen, Ying Zhou, Vera Chung, Qiang Qu, Weidong Cai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.08438v2.pdf)  
  Keywords: dynamic, 3d reconstruction, motion, robotics, autonomous driving, neural rendering, gaussian splatting, ar, survey, 3d gaussian, geometry, illumination, nerf  
- **[UltraGauss: Ultrafast Gaussian Reconstruction of 3D Ultrasound Volumes](https://arxiv.org/abs/2505.05643v1)**  
  Authors: Mark C. Eid, Ana I. L. Namburete, João F. Henriques  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.05643v1.pdf)  
  Keywords: 3d reconstruction, efficient, ar, gaussian splatting, survey, fast  
- **[Visual enhancement and 3D representation for underwater scenes: a review](https://arxiv.org/abs/2505.01869v1)**  
  Authors: Guoxi Huang, Haoran Wang, Brett Seymour, Evan Kovacs, John Ellerbrock, Dave Blackham, Nantheera Anantrasirichai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.01869v1.pdf)  
  Keywords: 3d reconstruction, lighting, ar, survey, 3d gaussian  
- **[A Survey on 3D Reconstruction Techniques in Plant Phenotyping: From
  Classical Methods to Neural Radiance Fields (NeRF), 3D Gaussian Splatting
  (3DGS), and Beyond](https://arxiv.org/abs/2505.00737v1)**  
  Authors: Jiajia Li, Xinda Qi, Seyed Hamidreza Nabaei, Meiqi Liu, Dong Chen, Xin Zhang, Xunyuan Yin, Zhaojian Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.00737v1.pdf)  
  Keywords: 3d reconstruction, face, understanding, outdoor, sparse view, ar, gaussian splatting, survey, 3d gaussian, geometry, nerf  
- **[Digital Twin Generation from Visual Data: A Survey](https://arxiv.org/abs/2504.13159v1)**  
  Authors: Andrew Melnik, Benjamin Alt, Giang Nguyen, Artur Wilkowski, Maciej Stefańczyk, Qirui Wu, Sinan Harms, Helge Rhodin, Manolis Savva, Michael Beetz  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.13159v1.pdf)  
  Keywords: robotics, lighting, segmentation, ar, gaussian splatting, semantic, survey, 3d gaussian  

### Acceleration

*Showing the latest 50 out of 278 papers*

- **[Enhancing non-Rigid 3D Model Deformations Using Mesh-based Gaussian
  Splatting](https://arxiv.org/abs/2507.07000v1)**  
  Authors: Wijayathunga W. M. R. D. B  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07000v1.pdf)  
  Keywords: face, animation, ar, gaussian splatting, 3d gaussian, fast, deformation  
- **[FlexGaussian: Flexible and Cost-Effective Training-Free Compression for
  3D Gaussian Splatting](https://arxiv.org/abs/2507.06671v1)**  
  Authors: Boyuan Tian, Qizhe Gao, Siran Xianyu, Xiaotong Cui, Minjia Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06671v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, fast, compression  
- **[LangSplatV2: High-dimensional 3D Language Gaussian Splatting with 450+
  FPS](https://arxiv.org/abs/2507.07136v1)**  
  Authors: Wanhua Li, Yujie Zhao, Minghan Qin, Yang Liu, Yuanhao Cai, Chuang Gan, Hanspeter Pfister  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07136v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://langsplat-v2.github.io.)  
  Keywords: high quality, efficient, ar, gaussian splatting, semantic, fast  
- **[A3FR: Agile 3D Gaussian Splatting with Incremental Gaze Tracked Foveated
  Rendering in Virtual Reality](https://arxiv.org/abs/2507.04147v1)**  
  Authors: Shuo Xin, Haiyu Wang, Sai Qian Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.04147v1.pdf)  
  Keywords: dynamic, efficient rendering, face, tracking, efficient, head, neural rendering, gaussian splatting, ar, vr, human, 3d gaussian  
- **[Gaussian-LIC2: LiDAR-Inertial-Camera Gaussian Splatting SLAM](https://arxiv.org/abs/2507.04004v2)**  
  Authors: Xiaolei Lang, Jiajun Lv, Kai Tang, Laijian Li, Jianxin Huang, Lina Liu, Yong Liu, Xingxing Zuo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.04004v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://xingxingzuo.github.io/gaussian_lic2.)  
  Keywords: ar, gaussian splatting, lightweight, slam, 3d gaussian, fast  
- **[ArmGS: Composite Gaussian Appearance Refinement for Modeling Dynamic
  Urban Environments](https://arxiv.org/abs/2507.03886v1)**  
  Authors: Guile Wu, Dongfeng Bai, Bingbing Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.03886v1.pdf)  
  Keywords: dynamic, urban scene, high-fidelity, autonomous driving, ar, gaussian splatting, 3d gaussian, real-time rendering  
- **[HyperGaussians: High-Dimensional Gaussian Splatting for High-Fidelity
  Animatable Face Avatars](https://arxiv.org/abs/2507.02803v2)**  
  Authors: Gent Serifi, Marcel C. Bühler  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.02803v2.pdf)  
  Keywords: high-fidelity, face, lighting, ar, gaussian splatting, avatar, reflection, 3d gaussian, fast, deformation  
- **[A LoD of Gaussians: Unified Training and Rendering for Ultra-Large Scale
  Reconstruction with External Memory](https://arxiv.org/abs/2507.01110v2)**  
  Authors: Felix Windisch, Lukas Radl, Thomas Köhler, Michael Steiner, Dieter Schmalstieg, Markus Steinberger  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.01110v2.pdf)  
  Keywords: dynamic, efficient, ar, gaussian splatting, lightweight, vr, real-time rendering  
- **[GaussianVLM: Scene-centric 3D Vision-Language Models using
  Language-aligned Gaussian Splats for Embodied Reasoning and Beyond](https://arxiv.org/abs/2507.00886v1)**  
  Authors: Anna-Maria Halacheva, Jan-Nico Zaech, Xi Wang, Danda Pani Paudel, Luc Van Gool  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.00886v1.pdf)  
  Keywords: understanding, ar, gaussian splatting, compact, 3d gaussian, fast  
- **[GDGS: 3D Gaussian Splatting Via Geometry-Guided Initialization And
  Dynamic Density Control](https://arxiv.org/abs/2507.00363v1)**  
  Authors: Xingjun Wang, Lianlei Shan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.00363v1.pdf)  
  Keywords: dynamic, high-fidelity, face, ar, gaussian splatting, 3d gaussian, fast, real-time rendering, geometry  

### Applications

*Showing the latest 50 out of 995 papers*

- **[RTR-GS: 3D Gaussian Splatting for Inverse Rendering with Radiance
  Transfer and Reflection](https://arxiv.org/abs/2507.07733v1)**  
  Authors: Yongyang Zhou, Fang-Lue Zhang, Zichen Wang, Lei Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07733v1.pdf)  
  Keywords: lighting, efficient, ar, gaussian splatting, reflection, 3d gaussian, relighting  
- **[MUVOD: A Novel Multi-view Video Object Segmentation Dataset and A
  Benchmark for 3D Segmentation](https://arxiv.org/abs/2507.07519v1)**  
  Authors: Bangning Wei, Joshua Maraval, Meriem Outtas, Kidiyo Kpalma, Nicolas Ramin, Lu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07519v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://volumetric-repository.labs.b-com.com/#/muvod.)  
  Keywords: dynamic, motion, understanding, segmentation, outdoor, ar, gaussian splatting, 3d gaussian, 4d, nerf  
- **[SD-GS: Structured Deformable 3D Gaussians for Efficient Dynamic Scene
  Reconstruction](https://arxiv.org/abs/2507.07465v1)**  
  Authors: Wei Yao, Shuzhao Xie, Letian Li, Weixiang Zhang, Zhixin Lai, Shiqi Dai, Ke Zhang, Zhi Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07465v1.pdf)  
  Keywords: dynamic, motion, efficient, ar, gaussian splatting, compact, 3d gaussian, 4d, deformation  
- **[Seg-Wild: Interactive Segmentation based on 3D Gaussian Splatting for
  Unconstrained Image Collections](https://arxiv.org/abs/2507.07395v1)**  
  Authors: Yongtang Bao, Chengjie Tang, Yuze Wang, Haojie Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07395v1.pdf)  
  Keywords: segmentation, lighting, ar, gaussian splatting, 3d gaussian  
- **[Enhancing non-Rigid 3D Model Deformations Using Mesh-based Gaussian
  Splatting](https://arxiv.org/abs/2507.07000v1)**  
  Authors: Wijayathunga W. M. R. D. B  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07000v1.pdf)  
  Keywords: face, animation, ar, gaussian splatting, 3d gaussian, fast, deformation  
- **[Photometric Stereo using Gaussian Splatting and inverse rendering](https://arxiv.org/abs/2507.06684v1)**  
  Authors: Matéo Ducastel, David Tschumperlé, Yvain Quéau  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06684v1.pdf)  
  Keywords: ar, gaussian splatting  
- **[FlexGaussian: Flexible and Cost-Effective Training-Free Compression for
  3D Gaussian Splatting](https://arxiv.org/abs/2507.06671v1)**  
  Authors: Boyuan Tian, Qizhe Gao, Siran Xianyu, Xiaotong Cui, Minjia Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06671v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, fast, compression  
- **[ClipGS: Clippable Gaussian Splatting for Interactive Cinematic
  Visualization of Volumetric Medical Data](https://arxiv.org/abs/2507.06647v1)**  
  Authors: Chengkun Li, Yuqi Tong, Kai Chen, Zhenya Yang, Ruiyang Li, Shi Qiu, Jason Ying-Kuen Chan, Pheng-Ann Heng, Qi Dou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06647v1.pdf)  
  Keywords: dynamic, understanding, ar, gaussian splatting, medical, deformation  
- **[LangSplatV2: High-dimensional 3D Language Gaussian Splatting with 450+
  FPS](https://arxiv.org/abs/2507.07136v1)**  
  Authors: Wanhua Li, Yujie Zhao, Minghan Qin, Yang Liu, Yuanhao Cai, Chuang Gan, Hanspeter Pfister  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07136v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://langsplat-v2.github.io.)  
  Keywords: high quality, efficient, ar, gaussian splatting, semantic, fast  
- **[LighthouseGS: Indoor Structure-aware 3D Gaussian Splatting for
  Panorama-Style Mobile Captures](https://arxiv.org/abs/2507.06109v1)**  
  Authors: Seungoh Han, Jaehoon Jang, Hyunsu Kim, Jaeheung Surh, Junhyung Kwak, Hyowon Ha, Kyungdon Joo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06109v1.pdf)  
  Keywords: high-fidelity, motion, ar, gaussian splatting, 3d gaussian, geometry  

### Avatar Generation

*Showing the latest 50 out of 329 papers*

- **[Enhancing non-Rigid 3D Model Deformations Using Mesh-based Gaussian
  Splatting](https://arxiv.org/abs/2507.07000v1)**  
  Authors: Wijayathunga W. M. R. D. B  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07000v1.pdf)  
  Keywords: face, animation, ar, gaussian splatting, 3d gaussian, fast, deformation  
- **[Reflections Unlock: Geometry-Aware Reflection Disentanglement in 3D
  Gaussian Splatting for Photorealistic Scenes Rendering](https://arxiv.org/abs/2507.06103v1)**  
  Authors: Jiayi Song, Zihan Ye, Qingyuan Zhou, Weidong Yang, Ben Fei, Jingyi Xu, Ying He, Wanli Ouyang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06103v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ref-unlock.github.io/.)  
  Keywords: face, efficient, ar, gaussian splatting, reflection, 3d gaussian, geometry, nerf  
- **[VisualSpeaker: Visually-Guided 3D Avatar Lip Synthesis](https://arxiv.org/abs/2507.06060v1)**  
  Authors: Alexandre Symeonidis-Herzig, Özge Mercanoğlu Sincan, Richard Bowden  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06060v1.pdf)  
  Keywords: high-fidelity, animation, ar, gaussian splatting, avatar, human, recognition, 3d gaussian  
- **[DreamArt: Generating Interactable Articulated Objects from a Single
  Image](https://arxiv.org/abs/2507.05763v1)**  
  Authors: Ruijie Lu, Yu Liu, Jiaxiang Tang, Junfeng Ni, Yuxiang Wang, Diwen Wan, Gang Zeng, Yixin Chen, Siyuan Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.05763v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://dream-art-0.github.io/DreamArt/.)  
  Keywords: high-fidelity, motion, face, segmentation, ar, gaussian splatting, vr, geometry, nerf  
- **[A Probabilistic Approach to Uncertainty Quantification Leveraging 3D
  Geometry](https://arxiv.org/abs/2507.06269v1)**  
  Authors: Rushil Desai, Frederik Warburg, Trevor Darrell, Marissa Ramirez de Chanlatte  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06269v1.pdf)  
  Keywords: face, efficient, ar, gaussian splatting, 3d gaussian, geometry, nerf  
- **[A3FR: Agile 3D Gaussian Splatting with Incremental Gaze Tracked Foveated
  Rendering in Virtual Reality](https://arxiv.org/abs/2507.04147v1)**  
  Authors: Shuo Xin, Haiyu Wang, Sai Qian Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.04147v1.pdf)  
  Keywords: dynamic, efficient rendering, face, tracking, efficient, head, neural rendering, gaussian splatting, ar, vr, human, 3d gaussian  
- **[HyperGaussians: High-Dimensional Gaussian Splatting for High-Fidelity
  Animatable Face Avatars](https://arxiv.org/abs/2507.02803v2)**  
  Authors: Gent Serifi, Marcel C. Bühler  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.02803v2.pdf)  
  Keywords: high-fidelity, face, lighting, ar, gaussian splatting, avatar, reflection, 3d gaussian, fast, deformation  
- **[Masks make discriminative models great again!](https://arxiv.org/abs/2507.00916v1)**  
  Authors: Tianshi Cao, Marie-Julie Rakotosaona, Ben Poole, Federico Tombari, Michael Niemeyer  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.00916v1.pdf)  
  Keywords: ar, 3d gaussian, face  
- **[GDGS: 3D Gaussian Splatting Via Geometry-Guided Initialization And
  Dynamic Density Control](https://arxiv.org/abs/2507.00363v1)**  
  Authors: Xingjun Wang, Lianlei Shan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.00363v1.pdf)  
  Keywords: dynamic, high-fidelity, face, ar, gaussian splatting, 3d gaussian, fast, real-time rendering, geometry  
- **[MILo: Mesh-In-the-Loop Gaussian Splatting for Detailed and Efficient
  Surface Reconstruction](https://arxiv.org/abs/2506.24096v1)**  
  Authors: Antoine Guédon, Diego Gomez, Nissim Maruani, Bingchen Gong, George Drettakis, Maks Ovsjanikov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.24096v1.pdf)  
  Keywords: face, efficient, animation, ar, gaussian splatting, 3d gaussian, fast, geometry  

### Dynamic Scene

*Showing the latest 50 out of 402 papers*

- **[MUVOD: A Novel Multi-view Video Object Segmentation Dataset and A
  Benchmark for 3D Segmentation](https://arxiv.org/abs/2507.07519v1)**  
  Authors: Bangning Wei, Joshua Maraval, Meriem Outtas, Kidiyo Kpalma, Nicolas Ramin, Lu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07519v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://volumetric-repository.labs.b-com.com/#/muvod.)  
  Keywords: dynamic, motion, understanding, segmentation, outdoor, ar, gaussian splatting, 3d gaussian, 4d, nerf  
- **[SD-GS: Structured Deformable 3D Gaussians for Efficient Dynamic Scene
  Reconstruction](https://arxiv.org/abs/2507.07465v1)**  
  Authors: Wei Yao, Shuzhao Xie, Letian Li, Weixiang Zhang, Zhixin Lai, Shiqi Dai, Ke Zhang, Zhi Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07465v1.pdf)  
  Keywords: dynamic, motion, efficient, ar, gaussian splatting, compact, 3d gaussian, 4d, deformation  
- **[Enhancing non-Rigid 3D Model Deformations Using Mesh-based Gaussian
  Splatting](https://arxiv.org/abs/2507.07000v1)**  
  Authors: Wijayathunga W. M. R. D. B  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07000v1.pdf)  
  Keywords: face, animation, ar, gaussian splatting, 3d gaussian, fast, deformation  
- **[ClipGS: Clippable Gaussian Splatting for Interactive Cinematic
  Visualization of Volumetric Medical Data](https://arxiv.org/abs/2507.06647v1)**  
  Authors: Chengkun Li, Yuqi Tong, Kai Chen, Zhenya Yang, Ruiyang Li, Shi Qiu, Jason Ying-Kuen Chan, Pheng-Ann Heng, Qi Dou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06647v1.pdf)  
  Keywords: dynamic, understanding, ar, gaussian splatting, medical, deformation  
- **[LighthouseGS: Indoor Structure-aware 3D Gaussian Splatting for
  Panorama-Style Mobile Captures](https://arxiv.org/abs/2507.06109v1)**  
  Authors: Seungoh Han, Jaehoon Jang, Hyunsu Kim, Jaeheung Surh, Junhyung Kwak, Hyowon Ha, Kyungdon Joo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06109v1.pdf)  
  Keywords: high-fidelity, motion, ar, gaussian splatting, 3d gaussian, geometry  
- **[VisualSpeaker: Visually-Guided 3D Avatar Lip Synthesis](https://arxiv.org/abs/2507.06060v1)**  
  Authors: Alexandre Symeonidis-Herzig, Özge Mercanoğlu Sincan, Richard Bowden  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06060v1.pdf)  
  Keywords: high-fidelity, animation, ar, gaussian splatting, avatar, human, recognition, 3d gaussian  
- **[D-FCGS: Feedforward Compression of Dynamic Gaussian Splatting for
  Free-Viewpoint Videos](https://arxiv.org/abs/2507.05859v1)**  
  Authors: Wenkang Zhang, Yan Zhao, Qiang Wang, Li Song, Zhengxue Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.05859v1.pdf)  
  Keywords: dynamic, high-fidelity, motion, efficient, ar, gaussian splatting, 3d gaussian, compression  
- **[DreamArt: Generating Interactable Articulated Objects from a Single
  Image](https://arxiv.org/abs/2507.05763v1)**  
  Authors: Ruijie Lu, Yu Liu, Jiaxiang Tang, Junfeng Ni, Yuxiang Wang, Diwen Wan, Gang Zeng, Yixin Chen, Siyuan Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.05763v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://dream-art-0.github.io/DreamArt/.)  
  Keywords: high-fidelity, motion, face, segmentation, ar, gaussian splatting, vr, geometry, nerf  
- **[InterGSEdit: Interactive 3D Gaussian Splatting Editing with 3D
  Geometry-Consistent Attention Prior](https://arxiv.org/abs/2507.04961v1)**  
  Authors: Minghao Wen, Shengjie Wu, Kangkan Wang, Dong Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.04961v1.pdf)  
  Keywords: high-fidelity, ar, gaussian splatting, semantic, 3d gaussian, geometry, deformation  
- **[A3FR: Agile 3D Gaussian Splatting with Incremental Gaze Tracked Foveated
  Rendering in Virtual Reality](https://arxiv.org/abs/2507.04147v1)**  
  Authors: Shuo Xin, Haiyu Wang, Sai Qian Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.04147v1.pdf)  
  Keywords: dynamic, efficient rendering, face, tracking, efficient, head, neural rendering, gaussian splatting, ar, vr, human, 3d gaussian  

### Few-shot

*Showing the latest 50 out of 69 papers*

- **[Particle-Grid Neural Dynamics for Learning Deformable Object Models from
  RGB-D Videos](https://arxiv.org/abs/2506.15680v1)**  
  Authors: Kaifeng Zhang, Baoyu Li, Kris Hauser, Yunzhu Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.15680v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://kywind.github.io/pgnd)  
  Keywords: sparse-view, dynamic, motion, ar, gaussian splatting  
- **[PointGS: Point Attention-Aware Sparse View Synthesis with Gaussian
  Splatting](https://arxiv.org/abs/2506.10335v1)**  
  Authors: Lintao Xiang, Hongpei Zheng, Yating Huang, Qijun Yang, Hujun Yin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.10335v1.pdf)  
  Keywords: nerf, few-shot, ar, gaussian splatting, lightweight, 3d gaussian, sparse view  
- **[UniForward: Unified 3D Scene and Semantic Field Reconstruction via
  Feed-Forward Gaussian Splatting from Only Sparse-View Images](https://arxiv.org/abs/2506.09378v1)**  
  Authors: Qijian Tian, Xin Tan, Jingyu Gong, Yuan Xie, Lizhuang Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.09378v1.pdf)  
  Keywords: sparse-view, understanding, segmentation, ar, gaussian splatting, semantic, 3d gaussian  
- **[ProSplat: Improved Feed-Forward 3D Gaussian Splatting for Wide-Baseline
  Sparse Views](https://arxiv.org/abs/2506.07670v1)**  
  Authors: Xiaohan Lu, Jiaye Fu, Jiaqi Zhang, Zetian Song, Chuanmin Jia, Siwei Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.07670v1.pdf)  
  Keywords: high-fidelity, ar, gaussian splatting, 3d gaussian, sparse view  
- **[Learning Fine-Grained Geometry for Sparse-View Splatting via Cascade
  Depth Loss](https://arxiv.org/abs/2505.22279v1)**  
  Authors: Wenjun Lu, Haodong Chen, Anqi Yi, Yuk Ying Chung, Zhiyong Wang, Kun Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.22279v1.pdf)  
  Keywords: sparse-view, efficient, ar, gaussian splatting, 3d gaussian, geometry, nerf  
- **[Intern-GS: Vision Model Guided Sparse-View 3D Gaussian Splatting](https://arxiv.org/abs/2505.20729v1)**  
  Authors: Xiangyu Sun, Runnan Chen, Mingming Gong, Dong Xu, Tongliang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.20729v1.pdf)  
  Keywords: sparse-view, motion, face, ar, gaussian splatting, 3d gaussian  
- **[Sparse2DGS: Sparse-View Surface Reconstruction using 2D Gaussian
  Splatting with Dense Point Cloud](https://arxiv.org/abs/2505.19854v2)**  
  Authors: Natsuki Takama, Shintaro Ito, Koichi Ito, Hwann-Tzong Chen, Takafumi Aoki  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.19854v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://gsisaoki.github.io/SPARSE2DGS/)  
  Keywords: sparse-view, 3d reconstruction, motion, face, ar, gaussian splatting, fast  
- **[Improving Novel view synthesis of 360$^\circ$ Scenes in Extremely Sparse
  Views by Jointly Training Hemisphere Sampled Synthetic Images](https://arxiv.org/abs/2505.19264v1)**  
  Authors: Guangan Chen, Anh Minh Truong, Hanhe Lin, Michiel Vlaminck, Wilfried Philips, Hiep Luong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.19264v1.pdf)  
  Keywords: sparse-view, motion, ar, gaussian splatting, 3d gaussian, sparse view  
- **[SHaDe: Compact and Consistent Dynamic 3D Reconstruction via Tri-Plane
  Deformation and Latent Diffusion](https://arxiv.org/abs/2505.16535v1)**  
  Authors: Asrar Alruwayqi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.16535v1.pdf)  
  Keywords: sparse-view, dynamic, 3d reconstruction, motion, efficient, head, ar, gaussian splatting, compact, 4d, deformation  
- **[RUSplatting: Robust 3D Gaussian Splatting for Sparse-View Underwater
  Scene Reconstruction](https://arxiv.org/abs/2505.15737v1)**  
  Authors: Zhuodong Jiang, Haoran Wang, Guoxi Huang, Brett Seymour, Nantheera Anantrasirichai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.15737v1.pdf)  
  Keywords: sparse-view, high-fidelity, robotics, ar, gaussian splatting, 3d gaussian  

### Geometry Reconstruction

*Showing the latest 50 out of 315 papers*

- **[LighthouseGS: Indoor Structure-aware 3D Gaussian Splatting for
  Panorama-Style Mobile Captures](https://arxiv.org/abs/2507.06109v1)**  
  Authors: Seungoh Han, Jaehoon Jang, Hyunsu Kim, Jaeheung Surh, Junhyung Kwak, Hyowon Ha, Kyungdon Joo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06109v1.pdf)  
  Keywords: high-fidelity, motion, ar, gaussian splatting, 3d gaussian, geometry  
- **[Reflections Unlock: Geometry-Aware Reflection Disentanglement in 3D
  Gaussian Splatting for Photorealistic Scenes Rendering](https://arxiv.org/abs/2507.06103v1)**  
  Authors: Jiayi Song, Zihan Ye, Qingyuan Zhou, Weidong Yang, Ben Fei, Jingyi Xu, Ying He, Wanli Ouyang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06103v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ref-unlock.github.io/.)  
  Keywords: face, efficient, ar, gaussian splatting, reflection, 3d gaussian, geometry, nerf  
- **[DreamArt: Generating Interactable Articulated Objects from a Single
  Image](https://arxiv.org/abs/2507.05763v1)**  
  Authors: Ruijie Lu, Yu Liu, Jiaxiang Tang, Junfeng Ni, Yuxiang Wang, Diwen Wan, Gang Zeng, Yixin Chen, Siyuan Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.05763v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://dream-art-0.github.io/DreamArt/.)  
  Keywords: high-fidelity, motion, face, segmentation, ar, gaussian splatting, vr, geometry, nerf  
- **[A Probabilistic Approach to Uncertainty Quantification Leveraging 3D
  Geometry](https://arxiv.org/abs/2507.06269v1)**  
  Authors: Rushil Desai, Frederik Warburg, Trevor Darrell, Marissa Ramirez de Chanlatte  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06269v1.pdf)  
  Keywords: face, efficient, ar, gaussian splatting, 3d gaussian, geometry, nerf  
- **[InterGSEdit: Interactive 3D Gaussian Splatting Editing with 3D
  Geometry-Consistent Attention Prior](https://arxiv.org/abs/2507.04961v1)**  
  Authors: Minghao Wen, Shengjie Wu, Kangkan Wang, Dong Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.04961v1.pdf)  
  Keywords: high-fidelity, ar, gaussian splatting, semantic, 3d gaussian, geometry, deformation  
- **[Gbake: Baking 3D Gaussian Splats into Reflection Probes](https://arxiv.org/abs/2507.02257v1)**  
  Authors: Stephen Pasch, Joel K. Salzman, Changxi Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.02257v1.pdf)  
  Keywords: lighting, ar, gaussian splatting, reflection, 3d gaussian, mapping, geometry  
- **[GDGS: 3D Gaussian Splatting Via Geometry-Guided Initialization And
  Dynamic Density Control](https://arxiv.org/abs/2507.00363v1)**  
  Authors: Xingjun Wang, Lianlei Shan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.00363v1.pdf)  
  Keywords: dynamic, high-fidelity, face, ar, gaussian splatting, 3d gaussian, fast, real-time rendering, geometry  
- **[MILo: Mesh-In-the-Loop Gaussian Splatting for Detailed and Efficient
  Surface Reconstruction](https://arxiv.org/abs/2506.24096v1)**  
  Authors: Antoine Guédon, Diego Gomez, Nissim Maruani, Bingchen Gong, George Drettakis, Maks Ovsjanikov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.24096v1.pdf)  
  Keywords: face, efficient, animation, ar, gaussian splatting, 3d gaussian, fast, geometry  
- **[GaVS: 3D-Grounded Video Stabilization via Temporally-Consistent Local
  Reconstruction and Rendering](https://arxiv.org/abs/2506.23957v1)**  
  Authors: Zinuo You, Stamatios Georgoulis, Anpei Chen, Siyu Tang, Dengxin Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.23957v1.pdf)  
  Keywords: dynamic, motion, ar, gaussian splatting, geometry  
- **[AttentionGS: Towards Initialization-Free 3D Gaussian Splatting via
  Structural Attention](https://arxiv.org/abs/2506.23611v1)**  
  Authors: Ziao Liu, Zhenjia Li, Yifeng Shi, Xiangang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.23611v1.pdf)  
  Keywords: 3d reconstruction, motion, efficient rendering, face, efficient, ar, gaussian splatting, 3d gaussian, nerf  

### Large Scene

*Showing the latest 50 out of 65 papers*

- **[MUVOD: A Novel Multi-view Video Object Segmentation Dataset and A
  Benchmark for 3D Segmentation](https://arxiv.org/abs/2507.07519v1)**  
  Authors: Bangning Wei, Joshua Maraval, Meriem Outtas, Kidiyo Kpalma, Nicolas Ramin, Lu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07519v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://volumetric-repository.labs.b-com.com/#/muvod.)  
  Keywords: dynamic, motion, understanding, segmentation, outdoor, ar, gaussian splatting, 3d gaussian, 4d, nerf  
- **[3DGS_LSR:Large_Scale Relocation for Autonomous Driving Based on 3D
  Gaussian Splatting](https://arxiv.org/abs/2507.05661v1)**  
  Authors: Haitao Lu, Haijier Chen, Haoze Liu, Shoujian Zhang, Bo Xu, Ziao Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.05661v1.pdf)  
  Keywords: autonomous driving, outdoor, ar, gaussian splatting, localization, 3d gaussian, mapping  
- **[ArmGS: Composite Gaussian Appearance Refinement for Modeling Dynamic
  Urban Environments](https://arxiv.org/abs/2507.03886v1)**  
  Authors: Guile Wu, Dongfeng Bai, Bingbing Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.03886v1.pdf)  
  Keywords: dynamic, urban scene, high-fidelity, autonomous driving, ar, gaussian splatting, 3d gaussian, real-time rendering  
- **[Outdoor Monocular SLAM with Global Scale-Consistent 3D Gaussian
  Pointmaps](https://arxiv.org/abs/2507.03737v1)**  
  Authors: Chong Cheng, Sicheng Yu, Zijian Wang, Yifan Zhou, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.03737v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://3dagentworld.github.io/S3PO-GS/.)  
  Keywords: dynamic, high-fidelity, tracking, outdoor, ar, gaussian splatting, slam, 3d gaussian, mapping  
- **[TVG-SLAM: Robust Gaussian Splatting SLAM with Tri-view Geometric
  Constraints](https://arxiv.org/abs/2506.23207v1)**  
  Authors: Zhen Tan, Xieyuanli Chen, Lei Feng, Yangbing Ge, Shuaifeng Zhi, Jiaxiong Liu, Dewen Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.23207v1.pdf)  
  Keywords: dynamic, high-fidelity, tracking, lighting, outdoor, ar, gaussian splatting, slam, 3d gaussian, mapping, geometry, illumination  
- **[BézierGS: Dynamic Urban Scene Reconstruction with Bézier Curve
  Gaussian Splatting](https://arxiv.org/abs/2506.22099v3)**  
  Authors: Zipei Ma, Junzhe Jiang, Yurui Chen, Li Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.22099v3.pdf)  
  Keywords: dynamic, urban scene, motion, autonomous driving, ar, gaussian splatting  
- **[ICP-3DGS: SfM-free 3D Gaussian Splatting for Large-scale Unbounded
  Scenes](https://arxiv.org/abs/2506.21629v1)**  
  Authors: Chenhao Zhang, Yezhi Shen, Fengqing Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.21629v1.pdf)  
  Keywords: motion, outdoor, neural rendering, gaussian splatting, ar, 3d gaussian, nerf  
- **[GRAND-SLAM: Local Optimization for Globally Consistent Large-Scale
  Multi-Agent Gaussian SLAM](https://arxiv.org/abs/2506.18885v1)**  
  Authors: Annika Thomas, Aneesa Sonawalla, Alex Rose, Jonathan P. How  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.18885v1.pdf)  
  Keywords: tracking, outdoor, ar, gaussian splatting, slam, 3d gaussian  
- **[3D Gaussian Splatting for Fine-Detailed Surface Reconstruction in
  Large-Scale Scene](https://arxiv.org/abs/2506.17636v1)**  
  Authors: Shihan Chen, Zhaojin Li, Zeyu Chen, Qingsong Yan, Gaoyang Shen, Ran Duan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.17636v1.pdf)  
  Keywords: dynamic, high-fidelity, face, autonomous driving, outdoor, efficient, ar, gaussian splatting, survey, 3d gaussian, nerf  
- **[Multiview Geometric Regularization of Gaussian Splatting for Accurate
  Radiance Fields](https://arxiv.org/abs/2506.13508v1)**  
  Authors: Jungeon Kim, Geonsoo Park, Seungyong Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.13508v1.pdf)  
  Keywords: outdoor, ar, gaussian splatting, 3d gaussian, geometry  

### Model Compression

*Showing the latest 50 out of 397 papers*

- **[RTR-GS: 3D Gaussian Splatting for Inverse Rendering with Radiance
  Transfer and Reflection](https://arxiv.org/abs/2507.07733v1)**  
  Authors: Yongyang Zhou, Fang-Lue Zhang, Zichen Wang, Lei Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07733v1.pdf)  
  Keywords: lighting, efficient, ar, gaussian splatting, reflection, 3d gaussian, relighting  
- **[SD-GS: Structured Deformable 3D Gaussians for Efficient Dynamic Scene
  Reconstruction](https://arxiv.org/abs/2507.07465v1)**  
  Authors: Wei Yao, Shuzhao Xie, Letian Li, Weixiang Zhang, Zhixin Lai, Shiqi Dai, Ke Zhang, Zhi Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07465v1.pdf)  
  Keywords: dynamic, motion, efficient, ar, gaussian splatting, compact, 3d gaussian, 4d, deformation  
- **[FlexGaussian: Flexible and Cost-Effective Training-Free Compression for
  3D Gaussian Splatting](https://arxiv.org/abs/2507.06671v1)**  
  Authors: Boyuan Tian, Qizhe Gao, Siran Xianyu, Xiaotong Cui, Minjia Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06671v1.pdf)  
  Keywords: ar, gaussian splatting, 3d gaussian, fast, compression  
- **[LangSplatV2: High-dimensional 3D Language Gaussian Splatting with 450+
  FPS](https://arxiv.org/abs/2507.07136v1)**  
  Authors: Wanhua Li, Yujie Zhao, Minghan Qin, Yang Liu, Yuanhao Cai, Chuang Gan, Hanspeter Pfister  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07136v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://langsplat-v2.github.io.)  
  Keywords: high quality, efficient, ar, gaussian splatting, semantic, fast  
- **[Reflections Unlock: Geometry-Aware Reflection Disentanglement in 3D
  Gaussian Splatting for Photorealistic Scenes Rendering](https://arxiv.org/abs/2507.06103v1)**  
  Authors: Jiayi Song, Zihan Ye, Qingyuan Zhou, Weidong Yang, Ben Fei, Jingyi Xu, Ying He, Wanli Ouyang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06103v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ref-unlock.github.io/.)  
  Keywords: face, efficient, ar, gaussian splatting, reflection, 3d gaussian, geometry, nerf  
- **[D-FCGS: Feedforward Compression of Dynamic Gaussian Splatting for
  Free-Viewpoint Videos](https://arxiv.org/abs/2507.05859v1)**  
  Authors: Wenkang Zhang, Yan Zhao, Qiang Wang, Li Song, Zhengxue Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.05859v1.pdf)  
  Keywords: dynamic, high-fidelity, motion, efficient, ar, gaussian splatting, 3d gaussian, compression  
- **[A Probabilistic Approach to Uncertainty Quantification Leveraging 3D
  Geometry](https://arxiv.org/abs/2507.06269v1)**  
  Authors: Rushil Desai, Frederik Warburg, Trevor Darrell, Marissa Ramirez de Chanlatte  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06269v1.pdf)  
  Keywords: face, efficient, ar, gaussian splatting, 3d gaussian, geometry, nerf  
- **[Mastering Regional 3DGS: Locating, Initializing, and Editing with
  Diverse 2D Priors](https://arxiv.org/abs/2507.05426v1)**  
  Authors: Lanqing Guo, Yufei Wang, Hezhen Hu, Yan Zheng, Yeying Jin, Siyu Huang, Zhangyang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.05426v1.pdf)  
  Keywords: efficient, ar, gaussian splatting, localization, semantic, 3d gaussian  
- **[A3FR: Agile 3D Gaussian Splatting with Incremental Gaze Tracked Foveated
  Rendering in Virtual Reality](https://arxiv.org/abs/2507.04147v1)**  
  Authors: Shuo Xin, Haiyu Wang, Sai Qian Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.04147v1.pdf)  
  Keywords: dynamic, efficient rendering, face, tracking, efficient, head, neural rendering, gaussian splatting, ar, vr, human, 3d gaussian  
- **[Gaussian-LIC2: LiDAR-Inertial-Camera Gaussian Splatting SLAM](https://arxiv.org/abs/2507.04004v2)**  
  Authors: Xiaolei Lang, Jiajun Lv, Kai Tang, Laijian Li, Jianxin Huang, Lina Liu, Yong Liu, Xingxing Zuo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.04004v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://xingxingzuo.github.io/gaussian_lic2.)  
  Keywords: ar, gaussian splatting, lightweight, slam, 3d gaussian, fast  

### Quality Enhancement

*Showing the latest 50 out of 163 papers*

- **[LangSplatV2: High-dimensional 3D Language Gaussian Splatting with 450+
  FPS](https://arxiv.org/abs/2507.07136v1)**  
  Authors: Wanhua Li, Yujie Zhao, Minghan Qin, Yang Liu, Yuanhao Cai, Chuang Gan, Hanspeter Pfister  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07136v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://langsplat-v2.github.io.)  
  Keywords: high quality, efficient, ar, gaussian splatting, semantic, fast  
- **[LighthouseGS: Indoor Structure-aware 3D Gaussian Splatting for
  Panorama-Style Mobile Captures](https://arxiv.org/abs/2507.06109v1)**  
  Authors: Seungoh Han, Jaehoon Jang, Hyunsu Kim, Jaeheung Surh, Junhyung Kwak, Hyowon Ha, Kyungdon Joo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06109v1.pdf)  
  Keywords: high-fidelity, motion, ar, gaussian splatting, 3d gaussian, geometry  
- **[VisualSpeaker: Visually-Guided 3D Avatar Lip Synthesis](https://arxiv.org/abs/2507.06060v1)**  
  Authors: Alexandre Symeonidis-Herzig, Özge Mercanoğlu Sincan, Richard Bowden  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06060v1.pdf)  
  Keywords: high-fidelity, animation, ar, gaussian splatting, avatar, human, recognition, 3d gaussian  
- **[D-FCGS: Feedforward Compression of Dynamic Gaussian Splatting for
  Free-Viewpoint Videos](https://arxiv.org/abs/2507.05859v1)**  
  Authors: Wenkang Zhang, Yan Zhao, Qiang Wang, Li Song, Zhengxue Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.05859v1.pdf)  
  Keywords: dynamic, high-fidelity, motion, efficient, ar, gaussian splatting, 3d gaussian, compression  
- **[DreamArt: Generating Interactable Articulated Objects from a Single
  Image](https://arxiv.org/abs/2507.05763v1)**  
  Authors: Ruijie Lu, Yu Liu, Jiaxiang Tang, Junfeng Ni, Yuxiang Wang, Diwen Wan, Gang Zeng, Yixin Chen, Siyuan Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.05763v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://dream-art-0.github.io/DreamArt/.)  
  Keywords: high-fidelity, motion, face, segmentation, ar, gaussian splatting, vr, geometry, nerf  
- **[SegmentDreamer: Towards High-fidelity Text-to-3D Synthesis with
  Segmented Consistency Trajectory Distillation](https://arxiv.org/abs/2507.05256v1)**  
  Authors: Jiahao Zhu, Zixuan Chen, Guangcong Wang, Xiaohua Xie, Yi Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.05256v1.pdf)  
  Keywords: 3d gaussian, high-fidelity, ar, gaussian splatting  
- **[InterGSEdit: Interactive 3D Gaussian Splatting Editing with 3D
  Geometry-Consistent Attention Prior](https://arxiv.org/abs/2507.04961v1)**  
  Authors: Minghao Wen, Shengjie Wu, Kangkan Wang, Dong Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.04961v1.pdf)  
  Keywords: high-fidelity, ar, gaussian splatting, semantic, 3d gaussian, geometry, deformation  
- **[ArmGS: Composite Gaussian Appearance Refinement for Modeling Dynamic
  Urban Environments](https://arxiv.org/abs/2507.03886v1)**  
  Authors: Guile Wu, Dongfeng Bai, Bingbing Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.03886v1.pdf)  
  Keywords: dynamic, urban scene, high-fidelity, autonomous driving, ar, gaussian splatting, 3d gaussian, real-time rendering  
- **[Outdoor Monocular SLAM with Global Scale-Consistent 3D Gaussian
  Pointmaps](https://arxiv.org/abs/2507.03737v1)**  
  Authors: Chong Cheng, Sicheng Yu, Zijian Wang, Yifan Zhou, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.03737v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://3dagentworld.github.io/S3PO-GS/.)  
  Keywords: dynamic, high-fidelity, tracking, outdoor, ar, gaussian splatting, slam, 3d gaussian, mapping  
- **[HyperGaussians: High-Dimensional Gaussian Splatting for High-Fidelity
  Animatable Face Avatars](https://arxiv.org/abs/2507.02803v2)**  
  Authors: Gent Serifi, Marcel C. Bühler  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.02803v2.pdf)  
  Keywords: high-fidelity, face, lighting, ar, gaussian splatting, avatar, reflection, 3d gaussian, fast, deformation  

### Ray Tracing

- **[RaRa Clipper: A Clipper for Gaussian Splatting Based on Ray Tracer and
  Rasterizer](https://arxiv.org/abs/2506.20202v1)**  
  Authors: Da Li, Donggang Jia, Yousef Rajeh, Dominik Engel, Ivan Viola  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.20202v1.pdf)  
  Keywords: high-fidelity, efficient, ar, gaussian splatting, real-time rendering, ray tracing  
- **[DNF-Avatar: Distilling Neural Fields for Real-time Animatable Avatar
  Relighting](https://arxiv.org/abs/2504.10486v1)**  
  Authors: Zeren Jiang, Shaofei Wang, Siyu Tang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.10486v1.pdf)  
  Keywords: lighting, ar, relightable, gaussian splatting, avatar, human, relighting, fast, ray tracing, shadow, geometry  
- **[Stochastic Ray Tracing of Transparent 3D Gaussians](https://arxiv.org/abs/2504.06598v3)**  
  Authors: Xin Sun, Iliyan Georgiev, Yun Fei, Miloš Hašan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.06598v3.pdf)  
  Keywords: efficient rendering, lighting, efficient, acceleration, gaussian splatting, ar, 3d gaussian, relighting, ray tracing  
- **[3D Gaussian Particle Approximation of VDB Datasets: A Study for
  Scientific Visualization](https://arxiv.org/abs/2504.04857v2)**  
  Authors: Isha Sharma, Dieter Schmalstieg  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.04857v2.pdf)  
  Keywords: dynamic, ray marching, efficient, animation, acceleration, gaussian splatting, ar, compact, 3d gaussian  
- **[3D Gaussian Inverse Rendering with Approximated Global Illumination](https://arxiv.org/abs/2504.01358v1)**  
  Authors: Zirui Wu, Jianteng Chen, Laijian Li, Shaoteng Wu, Zhikai Zhu, Kang Xu, Martin R. Oswald, Jie Song  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.01358v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://wuzirui.github.io/gs-ssr.)  
  Keywords: global illumination, face, lighting, efficient, ar, gaussian splatting, 3d gaussian, real-time rendering, ray tracing, illumination  
- **[REdiSplats: Ray Tracing for Editable Gaussian Splatting](https://arxiv.org/abs/2503.12284v1)**  
  Authors: Krzysztof Byrski, Grzegorz Wilczyński, Weronika Smolak-Dyżewska, Piotr Borycki, Dawid Baran, Sławomir Tadeja, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.12284v1.pdf)  
  Keywords: neural rendering, gaussian splatting, ar, reflection, 3d gaussian, fast, ray tracing, shadow  
- **[MeshSplats: Mesh-Based Rendering with Gaussian Splatting Initialization](https://arxiv.org/abs/2502.07754v1)**  
  Authors: Rafał Tobiasz, Grzegorz Wilczyński, Marcin Mazur, Sławomir Tadeja, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.07754v1.pdf)  
  Keywords: face, lighting, gaussian splatting, reflection, ray tracing, shadow  
- **[Scalable 3D Gaussian Splatting-Based RF Signal Spatial Propagation
  Modeling](https://arxiv.org/abs/2502.01826v1)**  
  Authors: Kang Yang, Gaofeng Dong, Sijie Ji, Wan Du, Mani Srivastava  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.01826v1.pdf)  
  Keywords: ar, gaussian splatting, survey, 3d gaussian, ray tracing  
- **[Radiant Foam: Real-Time Differentiable Ray Tracing](https://arxiv.org/abs/2502.01157v1)**  
  Authors: Shrisudhan Govindarajan, Daniel Rebain, Kwang Moo Yi, Andrea Tagliasacchi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.01157v1.pdf)  
  Keywords: efficient, acceleration, gaussian splatting, ar, reflection, light transport, ray tracing  
- **[RaySplats: Ray Tracing based Gaussian Splatting](https://arxiv.org/abs/2501.19196v1)**  
  Authors: Krzysztof Byrski, Marcin Mazur, Jacek Tabor, Tadeusz Dziarmaga, Marcin Kądziołka, Dawid Baran, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.19196v1.pdf)  
  Keywords: ar, gaussian splatting, reflection, 3d gaussian, ray tracing, shadow  

### Relighting

*Showing the latest 50 out of 108 papers*

- **[RTR-GS: 3D Gaussian Splatting for Inverse Rendering with Radiance
  Transfer and Reflection](https://arxiv.org/abs/2507.07733v1)**  
  Authors: Yongyang Zhou, Fang-Lue Zhang, Zichen Wang, Lei Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07733v1.pdf)  
  Keywords: lighting, efficient, ar, gaussian splatting, reflection, 3d gaussian, relighting  
- **[Seg-Wild: Interactive Segmentation based on 3D Gaussian Splatting for
  Unconstrained Image Collections](https://arxiv.org/abs/2507.07395v1)**  
  Authors: Yongtang Bao, Chengjie Tang, Yuze Wang, Haojie Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07395v1.pdf)  
  Keywords: segmentation, lighting, ar, gaussian splatting, 3d gaussian  
- **[Reflections Unlock: Geometry-Aware Reflection Disentanglement in 3D
  Gaussian Splatting for Photorealistic Scenes Rendering](https://arxiv.org/abs/2507.06103v1)**  
  Authors: Jiayi Song, Zihan Ye, Qingyuan Zhou, Weidong Yang, Ben Fei, Jingyi Xu, Ying He, Wanli Ouyang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06103v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ref-unlock.github.io/.)  
  Keywords: face, efficient, ar, gaussian splatting, reflection, 3d gaussian, geometry, nerf  
- **[HyperGaussians: High-Dimensional Gaussian Splatting for High-Fidelity
  Animatable Face Avatars](https://arxiv.org/abs/2507.02803v2)**  
  Authors: Gent Serifi, Marcel C. Bühler  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.02803v2.pdf)  
  Keywords: high-fidelity, face, lighting, ar, gaussian splatting, avatar, reflection, 3d gaussian, fast, deformation  
- **[Gbake: Baking 3D Gaussian Splats into Reflection Probes](https://arxiv.org/abs/2507.02257v1)**  
  Authors: Stephen Pasch, Joel K. Salzman, Changxi Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.02257v1.pdf)  
  Keywords: lighting, ar, gaussian splatting, reflection, 3d gaussian, mapping, geometry  
- **[SurgTPGS: Semantic 3D Surgical Scene Understanding with Text Promptable
  Gaussian Splatting](https://arxiv.org/abs/2506.23309v2)**  
  Authors: Yiming Huang, Long Bai, Beilei Cui, Kun Yuan, Guankun Wang, Mobarak I. Hoque, Nicolas Padoy, Nassir Navab, Hongliang Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.23309v2.pdf)  
  Keywords: 3d reconstruction, understanding, tracking, lighting, segmentation, ar, gaussian splatting, semantic, deformation  
- **[Endo-4DGX: Robust Endoscopic Scene Reconstruction and Illumination
  Correction with Gaussian Splatting](https://arxiv.org/abs/2506.23308v1)**  
  Authors: Yiming Huang, Long Bai, Beilei Cui, Yanheng Li, Tong Chen, Jie Wang, Jinlin Wu, Zhen Lei, Hongbin Liu, Hongliang Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.23308v1.pdf)  
  Keywords: dynamic, lighting, ar, gaussian splatting, 3d gaussian, 4d, illumination  
- **[TVG-SLAM: Robust Gaussian Splatting SLAM with Tri-view Geometric
  Constraints](https://arxiv.org/abs/2506.23207v1)**  
  Authors: Zhen Tan, Xieyuanli Chen, Lei Feng, Yangbing Ge, Shuaifeng Zhi, Jiaxiong Liu, Dewen Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.23207v1.pdf)  
  Keywords: dynamic, high-fidelity, tracking, lighting, outdoor, ar, gaussian splatting, slam, 3d gaussian, mapping, geometry, illumination  
- **[MADrive: Memory-Augmented Driving Scene Modeling](https://arxiv.org/abs/2506.21520v1)**  
  Authors: Polina Karpikova, Daniil Selikhanovych, Kirill Struminsky, Ruslan Musaev, Maria Golitsyna, Dmitry Baranchuk  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.21520v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yandex-research.github.io/madrive/)  
  Keywords: autonomous driving, lighting, ar, gaussian splatting, 3d gaussian, relighting  
- **[Micro-macro Gaussian Splatting with Enhanced Scalability for
  Unconstrained Scene Reconstruction](https://arxiv.org/abs/2506.13516v1)**  
  Authors: Yihui Li, Chengxin Lv, Hongyu Yang, Di Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.13516v1.pdf)  
  Keywords: 3d reconstruction, motion, ar, gaussian splatting, illumination  

### SLAM

*Showing the latest 50 out of 157 papers*

- **[3DGS_LSR:Large_Scale Relocation for Autonomous Driving Based on 3D
  Gaussian Splatting](https://arxiv.org/abs/2507.05661v1)**  
  Authors: Haitao Lu, Haijier Chen, Haoze Liu, Shoujian Zhang, Bo Xu, Ziao Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.05661v1.pdf)  
  Keywords: autonomous driving, outdoor, ar, gaussian splatting, localization, 3d gaussian, mapping  
- **[Mastering Regional 3DGS: Locating, Initializing, and Editing with
  Diverse 2D Priors](https://arxiv.org/abs/2507.05426v1)**  
  Authors: Lanqing Guo, Yufei Wang, Hezhen Hu, Yan Zheng, Yeying Jin, Siyu Huang, Zhangyang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.05426v1.pdf)  
  Keywords: efficient, ar, gaussian splatting, localization, semantic, 3d gaussian  
- **[A3FR: Agile 3D Gaussian Splatting with Incremental Gaze Tracked Foveated
  Rendering in Virtual Reality](https://arxiv.org/abs/2507.04147v1)**  
  Authors: Shuo Xin, Haiyu Wang, Sai Qian Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.04147v1.pdf)  
  Keywords: dynamic, efficient rendering, face, tracking, efficient, head, neural rendering, gaussian splatting, ar, vr, human, 3d gaussian  
- **[Gaussian-LIC2: LiDAR-Inertial-Camera Gaussian Splatting SLAM](https://arxiv.org/abs/2507.04004v2)**  
  Authors: Xiaolei Lang, Jiajun Lv, Kai Tang, Laijian Li, Jianxin Huang, Lina Liu, Yong Liu, Xingxing Zuo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.04004v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://xingxingzuo.github.io/gaussian_lic2.)  
  Keywords: ar, gaussian splatting, lightweight, slam, 3d gaussian, fast  
- **[Outdoor Monocular SLAM with Global Scale-Consistent 3D Gaussian
  Pointmaps](https://arxiv.org/abs/2507.03737v1)**  
  Authors: Chong Cheng, Sicheng Yu, Zijian Wang, Yifan Zhou, Hao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.03737v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://3dagentworld.github.io/S3PO-GS/.)  
  Keywords: dynamic, high-fidelity, tracking, outdoor, ar, gaussian splatting, slam, 3d gaussian, mapping  
- **[Gbake: Baking 3D Gaussian Splats into Reflection Probes](https://arxiv.org/abs/2507.02257v1)**  
  Authors: Stephen Pasch, Joel K. Salzman, Changxi Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.02257v1.pdf)  
  Keywords: lighting, ar, gaussian splatting, reflection, 3d gaussian, mapping, geometry  
- **[SurgTPGS: Semantic 3D Surgical Scene Understanding with Text Promptable
  Gaussian Splatting](https://arxiv.org/abs/2506.23309v2)**  
  Authors: Yiming Huang, Long Bai, Beilei Cui, Kun Yuan, Guankun Wang, Mobarak I. Hoque, Nicolas Padoy, Nassir Navab, Hongliang Ren  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.23309v2.pdf)  
  Keywords: 3d reconstruction, understanding, tracking, lighting, segmentation, ar, gaussian splatting, semantic, deformation  
- **[TVG-SLAM: Robust Gaussian Splatting SLAM with Tri-view Geometric
  Constraints](https://arxiv.org/abs/2506.23207v1)**  
  Authors: Zhen Tan, Xieyuanli Chen, Lei Feng, Yangbing Ge, Shuaifeng Zhi, Jiaxiong Liu, Dewen Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.23207v1.pdf)  
  Keywords: dynamic, high-fidelity, tracking, lighting, outdoor, ar, gaussian splatting, slam, 3d gaussian, mapping, geometry, illumination  
- **[VoteSplat: Hough Voting Gaussian Splatting for 3D Scene Understanding](https://arxiv.org/abs/2506.22799v1)**  
  Authors: Minchao Jiang, Shunyu Jia, Jiaming Gu, Xiaoyuan Lu, Guangming Zhu, Anqi Dong, Liang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.22799v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sy-ja.github.io/votesplat/)  
  Keywords: understanding, segmentation, ar, gaussian splatting, localization, semantic, 3d gaussian, real-time rendering  
- **[EndoFlow-SLAM: Real-Time Endoscopic SLAM with Flow-Constrained Gaussian
  Splatting](https://arxiv.org/abs/2506.21420v2)**  
  Authors: Taoyu Wu, Yiyi Miao, Zhuoxiao Li, Haocheng Zhao, Kang Dang, Jionglong Su, Limin Yu, Haoang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.21420v2.pdf)  
  Keywords: dynamic, 3d reconstruction, motion, face, efficient, ar, gaussian splatting, localization, slam, 3d gaussian, mapping  

### Scene Understanding

*Showing the latest 50 out of 188 papers*

- **[MUVOD: A Novel Multi-view Video Object Segmentation Dataset and A
  Benchmark for 3D Segmentation](https://arxiv.org/abs/2507.07519v1)**  
  Authors: Bangning Wei, Joshua Maraval, Meriem Outtas, Kidiyo Kpalma, Nicolas Ramin, Lu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07519v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://volumetric-repository.labs.b-com.com/#/muvod.)  
  Keywords: dynamic, motion, understanding, segmentation, outdoor, ar, gaussian splatting, 3d gaussian, 4d, nerf  
- **[Seg-Wild: Interactive Segmentation based on 3D Gaussian Splatting for
  Unconstrained Image Collections](https://arxiv.org/abs/2507.07395v1)**  
  Authors: Yongtang Bao, Chengjie Tang, Yuze Wang, Haojie Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07395v1.pdf)  
  Keywords: segmentation, lighting, ar, gaussian splatting, 3d gaussian  
- **[ClipGS: Clippable Gaussian Splatting for Interactive Cinematic
  Visualization of Volumetric Medical Data](https://arxiv.org/abs/2507.06647v1)**  
  Authors: Chengkun Li, Yuqi Tong, Kai Chen, Zhenya Yang, Ruiyang Li, Shi Qiu, Jason Ying-Kuen Chan, Pheng-Ann Heng, Qi Dou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06647v1.pdf)  
  Keywords: dynamic, understanding, ar, gaussian splatting, medical, deformation  
- **[LangSplatV2: High-dimensional 3D Language Gaussian Splatting with 450+
  FPS](https://arxiv.org/abs/2507.07136v1)**  
  Authors: Wanhua Li, Yujie Zhao, Minghan Qin, Yang Liu, Yuanhao Cai, Chuang Gan, Hanspeter Pfister  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.07136v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://langsplat-v2.github.io.)  
  Keywords: high quality, efficient, ar, gaussian splatting, semantic, fast  
- **[VisualSpeaker: Visually-Guided 3D Avatar Lip Synthesis](https://arxiv.org/abs/2507.06060v1)**  
  Authors: Alexandre Symeonidis-Herzig, Özge Mercanoğlu Sincan, Richard Bowden  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.06060v1.pdf)  
  Keywords: high-fidelity, animation, ar, gaussian splatting, avatar, human, recognition, 3d gaussian  
- **[DreamArt: Generating Interactable Articulated Objects from a Single
  Image](https://arxiv.org/abs/2507.05763v1)**  
  Authors: Ruijie Lu, Yu Liu, Jiaxiang Tang, Junfeng Ni, Yuxiang Wang, Diwen Wan, Gang Zeng, Yixin Chen, Siyuan Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.05763v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://dream-art-0.github.io/DreamArt/.)  
  Keywords: high-fidelity, motion, face, segmentation, ar, gaussian splatting, vr, geometry, nerf  
- **[Mastering Regional 3DGS: Locating, Initializing, and Editing with
  Diverse 2D Priors](https://arxiv.org/abs/2507.05426v1)**  
  Authors: Lanqing Guo, Yufei Wang, Hezhen Hu, Yan Zheng, Yeying Jin, Siyu Huang, Zhangyang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.05426v1.pdf)  
  Keywords: efficient, ar, gaussian splatting, localization, semantic, 3d gaussian  
- **[InterGSEdit: Interactive 3D Gaussian Splatting Editing with 3D
  Geometry-Consistent Attention Prior](https://arxiv.org/abs/2507.04961v1)**  
  Authors: Minghao Wen, Shengjie Wu, Kangkan Wang, Dong Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.04961v1.pdf)  
  Keywords: high-fidelity, ar, gaussian splatting, semantic, 3d gaussian, geometry, deformation  
- **[ArtGS:3D Gaussian Splatting for Interactive Visual-Physical Modeling and
  Manipulation of Articulated Objects](https://arxiv.org/abs/2507.02600v1)**  
  Authors: Qiaojun Yu, Xibin Yuan, Yu jiang, Junting Chen, Dongzhe Zheng, Ce Hao, Yang You, Yixing Chen, Yao Mu, Liu Liu, Cewu Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.02600v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sites.google.com/view/artgs/home)  
  Keywords: dynamic, motion, understanding, robotics, efficient, ar, gaussian splatting, semantic, 3d gaussian  
- **[VISTA: Open-Vocabulary, Task-Relevant Robot Exploration with Online
  Semantic Gaussian Splatting](https://arxiv.org/abs/2507.01125v1)**  
  Authors: Keiko Nagami, Timothy Chen, Javier Yu, Ola Shorinwa, Maximilian Adang, Carlyn Dougherty, Eric Cristofalo, Mac Schwager  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2507.01125v1.pdf)  
  Keywords: efficient, ar, gaussian splatting, semantic, 3d gaussian  



## Classic Papers
- **[3D Gaussian Splatting for Real-Time Radiance Field Rendering](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/)** (SIGGRAPH 2023)  
  Authors: Bernhard Kerbl, Georgios Kopanas, Thomas Leimkühler, George Drettakis  
  Code: 🔗 [GitHub](https://github.com/graphdeco-inria/gaussian-splatting)  
  Keywords: Real-time Rendering, Neural Rendering, Point-based Graphics

## Open Source Projects
- [gaussian-splatting](https://github.com/graphdeco-inria/gaussian-splatting) - Original implementation of 3D Gaussian Splatting
- [taichi-3d-gaussian-splatting](https://github.com/wanmeihuali/taichi-3d-gaussian-splatting) - 3D Gaussian Splatting implemented in Taichi

## Applications
- [3D Gaussian Splatting for Real-Time Radiance Field Rendering Demo](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/) - Online Demo

## Tutorials & Blogs
- [Introduction to 3D Gaussian Splatting](https://github.com/graphdeco-inria/gaussian-splatting) - Official Tutorial

## 📋 Project Features

### 🛠️ Core Features
- **Configurable Search System**: Customize search keywords through `data/search_config.json` for targeted paper collection
- **Automated Paper Collection**: Daily automatic crawling of latest Gaussian Splatting related papers
- **Intelligent Classification System**: Automatically categorize papers into different topics (Acceleration, Applications, Dynamic Scenes, etc.)
- **Flexible Search Scopes**: Support for abstract-only, title-only, or combined searches
- **Cross-Platform Compatibility**: Support for Windows/Linux/macOS with automatic environment detection

### 🛠️ Technical Features
- **Robust Error Handling**: Multi-layer retry and fallback strategies ensure stable operation
- **GitHub Actions Integration**: Automated CI/CD workflows
- **Real-time Update Mechanism**: Daily automatic paper data updates
- **Detailed Logging**: Comprehensive logging for debugging and monitoring

### 📚 Documentation System
- **User Guides**: Detailed configuration and usage instructions
- **Update Logs**: [News.md](News.md) - Records all important updates
- **Validation Reports**: Automated testing and validation results

## 🚀 Quick Start

### Customize Search Keywords
Edit `data/search_config.json` to target specific research areas:

```json
{
  "search_config": {
    "both_abstract_and_title": [
      "gaussian splatting",
      "3d gaussian",
      "neural rendering"
    ],
    "abstract_only": [
      "volumetric rendering",
      "point cloud reconstruction"
    ],
    "title_only": [
      "real-time rendering",
      "3D reconstruction"
    ]
  }
}
```

### Run the Crawler
```bash
# Basic usage
python scripts/arxiv_crawler.py

# Custom number of papers
python scripts/arxiv_crawler.py --max-results 200

# Validate configuration
python scripts/validate_search_config.py
```

## Contribution Guidelines
Feel free to submit Pull Requests to improve this list! Please follow these formats:
- Paper entry format: `**[Paper Title](link)** - Brief description`
- Project entry format: `[Project Name](link) - Project description`

## License
[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/) 