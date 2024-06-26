# Awesome VGM/VLM Unlearning

[![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/YuyangXueEd/Awesome-LLM-VLM-VGM-unlearning/blob/main/vlm.md)

A collection of papers and resources about Machine Unlearning on Vision Generative Models (VGMs) and Vision Language Models (VLMs).

Another collection of Vision Language Models and Vision Generative models can be found [here](readme.md).

---

## Background, Concerns, and Motivations

### Image Generation Ability

- [High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2112.10752), Rombach et al., **Stable Diffusion**, CVPR 2022, 2021-12
- [Midjourney](https://www.midjourney.com), Midjourney, **Business Image Generation Services**, Website, 2023

### Regulation and Compliance

- [Regulating ChatGPT and other large generative AI models](https://dl.acm.org/doi/abs/10.1145/3593013.3594067), Hacker et al., **Regulating ChatGPT**, FAccT 23, 2023-12

### Harmful Generation 

- [Safe Latent Diffusion: Mitigating Inappropriate Degeneration in Diffusion Models](https://arxiv.org/abs/2211.05105), Schramowski et al., **Safe Latent Diffusion**, [Code](https://github.com/ml-research/safe-latent-diffusion), CVPR 2023, 2022-11
- [Discovering Universal Semantic Triggers for Text-to-Image Synthesis](https://arxiv.org/abs/2402.07562), Zhai et al., **Universal Semantic Triggers**, ArXiv, 2024-02, [No Code Available]()

### Copyright Infringement

- [Users of Midjourney text-to-image site claim issues with new update](https://www.thestreet.com/technology/users-of-midjourney-text-to-image-site-claim-issues-with-new-update), **News**, The Street, 2023-12
- [Understanding and Mitigating Copying in Diffusion Models](https://proceedings.neurips.cc/paper_files/paper/2023/hash/9521b6e7f33e039e7d92e23f5e37bbf4-Abstract-Conference.html), Somepalli et al., [Code](https://github.com/somepago/DCR), NeurIPS 2023, 2023-05

### Bias, Fairness and Stereotypes

- [Exploiting Cultural Biases via Homoglyphs in Text-to-Image Synthesis](http://arxiv.org/abs/2209.08891), Struppek et al., **Homoglyphs**, [Code](https://github.com/LukasStruppek/Exploiting-Cultural-Biases-via-Homoglyphs?utm_source=catalyzex.com), Journal of Artificial Intelligence Research, 2022-09
- [Concept Decomposition for Visual Exploration and Inspiration](https://arxiv.org/abs/2305.18203), Vinker et al, **Concept Decomposition**, [Code](https://inspirationtree.github.io/inspirationtree/?utm_source=catalyzex.com), ACM Transactions on Graphics (TOG), 2023-05
- [On the Trustworthiness Landscape of State-of-the-art Generative Models: A Survey and Outlook](https://arxiv.org/abs/2307.16680), Fan et al., **Trustworthiness Survey**, ArXiv, 2023-07 
- [How AI reduces the world to stereotypes](https://restofworld.org/2023/ai-image-stereotypes/?utm_source=pocket-newtab-en-us), Turk, **News**, Rest of World, 2023-10
- [Security and Privacy on Generative Data in AIGC: A Survey](https://arxiv.org/abs/2309.09435), Wang et al., **Security and Privacy Survey**, ArXiv, 2023-09
- [Trustworthy Large Models in Vision: A Survey](https://arxiv.org/abs/2311.09680), Guo et al., **Trustworthy Vision Models Survey**, ArXiv, 2023-11
- [Multilingual Text-to-Image Generation Magnifies Gender Stereotypes and Prompt Engineering May Not Help You](http://arxiv.org/abs/2401.16092), Friedrich et al., **Bias in multilingual**, ArXiv, 2024-01


### Privacy and Security

- [Extracting Training Data from Diffusion Models](https://arxiv.org/abs/2301.13188), Carlini et al., **Diffusion Data Extraction**, 32nd USENIX, 2023-01

## Survey

- [Rethinking Machine Unlearning for Large Language Models](https://arxiv.org/abs/2402.08787), Liu et al., arXiv, 2024.02
- [Threats, Attacks, and Defenses in Machine Unlearning: A Survey](https://arxiv.org/abs/2403.13682), Liu et al., **Machine Unlearning Survey**, ArXiv, 2024-03
- [Machine Unlearning: Taxonomy, Metrics, Applications, Challenges, and Prospects](http://arxiv.org/abs/2403.08254), arXiv, 2024.03

## Methods

### Image-to-Image
- [Machine Unlearning for Image-to-Image Generative Models](https://arxiv.org/abs/2402.00351), Li et al, **Machine Unlearning for Image-to-Image**, [Code](https://github.com/jpmorganchase/l2l-generator-unlearning), ArXiv, 2024-02

### Prompt Engineering
- [Safe Latent Diffusion: Mitigating Inappropriate Degeneration in Diffusion Models](https://arxiv.org/abs/2211.05105), Schramowski et al., **Safe Latent Diffusion**, [Code](https://github.com/ml-research/safe-latent-diffusion), CVPR 2023, 2022-11
- [Forgedit: Text-guided Image Editing via Learning and Forgetting](https://arxiv.org/abs/2309.10556v2), Zhang et al., **Latent vector substraction, projection and editing**, [Code](https://github.com/witcherofresearch/Forgedit?utm_source=catalyzex.com), ArXiv, 2023-09
- [Prompting4Debugging: Red-Teaming Text-to-Image Diffusion Models by Finding Problematic Prompts](https://arxiv.org/abs/2309.06135), Chin et al., **Finding problematic prompts**, [No Code Available](), ArXiv, 2023-09
- [Prompt-Specific Poisoning Attacks on Text-to-Image Generative Models](http://arxiv.org/abs/2310.13828), **Prompt poisoning**, Shan et al., [No Code Available](), ArXiv, 2023-10
- [Removing NSFW Concepts from Vision-and-Language Models for Text-to-Image Retrieval and Generation](http://arxiv.org/abs/2311.16254), Poppi et al., **Clip-based Prompt engineering**, [Code](https://github.com/aimagelab/safe-clip?utm_source=catalyzex.com), ArXiv, 2023-11
- [Removing Undesirable Concepts in Text-to-Image Generative Models with Learnable Prompts](https://arxiv.org/abs/2403.12326), Bui et al., **Learnable Prompts**, ArXiv, 2024-03
- [Unlearning Backdoor Threats: Enhancing Backdoor Defense in Multimodal Contrastive Learning via Local Token Unlearning](http://arxiv.org/abs/2403.16257), Liang et al., **Local Token Unlearning**, ArXiv, 2024-03

### Weight Engineering

- [Salun: Empowering machine unlearning via gradientbased weight saliency in both image classification and generation](https://arxiv.org/abs/2310.12508), Fan et al., **Weight Saliency**, [Code](https://github.com/OPTML-Group/Unlearn-Saliency), ICLR 2024, 2023-10
- [Forget-Me-Not: Learning to Forget in Text-to-Image Diffusion Models](https://arxiv.org/abs/2303.17591), Zhang et al., **Attention Resteering Loss**, [Code](https://github.com/SHI-Labs/Forget-Me-Not?utm_source=catalyzex.com), ArXiv, 2023-03

### Knowledge Distillation
- [Exploiting Cultural Biases via Homoglyphs in Text-to-Image Synthesis](http://arxiv.org/abs/2209.08891), Struppek et al., **Homoglyphs**, [Code](https://github.com/LukasStruppek/Exploiting-Cultural-Biases-via-Homoglyphs?utm_source=catalyzex.com), Journal of Artificial Intelligence Research, 2022-09
- [Towards Safe Self-Distillation of Internet-Scale Text-to-Image Diffusion Models](https://arxiv.org/abs/2307.05977.pdf), Kim et al., **Safe Self-Distillation**, [Code](https://github.com/nannullna/safe-diffusion?utm_source=catalyzex.com), ArXiv, 2023-07
- [Editing Massive Concepts in Text-to-Image Diffusion Models](https://arxiv.org/abs/2403.13807), Xiong et al., **Massive Concept Editing**, [Code](https://silentview.github.io/EMCID/?utm_source=catalyzex.com), ArXiv, 2024-03

### Adversarial Training

- [To Generate or Not? Safety-Driven Unlearned Diffusion Models Are Still Easy To Generate Unsafe Images ... For Now](https://arxiv.org/abs/2310.11868), Zhang et al., **UnlearnDiff**, [Code](https://github.com/OPTML-Group/Diffusion-MU-Attack?utm_source=catalyzex.com), ArXiv, 2023-10

### Concept Editing
- [Ablating concepts in text-to-image diffusion models](https://arxiv.org/abs/2303.13516), Kumari et al., **Concept Ablation**, [Code](https://github.com/nupurkmr9/concept-ablation?utm_source=catalyzex.com), ICCV 2023, 2023-03
- [Erasing concepts from diffusion models](https://arxiv.org/abs/2303.07345), Gandikota et al., **Concept Erasure**, [Code](https://github.com/rohitgandikota/erasing?utm_source=catalyzex.com), CVPR 2023, 2023-03
- [Circumventing Concept Erasure Methods For Text-To-Image Generative Models](https://openreview.net/forum?id=YXciFZ4x8i), Pham et al., **Concept Erasure**, ICLR 2024, 2023-08
- [Unified Concept Editing in Diffusion Models](https://arxiv.org/abs/2308.14761), Gandikota et al., **Unified Concept Editing**, [Code](https://github.com/rohitgandikota/unified-concept-editing?utm_source=catalyzex.com), WACV 2024, 2023-08
- [Concept Sliders: LoRA Adaptors for Precise Control in Diffusion Models](https://arxiv.org/abs/2311.12092), Gandikota et al., **Concept Sliders**, ArXiv, 2023-11
- [Receler: Reliable Concept Erasing of Text-to-Image Diffusion Models via Lightweight Erasers](https://arxiv.org/abs/2311.17717), Huang et al., **Lightweight Erasers**,ArXiv, 2023-11
- [All but One: Surgical Concept Erasing with Model Preservation in Text-to-Image Diffusion Models](https://arxiv.org/pdf/2312.12807.pdf), Hong et al., **Surgical Concept Erasing**, ArXiv, 2023-12
- [Get What You Want, Not What You Don't: Image Content Suppression for Text-to-Image Diffusion Models](https://arxiv.org/abs/2402.05375), Li et al., **Image Content Suppression**, ArXiv, 2024-02
- [Separable Multi-Concept Erasure from Diffusion Models](http://arxiv.org/abs/2402.05947), Zhao et al., **Multi-Concept Erasure**, [Code](https://github.com/Dlut-lab-zmn/SepCE4MU), ArXiv, 2024-02
- [Editing Massive Concepts in Text-to-Image Diffusion Models](https://arxiv.org/abs/2403.13807), Xiong et al., **Massive Concept Editing**, [Code](https://silentview.github.io/EMCID/?utm_source=catalyzex.com), ArXiv, 2024-03

### Others

- [Continual Learning for Forgetting in Deep Generative Models](https://openreview.net/forum?id=YXciFZ4x8i), Heng et al, **Continual UnLearning**, ICML 2023 Workshop DeployableGenerativeAI, 2023-06


## Dataset

### Text-Image
- [Conceptual 12M](https://github.com/google-research-datasets/conceptual-12m), Changpinyo et al., CVPR 2021, 2021-09
- [COYO](https://github.com/kakaobrain/coyo-dataset), kakaobrain, **COYO**, ArXiv, 2022-08
- [TedBench](https://github.com/imagic-editing/imagic-editing.github.io/tree/main/tedbench), Kawar et al., **TedBench**, ArXiv, 2022-10
- [LAION-5B: An open large-scale dataset for training next generation image-text models](https://arxiv.org/abs/2210.08402), Schuhmann et al, **LAION-5B**, NeurIPS 2022, 2022-10
- [Inappropriate Image Prompts (I2P)](https://huggingface.co/datasets/AIML-TUDA/i2p), schramowski et al., **I2P**, CVPR 2023, 2023-01
- [ConceptBench](), Zhang et al., **ConceptBench**, ArXiv, 2023-03
- [MAGBIG](https://github.com/felifri/magbig), Fredrich et al., **Gender bias dataset**, ArXiv, 2024-01
- [UnlearnCanvas](), Zhang et al., **UnlearnCanvas**, ArXiv, 2024-03


## Evaluation

### General 

- [Deja Vu Memorization in Vision-Language Models](http://arxiv.org/abs/2402.02103), Jayaraman et al., **Deja Vu Memorization**, ArXiv, 2024-02

### Attack
- [Are Diffusion Models Vulnerable to Membership Inference Attacks?](https://arxiv.org/abs/2302.01316), Duan et al., **Membership Inference Attacks**, [Code](https://github.com/jinhaoduan/SecMI), ICML 2023, 2023-02
- [SneakyPrompt: Jailbreaking Text-to-image Generative Models](https://arxiv.org/abs/2305.12082), Yang et al., **SneakyPrompt**, [Code](https://github.com/Yuchen413/text2image_safety), IEEE SSP 2024, 2023-05
- [Can Sensitive Information Be Deleted From LLMs? Objectives for Defending Against Extraction Attacks](https://arxiv.org/abs/2309.17410), Wang et al., **Defending Against Extraction Attacks**, [Code](https://github.com/Vaidehi99/InfoDeletionAttacks?utm_source=catalyzex.com), ICLR 2024, 2023-09
- [Ring-A-Bell! How Reliable are Concept Removal Methods for Diffusion Models?](https://arxiv.org/abs/2310.10012), Tsai et al, **Red-teaming tool for T2I diffusion models**, ICLR 2024, 2023-10
- [To Generate or Not? Safety-Driven Unlearned Diffusion Models Are Still Easy To Generate Unsafe Images ... For Now](https://arxiv.org/abs/2310.11868), Zhang et al., **UnlearnDiff**, [Code](https://github.com/OPTML-Group/Diffusion-MU-Attack?utm_source=catalyzex.com), ArXiv, 2023-10
- [MMA-Diffusion: MultiModal Attack on Diffusion Models](https://arxiv.org/abs/2311.17516), Yang et al., **MMA-Diffusion**, Arxiv, 2023-11
- [The Stronger the Diffusion Model, the Easier the Backdoor: Data Poisoning to Induce Copyright Breaches Without Adjusting Finetuning Pipeline](https://arxiv.org/abs/2401.04136), Wang et al., **Data Poisoning for Copyright Breaches**, ArXiv, 2024-01
- [Discovering Universal Semantic Triggers for Text-to-Image Synthesis](http://arxiv.org/abs/2402.07562), Zhai et al., **Universal Semantic Triggers**, ArXiv, 2024-02
- 
### 