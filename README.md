# AI-paper-follow
梳理每周最新多模态，LLMs,embodied AI相关论文

## update
**[2023/07/13]**

<details>
  <summary><b><a href="https://www.bakerlab.org/2023/07/11/diffusion-model-for-protein-design/">RFdiffusion: A generative model for protein design</a></b></summary>

  - *Affiliation*： University of Washington
  - *Keywords*： Diffusion models, Protein design 
  - *Summary*：The paper presents a novel deep learning framework, called RoseTTAFold Diffusion (RFdiffusion), for protein design. By fine-tuning the RoseTTAFold structure prediction network on protein structure denoising tasks, the authors achieve remarkable performance in designing various types of proteins, including binders, symmetric architectures, enzyme active site scaffolds, and therapeutic and metal-binding proteins. RFdiffusion enables the generation of complex and functional proteins from simple molecular specifications, demonstrating its potential for advancing protein design using deep learning techniques.

<details>
  <summary><b><a href="https://arxiv.org/pdf/2307.04964.pdf">Emu: An Open Multimodal Generalist</a></b></summary>
   - *Affiliation*： BAAI
  - *Keywords*：  Reinforcement Learning from Human Feedback (RLHF), Proximal Policy Optimization (PPO)
  - *Summary*：This article starts with an introduction to Large Language Models (LLMs) and their role in the advancement of artificial general intelligence. The authors then discuss relevant research related to reinforcement learning from human feedback (RLHF), a key methodology used in training these models. They delve into reward modeling, a component of RLHF that is critical for ensuring the models' helpfulness and harmlessness. The authors explore the Proximal Policy Optimization (PPO) algorithm, a reinforcement learning method frequently used in RLHF to optimize the models' outputs.

Following this, they provide evaluations and discussions around their work, including an analysis of the reward distribution under PPO training. This part likely involves an examination of how rewards are distributed during the learning process and how it impacts the effectiveness of the PPO training. Further, they conduct supplementary experiments focused on hyperparameter tuning, a process that involves adjusting various parameters in the learning algorithm to optimize model performance.

Lastly, the authors present comparison results on secondary tricks. While I can't provide specific details without the actual context, "secondary tricks" often refer to additional techniques or strategies used in machine learning to enhance the performance of the model or the efficiency of the learning process. The article concludes with the authors' intentions to contribute to the LLMs field by releasing technical reports, reward models, and PPO code.
