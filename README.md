# AI-paper-follow
梳理每周最新多模态，LLMs,embodied AI相关论文

## update
**[2023/07/13]**

<details>
  <summary><b><a href="https://www.bakerlab.org/2023/07/11/diffusion-model-for-protein-design/">RFdiffusion: A generative model for protein design</a></b></summary>

  - *Affiliation*： University of Washington
  - *Keywords*： Diffusion Models, Protein Design 
  - *Summary*： The paper presents a novel deep learning framework, called RoseTTAFold Diffusion (RFdiffusion), for protein design. By fine-tuning the RoseTTAFold structure prediction network on protein structure denoising tasks, the authors achieve remarkable performance in designing various types of proteins, including binders, symmetric architectures, enzyme active site scaffolds, and therapeutic and metal-binding proteins. RFdiffusion enables the generation of complex and functional proteins from simple molecular specifications, demonstrating its potential for advancing protein design using deep learning techniques.
</details>

<details>
  <summary><b><a href="https://arxiv.org/pdf/2307.04964.pdf">Secrets of RLHF in Large Language Models Part I: PPO</a></b></summary>
  
  - *Affiliation*： Fudan
  - *Keywords*： Reinforcement Learning from Human Feedback (RLHF), Proximal Policy Optimization (PPO)
  - *Summary*： This article starts with an introduction to Large Language Models (LLMs) and their role in the advancement of artificial general intelligence. The authors then discuss relevant research related to reinforcement learning from human feedback (RLHF), a key methodology used in training these models. They delve into reward modeling, a component of RLHF that is critical for ensuring the models' helpfulness and harmlessness. The authors explore the Proximal Policy Optimization (PPO) algorithm, a reinforcement learning method frequently used in RLHF to optimize the models' outputs.
</details>

<details>
  <summary><b><a href='https://github.com/baaivision/Emu'>Emu: An Open Multimodal Generalist</a></b></summary>
  
  - *Affiliation*： BAAI
  - *Keywords*：  Multimodal Generalist, Autoregressive Objective
  - *Summary*：This article introduces Emu, a sophisticated tool capable of generating both images and text in a multimodal context, using a unified autoregressive objective. Emu is versatile and serves as a general interface for tasks including image captioning, image/video question answering, text-to-image generation, and new abilities such as in-context text and image generation, and image blending.
</details>

<details>
  <summary><b><a href='https://arxiv.org/abs/2307.04767'>Semantic-SAM: Segment and Recognize Anything at Any Granularity</a></b></summary>
  
  - *Affiliation*： HKUST 
  - *Keywords*： Semantic-Awareness, Granularity-Abundance
  - *Summary*： This is a paper introducing Semantic-SAM, an advanced image segmentation model with semantic-awareness and multi-granularity capabilities. Semantic-SAM combines multiple datasets across three granularities and applies a decoupled classification process for objects and parts, allowing it to capture comprehensive semantic information. Furthermore, a multi-choice learning scheme during training allows for mask generation at multiple levels. The paper showcases the effectiveness of Semantic-SAM through various experiments and visualizations, and the authors plan to provide the code and a demo for further research and evaluation.
</details>

<details>
  <summary><b><a href='https://arxiv.org/abs/2307.04738'>RoCo: Dialectic Multi-Robot Collaboration with Large Language Models</a></b></summary>
  
  - *Affiliation*： Columbia University
  - *Keywords*： Multi-Robot Collaboration, Large Language Models (LLM)
  - *Summary*： This paper introduces a novel method of multi-robot collaboration, leveraging pre-trained large language models (LLMs) for both communication and path planning. The robots, equipped with LLMs, are able to discuss task strategies, create sub-task plans, and form waypoint paths for motion planning. Feedback from the environment aids in the improvement of plans and waypoints. To test this approach, RoCoBench, a benchmark for multi-robot collaboration scenarios, and a text-only dataset for agent representation and reasoning are introduced. The approach has demonstrated high success rates across all tasks in RoCoBench, including real-world scenarios where humans and robots can collaborate. Further resources, such as videos and code, are provided on the project website.
</details>

<details>
  <summary><b><a href='https://www.lerf.io/'>Language Embedded Radiance Fields</a></b></summary>
  
  - *Affiliation*： UC Berkeley
  - *Keywords*： 3D Language Field, CLIP Embeddings
  - *Summary*： This paper presents an optimized, dense, multi-scale 3D language field, known as LERF. This model utilizes volume rendering of CLIP embeddings supervised with multi-scale CLIP features across multi-view training images. The optimized LERF is capable of real-time extraction of 3D relevancy maps for language queries. It allows pixel-aligned queries of the distilled 3D CLIP embeddings, thus supporting long-tail open-vocabulary queries hierarchically across the volume, without the need for region proposals, masks, or fine-tuning.
</details>
