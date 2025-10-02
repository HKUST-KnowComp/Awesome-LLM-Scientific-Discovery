# Awesome LLM Scientific Discovery [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of pioneering research papers, tools, and resources at the intersection of Large Language Models (LLMs) and Scientific Discovery. 

Survey: ***From Automation to Autonomy: A Survey on Large Language Models in Scientific Discovery.*** ([https://arxiv.org/abs/2505.13259])

The survey delineates the evolving role of LLMs in science through a three-level autonomy framework:
*   **Level 1: LLM as Tool:** LLMs augmenting human researchers for specific, well-defined tasks.
*   **Level 2: LLM as Analyst:** LLMs exhibiting greater autonomy in processing complex information and offering insights.
*   **Level 3: LLM as Scientist:** LLM-based systems autonomously conducting major research stages.

Below is a visual representation of this taxonomy:

![Taxonomy of LLM in Scientific Discovery](taxonomy.png)

We aim to provide a comprehensive overview for researchers, developers, and enthusiasts interested in this rapidly advancing field.

## Contents

*   [Level 1: LLM as Tool](#level-1-llm-as-tool)
    *   [Literature Review and Information Gathering](#literature-review-and-information-gathering)
    *   [Idea Generation and Hypothesis Formulation](#idea-generation-and-hypothesis-formulation)
    *   [Experiment Planning and Execution](#experiment-planning-and-execution)
    *   [Data Analysis and Organization](#data-analysis-and-organization)
    *   [Conclusion and Hypothesis Validation](#conclusion-and-hypothesis-validation)
    *   [Iteration and Refinement](#iteration-and-refinement)
*   [Level 2: LLM as Analyst](#level-2-llm-as-analyst)
    *   [Machine Learning Research](#machine-learning-research)
    *   [Data Modeling and Analysis](#data-modeling-and-analysis)
    *   [Function Discovery](#function-discovery)
    *   [Natural Science Research](#natural-science-research)
    *   [General Research](#general-research)
    *   [Survey Generation](#survey-generation)
*   [Level 3: LLM as Scientist](#level-3-llm-as-scientist)
*   [Contributing](#contributing)

---

## Level 1: LLM as Tool

At this foundational level, LLMs function as tailored tools under direct human supervision, designed to execute specific, well-defined tasks within a single stage of the scientific method. Their primary goal is to enhance researcher efficiency.

### Literature Review and Information Gathering

Automating literature search, retrieval, synthesis, structuring, and organization.

*   **SCIMON : Scientific Inspiration Machines Optimized for Novelty** [![arXiv](https://pfst.cf2.poecdn.net/base/image/4d4ba262cd09ef3201012438cf42475526e49cffd727499d0589e25f1a7facab?pmaid=479529545)](https://arxiv.org/pdf/2305.14259) - *Wang et al. (2023.05)*
*   **ResearchAgent: Iterative research idea generation over scientific literature with Large Language Models** [![arXiv](https://arxiv.org/pdf/2404.07738)](https://arxiv.org/pdf/2404.07738) - *Baek et al. (2024.04)*
*   **Text-Tuple-Table: Towards Information Integration in Text-to-Table Generation via Global Tuple Extraction** [![arXiv](https://pfst.cf2.poecdn.net/base/image/951a79f1a483e43f056ea371995d112b222e47dfe146aae0395b05470a48e240?pmaid=479529524)](https://arxiv.org/pdf/2404.14215) - *Deng et al. (2024.04)*
*   **TKGT: Redefinition and A New Way of text-to-table tasks based on real world demands and knowledge graphs augmented LLMs** [![arXiv](https://pfst.cf2.poecdn.net/base/image/e0973bb8067b6438ef998a157154f54f38d851be22f8e94d9e103501f182902a?pmaid=479529519)](https://aclanthology.org/2024.emnlp-main.901.pdf) - *Jiang et al. (2024.10)*
*   **ArxivDIGESTables: Synthesizing scientific literature into tables using language models** [![arXiv](https://pfst.cf2.poecdn.net/base/image/8a43dfdbc844f2bc6cb06a7244611d2d45239d451ec7863d294fb0562eb005c3?pmaid=479529523)](https://arxiv.org/pdf/2410.22360) - *Newman et al. (2024.10)*
*   **Can LLMs Generate Tabular Summaries of Science Papers? Rethinking the Evaluation Protocol** [![arXiv](https://pfst.cf2.poecdn.net/base/image/1914ce3f7db99bf8d8a21b9b49566cbcc85fff80dc27ca75d7927c554ed2dd80?pmaid=479529498)](https://arxiv.org/pdf/2504.10284) - *Wang et al. (2025.04)*
*   **LitLLM: A Toolkit for Scientific Literature Review** [![arXiv](https://pfst.cf2.poecdn.net/base/image/3eee2dd5f3e1786b2ed12c970b86f33605395a1e837311a76d3e0c519ae052df?pmaid=479529556)](https://arxiv.org/pdf/2402.01788v1) - *Agarwal et al. (2024.02)*
*   **Title and abstract screening for literature reviews using large language models: an exploratory study in the biomedical domain** [![DOI](https://pfst.cf2.poecdn.net/base/image/ba25374b51bcb99df54c464778831f920d8b29032218ba924c946cb7c3f43f38?pmaid=479529504)](https://systematicreviewsjournal.biomedcentral.com/articles/10.1186/s13643-024-02575-4) - *Dennstädt et al. (2024.06)*
*   **Science Hierarchography: Hierarchical Organization of Science Literature** [![arXiv](https://pfst.cf2.poecdn.net/base/image/62746295b090c1a40660854aec64a66dac5ee4770c94dc9a470622b99ba84c91?pmaid=479529518)](https://arxiv.org/pdf/2504.13834) - *Gao et al. (2025.04)* 

### Idea Generation and Hypothesis Formulation

Automated generation of novel research ideas, conceptual insights, and testable scientific hypotheses.

*   **SciAgents: Automating scientific discovery through multi-agent intelligent graph reasoning** [![arXiv](https://pfst.cf2.poecdn.net/base/image/51b1b67814d2771c9fd3d3792dd13ca21d8a96b9cd7b33331cc87439bae29d0e?pmaid=479529466)](https://arxiv.org/pdf/2409.05556) - *Ghafarollahi et al. (2024.09)*
*   **Accelerating scientific discovery with generative knowledge extraction, graph-based representation, and multimodal intelligent graph reasoning** [![arXiv](https://pfst.cf2.poecdn.net/base/image/4861fd431c0f2481b80f53e076ae9b0a474408e4745442db8f94a503e7d5ce2d?pmaid=479529521)](https://arxiv.org/pdf/2403.11996) - *Buehler (2024.03)*
*   **MOOSE-Chem: Large Language Models for Rediscovering Unseen Chemistry Scientific Hypotheses** [![arXiv](https://pfst.cf2.poecdn.net/base/image/082876d870604712ac14aefea6d4483877bf9daf84e9c3d99e5d65568f5af213?pmaid=479529513)](https://arxiv.org/pdf/2410.07076) - *Yang et al. (2024.10)*
*   **Large Language Models are Zero Shot Hypothesis Proposers** [![arXiv](https://pfst.cf2.poecdn.net/base/image/ef2158eb75dd3d4084599eebc3df6a0d95e0b59f5a2d43470aee09cf04823604?pmaid=479529543)](https://arxiv.org/pdf/2311.05965) - *Qi et al. (2023.11)*
*   **Machine learning for hypothesis generation in biology and medicine: exploring the latent space of neuroscience and developmental bioelectricity** [![DOI](https://pfst.cf2.poecdn.net/base/image/c6dbf6481e3ba8ae5172b1679099f7e5897db0b4c49239f5f2ddd75ed33aa38e?pmaid=479529529)](https://pubs.rsc.org/en/content/articlelanding/2024/dd/d3dd00185g) - *O’Brien et al. (2023.07)*
*   **Large Language Models as Biomedical Hypothesis Generators: A Comprehensive Evaluation** [![arXiv](https://pfst.cf2.poecdn.net/base/image/e6945c9609f948d763d869d2f4e0602fda0d4d92a7ab8f1c5824e8dd645baeca?pmaid=479529473)](https://arxiv.org/pdf/2407.08940) - *Qi et al. (2024.07)*
*   **LLM4GRN: Discovering Causal Gene Regulatory Networks with LLMs -- Evaluation through Synthetic Data Generation** [![arXiv](https://pfst.cf2.poecdn.net/base/image/73ad0cf93c45ce22182317f461dbad86010d758f6b0055b3461147a18ad93533?pmaid=479529487)](https://arxiv.org/pdf/2410.15828) - *Afonja et al. (2024.10)*
*   **Scideator: Human-LLM Scientific Idea Generation Grounded in Research-Paper Facet Recombination** [![arXiv](https://pfst.cf2.poecdn.net/base/image/b8fcdd96cf98a30ff671c4b7e63837425f7aeffba0ccf761d162504adfe16342?pmaid=479529503)](https://arxiv.org/pdf/2409.14634) - *Radensky et al. (2024.09)*
*   **HypER: Literature-grounded Hypothesis Generation and Distillation with Provenance** [![arXiv](https://pfst.cf2.poecdn.net/base/image/e43a10c4f3cd5f5d6c93f5851a197dfdcd39236fc382a0924839a2ace72a2a37?pmaid=479529532)](https://arxiv.org/pdf/2503.12600) - *Vasu et al. (2025.06)*
*   **Sparks of Science: Hypothesis Generation Using Structured Paper Data** [![arXiv](https://pfst.cf2.poecdn.net/base/image/c2b21903a011a15420810d45d7ae3b809f78976c2d4b0ed293e29425253c76cb?pmaid=479529548)](https://arxiv.org/pdf/2504.12976) - *O'Neill et al. (2025.04)*
*   **Hypothesis Generation with Large Language Models** [![arXiv](https://pfst.cf2.poecdn.net/base/image/3bd5a03713598a8bf66da23a4dc2c84cdfbe253fec05fd3628c68aace2b60e86?pmaid=479529479)](https://arxiv.org/pdf/2404.04326) - *Zhou et al. (2024.04)*
*   **Harnessing the Power of Adversarial Prompting and Large Language Models for Robust Hypothesis Generation in Astronomy** [![arXiv](https://pfst.cf2.poecdn.net/base/image/8aa7f0941c8239d009ac0e2fb7cf29d33e13719848d83ba6f9ef08bdc271bfc2?pmaid=479529464)](https://arxiv.org/pdf/2306.11648) - *Ciuca et al. (2023.06)*
*   **Large Language Models for Scientific Synthesis, Inference and Explanation** [![arXiv](https://pfst.cf2.poecdn.net/base/image/0bb342438451f9a0042d0c5a430c3f2924e2876b97f7bcedee47b5c7f80a6fd7?pmaid=479529516)](https://arxiv.org/pdf/2310.07984) - *Zheng et al. (2023.10)*
*   **ResearchBench: Benchmarking LLMs in Scientific Idea Generation with Minimal Context** [![arXiv](https://pfst.cf2.poecdn.net/base/image/d6a64db638b3af03a24957b5be64220653741dd3c68f25bb5634d2c152d4f58a?pmaid=479529514)](https://arxiv.org/pdf/2503.21248) - *Liu et al. (2025.03)*
*   **AI Idea Bench 2025: AI Research Idea Generation Benchmark** [![arXiv](https://pfst.cf2.poecdn.net/base/image/8ead8edd66c7b2d304fba5015e3ca93bb5dc40086bf1711e8f2ab49210e01fa1?pmaid=479529471)](https://arxiv.org/pdf/2504.14191) - *Qiu et al. (2025.04)*
*   **IdeaBench: Benchmarking Large Language Models for Research Idea Generation** [![arXiv](https://pfst.cf2.poecdn.net/base/image/4a66b183eed7cee4a4537e368a08528074f43cb40701c60af5cdfeee8e773a4b?pmaid=479529557)](https://arxiv.org/pdf/2411.02429) - *Guo et al. (2024.11)*
*   **Can LLMs Generate Novel Research Ideas? A Large-Scale Human Study with 100+ NLP Researchers** [![arXiv](https://pfst.cf2.poecdn.net/base/image/28151fc6044ecd9ce45430571cd8665fc2ec10fdc5e38e9cc2c0dd215137f589?pmaid=479529460)](https://arxiv.org/pdf/2409.04109) - *Si et al. (2024.09)*
*   **Learning to Generate Research Idea with Dynamic Control** [![arXiv](https://pfst.cf2.poecdn.net/base/image/cf732870aeaff9fa95e0cb1efaca7b8143de0ffe2d847cad67cbf6f66c63379e?pmaid=479529542)](https://arxiv.org/pdf/2412.14626) - *Li et al. (2024.12)*
*   **LiveIdeaBench: Evaluating LLMs' Divergent Thinking for Scientific Idea Generation with Minimal Context** [![arXiv](https://pfst.cf2.poecdn.net/base/image/79cfdf99f0155a2abb99ea337545cd590aaa7b03943898c3fb208002294d9276?pmaid=479529476)](https://arxiv.org/pdf/2412.17596) - *Ruan et al. (2024.12)*
*   **Nova: An Iterative Planning and Search Approach to Enhance Novelty and Diversity of LLM Generated Ideas** [![arXiv](https://pfst.cf2.poecdn.net/base/image/ab664333a14199b39b273016ad872a6444c5ca89979116d52051635ac4008eb6?pmaid=479529458)](https://arxiv.org/pdf/2410.14255) - *Hu et al. (2024.10)*
*   **GraphEval: A Lightweight Graph-Based LLM Framework for Idea Evaluation** [![arXiv](https://pfst.cf2.poecdn.net/base/image/e43a10c4f3cd5f5d6c93f5851a197dfdcd39236fc382a0924839a2ace72a2a37?pmaid=479529532)](https://arxiv.org/pdf/2503.12600) - *Feng et al. (2025.03)*

### Experiment Planning and Execution

LLMs assisting in experimental protocol planning, workflow design, and scientific code generation.

*   **BioPlanner: Automatic Evaluation of LLMs on Protocol Planning in Biology** [![arXiv](https://pfst.cf2.poecdn.net/base/image/29b868dec7ab160ee670b66cfb731d4e93ec4a3d4588250e1a8847befc906b3d?pmaid=479529522)](https://arxiv.org/pdf/2310.10632) - *O'Donoghue et al. (2023.10)*
*   **Can Large Language Models Help Experimental Design for Causal Discovery?** [![arXiv](https://pfst.cf2.poecdn.net/base/image/b482095ed570d9aba3fc8a81971bd0d466a9035e0264d2a823dbc6d1cbb37f45?pmaid=479529554)](https://arxiv.org/pdf/2503.01139) - *Li et al. (2025.03)*
*   **Hierarchically Encapsulated Representation for Protocol Design in Self-Driving Labs** [![arXiv](https://arxiv.org/pdf/2504.03810)](https://arxiv.org/pdf/2504.03810) - *Shi et al. (2025.04)*
*   **SciCode: A Research Coding Benchmark Curated by Scientists** [![arXiv](https://pfst.cf2.poecdn.net/base/image/9bc53e61cd1ca2442b3c7603aafd76ca53a3d3211e66022a07486722a47ec056?pmaid=479529456)](https://arxiv.org/pdf/2407.13168) - *Tian et al. (2024.07)*
*   **Natural Language to Code Generation in Interactive Data Science Notebooks** [![arXiv](https://pfst.cf2.poecdn.net/base/image/c72208ff651dd976e81066e22e00e85f17a4aee97bf8609e71076345748acb71?pmaid=479529490)](https://arxiv.org/pdf/2212.09248) - *Yin et al. (2022.12)*
*   **DS-1000: A Natural and Reliable Benchmark for Data Science Code Generation** [![arXiv](https://pfst.cf2.poecdn.net/base/image/9218a9481d12f361b35858a5aaf8d853394e3a90121fd386a65273b56db7359b?pmaid=479529474)](https://arxiv.org/pdf/2211.11501) - *Lai et al. (2022.11)*
*   **Curie: Toward Rigorous and Automated Scientific Experimentation with AI Agents** [![arXiv](https://pfst.cf2.poecdn.net/base/image/6cac63f20df6d89f7dec39759b0b5d1b184eb6080d7c5c5362a68f674c5c7964?pmaid=479529481)](https://arxiv.org/pdf/2502.16069) - *Kon et al. (2025.02)*

### Data Analysis and Organization

LLMs assisting in data-driven analysis, tabular/chart reasoning, statistical reasoning, and model discovery.

*   **AutomaTikZ: Text-Guided Synthesis of Scientific Vector Graphics with TikZ** [![arXiv](https://pfst.cf2.poecdn.net/base/image/a8f9fcc1868d0a2608f91cf6e1075c49fafc9c50bd9bcd6ba01b1f10bc33ba09?pmaid=479529485)](https://arxiv.org/pdf/2310.00367) - *Belouadi et al. (2023.10)*
*   **Text2Chart31: Instruction Tuning for Chart Generation with Automatic Feedback** [![arXiv](https://pfst.cf2.poecdn.net/base/image/92a4983d2470190fd48e6a4868005b8848868f9615733a38944e918910639c45?pmaid=479529459)](https://arxiv.org/pdf/2410.04064) - *Zadeh et al. (2024.10)*
*   **ChartQA: A Benchmark for Question Answering about Charts with Visual and Logical Reasoning** [![arXiv](https://pfst.cf2.poecdn.net/base/image/b0860ca74a57d459a51073c60e147f534043abfab3deb0b1d026486dadfb2784?pmaid=479529546)](https://arxiv.org/pdf/2203.10244) - *Masry et al. (2022.03)*
*   **CharXiv: Charting Gaps in Realistic Chart Understanding in Multimodal LLMs** [![arXiv](https://pfst.cf2.poecdn.net/base/image/bb6010bee5ea00c664ca41d1738988a68bc4797b636127796a6be4b2e9e97a97?pmaid=479529489)](https://arxiv.org/pdf/2406.18521) - *Wang et al. (2024.06)*
*   **ChartX & ChartVLM: A Versatile Benchmark and Foundation Model for Complicated Chart Reasoning** [![arXiv](https://pfst.cf2.poecdn.net/base/image/280fecf207a7ead4b39ece7e60267d5f71fa3d9779a1ed45006f3a1572cdfcbb?pmaid=479529478)](https://arxiv.org/pdf/2402.12185) - *Xia et al. (2024.02)*
*   **Chain-of-Table: Evolving Tables in the Reasoning Chain for Table Understanding** [![arXiv](https://pfst.cf2.poecdn.net/base/image/c4dac83da1e31157bcded0cf90d815135a9aeb9daffb73d2bab84fe41f7f1e69?pmaid=479529541)](https://arxiv.org/pdf/2401.04398) - *Wang et al. (2024.01)*
*   **TableBench: A Comprehensive and Complex Benchmark for Table Question Answering** [![arXiv](https://pfst.cf2.poecdn.net/base/image/4e63eef45b1b788500c38941c303194bd2e175c96cb073bfa84c90d0fdc59311?pmaid=479529550)](https://arxiv.org/pdf/2408.09174) - *Wu et al. (2024.08)*
*   **Tables as Texts or Images: Evaluating the Table Reasoning Ability of LLMs and MLLMs** [![arXiv](https://pfst.cf2.poecdn.net/base/image/2c2f8e2a1161fb3947ace17e9b382a90d1c53ed19f4b865525683a2ae6f56bc0?pmaid=479529480)](https://arxiv.org/pdf/2402.12424) - *Deng et al. (2024.02)*

### Conclusion and Hypothesis Validation

LLMs providing feedback, verifying claims, replicating results, and generating reviews.

*   **CLAIMCHECK: How Grounded are LLM Critiques of Scientific Papers?** [![arXiv](https://pfst.cf2.poecdn.net/base/image/c7f87f4be57a6240ee8a52f01520cb3c1182f1a22f25f397f6a6f7512752e643?pmaid=479529534)](https://arxiv.org/pdf/2503.21717) - *Ou et al. (2025.03)*
*   **LLMs Assist NLP Researchers: Critique Paper (Meta-)Reviewing** [![arXiv](https://pfst.cf2.poecdn.net/base/image/8afb2d62c074ad3148a0ecc9b7d5ee44b16395b11a09a171598bdb580000ab24?pmaid=479529502)](https://arxiv.org/pdf/2406.16253) - *Du et al. (2024.06)*
*   **AI-Driven Review Systems: Evaluating LLMs in Scalable and Bias-Aware Academic Reviews** [![arXiv](https://pfst.cf2.poecdn.net/base/image/1eddd2921ce7856ebee550750e7f841f0fc7881cb6a023cabde66ea45ece1ed4?pmaid=479529517)](https://arxiv.org/pdf/2408.10365) - *Tyser et al. (2024.08)*
*   **Is LLM a Reliable Reviewer? A Comprehensive Evaluation of LLM on Automatic Paper Reviewing Tasks** [![Link](https://pfst.cf2.poecdn.net/base/image/b1a9e41c6b7696115981b094a26e3d39c0bcddc9655e8a4d6dd2ec0eba59bc16?pmaid=479529549)](https://aclanthology.org/2024.lrec-main.816.pdf) - *Zhou et al. (2024.05)*
*   **ReviewerGPT? An Exploratory Study on Using Large Language Models for Paper Reviewing** [![arXiv](https://pfst.cf2.poecdn.net/base/image/472eb54b69084569f4e83d8227894973860959965b4893861690047101bcdd69?pmaid=479529536)](https://arxiv.org/pdf/2306.00622) - *Liu and Shah (2023.06)*
*   **Towards Autonomous Hypothesis Verification via Language Models with Minimal Guidance** [![arXiv](https://pfst.cf2.poecdn.net/base/image/f44a5bbc6ab8e1f4b8c5a0388b53137d1559ed5d59280e7442c252ba61272021?pmaid=479529505)](https://arxiv.org/pdf/2311.09706) - *Takagi et al. (2023.11)*
*   **CycleResearcher: Improving Automated Research via Automated Review** [![arXiv](https://pfst.cf2.poecdn.net/base/image/030fe11289216ebe710703ec31ee224d1cbd4bd1b40e6e1b3113473d19332bac?pmaid=479529539)](https://arxiv.org/pdf/2411.00816) - *Weng et al. (2024.11)*
*   **PaperBench: Evaluating AI’s Ability to Replicate AI Research** [![arXiv](https://pfst.cf2.poecdn.net/base/image/4fff9cffe893b7c6f63dd2f0429425be4f215209a6c70d222dc6c7114216e5e0?pmaid=479529457)](https://arxiv.org/pdf/2504.01848) - *Starace et al. (2025.04)*
*   **SciReplicate-Bench: Benchmarking LLMs in Agent-driven Algorithmic Reproduction from Research Papers** [![arXiv](https://arxiv.org/pdf/2504.00255)](https://arxiv.org/pdf/2504.00255) - *Xiang et al. (2025.04)*
*   **Advancing AI-Scientist Understanding: Making LLM Think Like a Physicist with Interpretable Reasoning** [![arXiv](https://pfst.cf2.poecdn.net/base/image/1793dcbe461c1687ccfe24e86d564e343aaa63d0d6f58719a878d6236bdf3014?pmaid=479529469)](https://arxiv.org/pdf/2504.01911) - *Xu et al. (2025.04)*
*   **Generative Adversarial Reviews: When LLMs Become the Critic** [![arXiv](https://pfst.cf2.poecdn.net/base/image/c854084b87aaa9cf9ddc6584582c464aa6256b2c4493988c0b6d47869ce988ba?pmaid=479529497)](https://arxiv.org/pdf/2412.10415) - *Bougie & Watanabe (2024.12)*
*   **Predicting Empirical AI Research Outcomes with Language Models** [![arXiv](https://pfst.cf2.poecdn.net/base/image/ac8ea4e93dfb1fc3fc9a7475c0a547ee6f30330fa48d591af65231086e211f70?pmaid=479529506)](https://arxiv.org/pdf/2506.00794) - *Wen et al. (2025.06)*

### Iteration and Refinement

LLMs involved in iterative refinement of research hypotheses and strategic exploration.

*   **Verification and Refinement of Natural Language Explanations through LLM-Symbolic Theorem Proving** [![arXiv](https://pfst.cf2.poecdn.net/base/image/310561f9df22b7033b2268dbf1ff1a41fecc840538025b34b8de8c6a20b6d76a?pmaid=479529468)](https://arxiv.org/pdf/2405.01379) - *Quan et al. (2024.05)*
*   **Chain of Ideas: Revolutionizing Research Via Novel Idea Development with LLM Agents** [![arXiv](https://pfst.cf2.poecdn.net/base/image/a8feba712f587b7ae0de752fab22818932967dfe50eee85e53fa3bc96d547b57?pmaid=479529482)](https://arxiv.org/pdf/2410.13185) - *Li et al. (2024.10)*
*   **Iterative Hypothesis Generation with Monte Carlo Nash Equilibrium Self-Refining Trees** [![arXiv](https://pfst.cf2.poecdn.net/base/image/c75a1dbcfdd46c3727e3703646e37ec0fae9664f070f3b8b1ca53b7ab8342bb9?pmaid=479529509)](https://arxiv.org/pdf/2503.19309) - *Rabby et al. (2025.03)*
*   **XtraGPT: LLMs for Human-AI Collaboration on Controllable Academic Paper Revision** [![arXiv](https://pfst.cf2.poecdn.net/base/image/3d6efcda471b30090a07fa82c0e996026be2090430f9b17f49b202e2e2377616?pmaid=479529507)](https://arxiv.org/pdf/2505.11336) - *Chen et al. (2025.05)*

---

## Level 2: LLM as Analyst

LLMs exhibiting a greater degree of autonomy, functioning as passive agents capable of complex information processing, data modeling, and analytical reasoning with reduced human intervention.

### Machine Learning Research

Automated modeling of machine learning tasks, experiment design, and execution.

*   **MLAgentBench: Evaluating Language Agents on Machine Learning Experimentation** [![arXiv](https://pfst.cf2.poecdn.net/base/image/ff43a01d6ca44965b2f21969466d7df4e47b17fbfdea139aa1c0b7517bbcf3b6?pmaid=479529470)](https://arxiv.org/pdf/2310.03302) - *Huang et al. (2023.10)*
*   **MLR-Copilot: Autonomous Machine Learning Research based on Large Language Models Agents** [![arXiv](https://pfst.cf2.poecdn.net/base/image/738494b58c91cdd4177fe11082bf39c01cb82da28ff3fb1d88ce31dc3a22d398?pmaid=479529537)](https://arxiv.org/pdf/2408.14033) - *Li et al. (2024.08)*
*   **MLE-bench: Evaluating Machine Learning Agents on Machine Learning Engineering** [![arXiv](https://pfst.cf2.poecdn.net/base/image/de58bc6c21c81dee823adb950052660d8921d0ea6810f9a7d06c8d0aacbbc53d?pmaid=479529463)](https://arxiv.org/pdf/2410.07095) - *Chan et al. (2024.10)*
*   **IMPROVE: Iterative Model Pipeline Refinement and Optimization Leveraging LLM Agents** [![arXiv](https://pfst.cf2.poecdn.net/base/image/2214a0967159a4d1dfc240c9e985305bda60c5db753fdf21579ed8e6c3a25e1c?pmaid=479529528)](https://arxiv.org/pdf/2502.18530v1) - *Xue et al. (2025.02)*
*   **CodeScientist: End-to-End Semi-Automated Scientific Discovery with Code-based Experimentation** [![arXiv](https://pfst.cf2.poecdn.net/base/image/4266a0d973ef963c14e96b2e3425964473f525cbaa562412c04e046240f75a62?pmaid=479529461)](https://arxiv.org/pdf/2503.22708) - *Jansen et al. (2025.03)*
*   **MLRC-Bench: Can Language Agents Solve Machine Learning Research Challenges?** [![arXiv](https://pfst.cf2.poecdn.net/base/image/a1d6efa83e2674f5bfa49c791a4cee9f27f51e366c0b15a794dda971ead33fef?pmaid=479529493)](https://arxiv.org/pdf/2504.09702) - *Zhang et al. (2025.04)*
*   **RE-Bench: Evaluating frontier AI R&D capabilities of language model agents against human experts** [![arXiv](https://pfst.cf2.poecdn.net/base/image/0a21d2105616573796f9bc04db84432074b139b85d67d3c86d9108dc71528f28?pmaid=479529525)](https://arxiv.org/pdf/2411.15114) - *Wijk et al. (2024.11)*
*   **MLZero: A Multi-Agent System for End-to-end Machine Learning Automation** [![arXiv](https://pfst.cf2.poecdn.net/base/image/d91e23f22d425c9bf74ad098cee59591ebfcf7490355f3f75b117be3dc91032b?pmaid=479529515)](https://arxiv.org/pdf/2505.13941) - *Fang et al. (2025.05)*
*   **AIDE: AI-Driven Exploration in the Space of Code** [![arXiv](https://pfst.cf2.poecdn.net/base/image/4cb1c99cb44c8851d9f7d9d566f32951181ca6e5a286dcb28d579b487571e188?pmaid=479529555)](https://arxiv.org/pdf/2502.13138) - *Jiang et al. (2025.02)*
*   **Language Modeling by Language Models** [![arXiv](https://arxiv.org/pdf/2506.00794)](https://arxiv.org/pdf/2506.00794) - *Cheng et al. (2025.06)*
*   **MLGym: A New Framework and Benchmark for Advancing AI Research Agents** [![arXiv](https://pfst.cf2.poecdn.net/base/image/9ace785c27d0747fe174fdddd9cf2792452641db93e3b1a7e6672fc074dfe561?pmaid=479529552)](https://arxiv.org/pdf/2502.14499) - *Nathani et al. (2025.02)*

### Data Modeling and Analysis

Automated data-driven analysis, statistical data modeling, and hypothesis validation.

*   **Automated Statistical Model Discovery with Language Models** [![arXiv](https://pfst.cf2.poecdn.net/base/image/d074449cdd945dd1d7a8938a0e11d292db27afbe5c0663d9d423b54003b4dde2?pmaid=479529486)](https://arxiv.org/pdf/2402.17879) - *Li et al. (2024.02)*
*   **InfiAgent-DABench: Evaluating Agents on Data Analysis Tasks** [![arXiv](https://pfst.cf2.poecdn.net/base/image/9b8dd9615209c1d37f7e89f4ef5297621bd79b27c91325ce513fd0851fa9a118?pmaid=479529477)](https://arxiv.org/pdf/2401.05507) - *Hu et al. (2024.01)*
*   **DS-Agent: Automated Data Science by Empowering Large Language Models with Case-Based Reasoning** [![arXiv](https://pfst.cf2.poecdn.net/base/image/daf0aca8deb525c87d8148f242a8c2c646fdf5b7964df33d58c50745b120358f?pmaid=479529495)](https://arxiv.org/pdf/2402.17453) - *Guo et al. (2024.02)*
*   **BLADE: Benchmarking Language Model Agents for Data-Driven Science** [![arXiv](https://pfst.cf2.poecdn.net/base/image/132814e6ca3fd80d6c0590e164844021c087c9a6fb81b975e514be3e497635df?pmaid=479529492)](https://arxiv.org/pdf/2408.09667) - *Gu et al. (2024.08)*
*   **DAgent: A Relational Database-Driven Data Analysis Report Generation Agent** [![arXiv](https://pfst.cf2.poecdn.net/base/image/d8ca42e16bafae0e7c91bd249e624e09a3af4e0a0a21e3839f239867f96dd18b?pmaid=479529511)](https://arxiv.org/pdf/2503.13269) - *Xu et al. (2025.03)*
*   **DiscoveryBench: Towards Data-Driven Discovery with Large Language Models** [![arXiv](https://pfst.cf2.poecdn.net/base/image/e86fbbf58a6dc615ab7553131a6a2c2ada8aaf3ae52e348b89adbfea7328991a?pmaid=479529510)](https://arxiv.org/pdf/2407.01725) - *Majumder et al. (2024.07)*
*   **Large Language Models for Scientific Synthesis, Inference and Explanation** [![arXiv](https://pfst.cf2.poecdn.net/base/image/0bb342438451f9a0042d0c5a430c3f2924e2876b97f7bcedee47b5c7f80a6fd7?pmaid=479529516)](https://arxiv.org/pdf/2310.07984) - *Zheng et al. (2023.10)*
*   **MM-Agent: LLM as Agents for Real-world Mathematical Modeling Problem** [![arXiv](https://pfst.cf2.poecdn.net/base/image/1204056cfa4da3a8662050074a94ef8261b3a294c7a0725396785618d286295c?pmaid=479529540)](https://arxiv.org/pdf/2505.14148) - *Liu et al. (2025.05)*
*   **DSBench: How Far Are Data Science Agents from Becoming Data Science Experts?** [![arXiv](https://pfst.cf2.poecdn.net/base/image/38af421275697b76089c559a7c6d7975f9100a1eee2162dcee90563997ef2b17?pmaid=479529520)](https://arxiv.org/pdf/2409.07703) - *Jing et al. (2024.09)*

### Function Discovery

Identifying underlying equations from observational data (AI-driven symbolic regression).

*   **LLM-SR: Scientific Equation Discovery via Programming with Large Language Models** [![arXiv](https://pfst.cf2.poecdn.net/base/image/fa4b73511c0d6358a02e72527378cd86f90b44c21ff67619160e772d2c583659?pmaid=479529526)](https://arxiv.org/pdf/2404.18400) - *Shojaee et al. (2024.04)*
*   **LLM-SRBench: A New Benchmark for Scientific Equation Discovery with Large Language Models** [![arXiv](https://pfst.cf2.poecdn.net/base/image/2dfe3399c4c0c3e24090365f2b4f46644d27d762f77260b1d91bb6f513b1ff09?pmaid=479529533)](https://arxiv.org/pdf/2504.10415) - *Shojaee et al. (2025.04)*
*   **Gravity-Bench-v1: A Benchmark on Gravitational Physics Discovery for Agents** [![arXiv](https://pfst.cf2.poecdn.net/base/image/acdadfee979d6d614dc7c2137f29faec074457c5ab0f3cc01af0770b7eed3cf0?pmaid=479529512)](https://arxiv.org/pdf/2501.18411) - *Koblischke et al. (2025.01)*
*   **Evosld: Automated neural scaling law discovery with large language models** [![arXiv](https://arxiv.org/pdf/2505.14148)](https://arxiv.org/pdf/2505.14148) - *Unknown (year unknown)*
*   **DrSR: LLM based Scientific Equation Discovery with Dual Reasoning from Data and Experience** [![arXiv](https://arxiv.org/pdf/2411.00816)](https://arxiv.org/pdf/2411.00816) - *Unknown (year unknown)*

### Natural Science Research

Autonomous research workflows for natural science discovery (e.g., chemistry, biology, biomedicine).

*   **Coscientist: Autonomous Chemical Research with Large Language Models** [![DOI](https://pfst.cf2.poecdn.net/base/image/1f527b1741a21de641fccf6621212fcdead1e5d0d3e7cbef84b7e1a0035a3d52?pmaid=479529544)](https://www.nature.com/articles/s41586-023-06792-0) - *Boiko et al. (2023.10)*
*   **Empowering biomedical discovery with AI agents** [![DOI](https://pfst.cf2.poecdn.net/base/image/3e58f19a5716d52656740a703c3af7fc3b77709ad431c48600c284e14cb52960?pmaid=479529472)](https://www.cell.com/action/showPdf?pii=S0092-8674%2824%2901070-5) - *Gao et al. (2024.09)*
*   **From Intention To Implementation: Automating Biomedical Research via LLMs** [![arXiv](https://arxiv.org/pdf/2412.09429)](https://arxiv.org/pdf/2412.09429) - *Luo et al. (2024.12)*
*   **DrugAgent: Automating AI-aided Drug Discovery Programming through LLM Multi-Agent Collaboration** [![arXiv](https://pfst.cf2.poecdn.net/base/image/dd4bf460c07a0f463ed29c62ed73ef7d187214eae3e560f6eb5ad50b39a5d98e?pmaid=479529538)](https://arxiv.org/pdf/2411.15692) - *Liu et al. (2024.11)*
*   **ScienceAgentBench: Toward Rigorous Assessment of Language Agents for Data-Driven Scientific Discovery** [![arXiv](https://pfst.cf2.poecdn.net/base/image/276479e3a9c8ae74fea731d124df4308bb4dc8e1452814a2d92d55066bf88444?pmaid=479529462)](https://arxiv.org/pdf/2410.05080) - *Chen et al. (2024.10)*
*   **ProtAgents: Protein discovery by combining physics and machine learning** [![arXiv](https://pfst.cf2.poecdn.net/base/image/916932cdbf34525677613798130db86d547e95088a8331061ecb175e99aa23ad?pmaid=479529501)](https://arxiv.org/pdf/2402.04268) - *Ghafarollahi and Buehler (2024.02)*
*   **Auto-Bench: An Automated Benchmark for Scientific Discovery in LLMs** [![arXiv](https://pfst.cf2.poecdn.net/base/image/698f71ac6578cae69bce32a6312d04c47c22f88096cd07f9456c30a554bd4f15?pmaid=479529488)](https://arxiv.org/pdf/2502.15224) - *Chen et al. (2025.02)*
*   **Towards an AI co-scientist** [![arXiv](https://pfst.cf2.poecdn.net/base/image/a63ebebf42fbbbe0c953ad7f6ff99f5df636e08ca5164601548a376d621963df?pmaid=479529535)](https://arxiv.org/pdf/2502.18864) - *Gottweis et al. (2025.02)*

### General Research

Benchmarks and frameworks evaluating diverse tasks from different stages of scientific discovery.

*   **DISCOVERYWORLD: A Virtual Environment for Developing and Evaluating Automated Scientific Discovery Agents** [![arXiv](https://pfst.cf2.poecdn.net/base/image/64f5058f1082872fe9b4917977fe0222eeb7ab7e3e223cd1853a1301e78355e3?pmaid=479529467)](https://arxiv.org/pdf/2406.06769) - *Jansen et al. (2024.06)*
*   **A Vision for Auto Research with LLM Agents** [![arXiv](https://pfst.cf2.poecdn.net/base/image/858ae871487129721ed719323408a5218d570f7499026b373c5cdd5ca3438f4c?pmaid=479529496)](https://arxiv.org/pdf/2504.18765) - *Liu et al. (2025.04)*
*   **CURIE: Evaluating LLMs On Multitask Scientific Long Context Understanding and Reasoning** [![arXiv](https://pfst.cf2.poecdn.net/base/image/e28a0b55ccfed27bc4ab393592d07294167df4940c4505999f40beb689b9c2c1?pmaid=479529530)](https://arxiv.org/pdf/2503.13517) - *Cui et al. (2025.03)*
*   **EAIRA: Establishing a Methodology for Evaluating AI Models as Scientific Research Assistants** [![arXiv](https://pfst.cf2.poecdn.net/base/image/83cf24a86cc204c091cf37b0821fbac71d5cb375d4c9e9ebcd03d6733c23b618?pmaid=479529483)](https://arxiv.org/pdf/2502.20309) - *Cappello et al. (2025.02)*

### Survey Generation

*   **AutoSurvey: Large Language Models Can Automatically Write Surveys** [![arXiv](https://arxiv.org/pdf/2406.10252)](https://arxiv.org/pdf/2406.10252) - *Wang et al. (2024.06)*

---

## Level 3: LLM as Scientist

LLM-based systems operating as active agents capable of orchestrating and navigating multiple stages of the scientific discovery process with considerable independence, often culminating in draft research papers.

*   **Agent Laboratory: Using LLM Agents as Research Assistants** [![arXiv](https://img.shields.io/badge/arXiv-2501.04227-B31B1B.svg)](https://arxiv.org/pdf/2501.04227) - *Schmidgall et al. (2025.01)*
*   **The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery** [![arXiv](https://img.shields.io/badge/arXiv-2408.06292-B31B1B.svg)](https://arxiv.org/pdf/2408.06292) - *Lu et al. (2024.08)*
*   **The AI Scientist-v2: Workshop-Level Automated Scientific Discovery via Agentic Tree Search** [![arXiv](https://img.shields.io/badge/arXiv-2504.08066-B31B1B.svg)](https://arxiv.org/pdf/2504.08066) - *Yamada et al. (2025.04)*
*   **AI-Researcher: Fully-Automated Scientific Discovery with LLM Agents** [![GitHub](https://img.shields.io/badge/GitHub-HKUDS/AI--Researcher-blue.svg)](https://github.com/HKUDS/AI-Researcher) - *Data Intelligence Lab (2025.03)*
*   **Zochi Technical Report** [![Link](https://img.shields.io/badge/Link-Intology.AI-blue.svg)](https://www.intology.ai/blog/zochi-tech-report) - *Intology AI (2025.03)*
*   **Meet Carl: The First AI System To Produce Academically Peer-Reviewed Research** [![Link](https://img.shields.io/badge/Link-AutoScience.AI-blue.svg)](https://www.autoscience.ai/blog/meet-carl-the-first-ai-system-to-produce-academically-peer-reviewed-research) - *Autoscience Institute (2025.03)*

---

## Contributing

Contributions are welcome! If you have a paper, tool, or resource that fits into this taxonomy, please submit a **pull request**.

---

## Citation

Please cite our paper if you found our survey helpful:
```bibtex
@misc{zheng2025automationautonomysurveylarge,
      title={From Automation to Autonomy: A Survey on Large Language Models in Scientific Discovery}, 
      author={Tianshi Zheng and Zheye Deng and Hong Ting Tsang and Weiqi Wang and Jiaxin Bai and Zihao Wang and Yangqiu Song},
      year={2025},
      eprint={2505.13259},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2505.13259}, 
}
