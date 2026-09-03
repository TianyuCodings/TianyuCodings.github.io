---
layout: about
title: About
permalink: /
subtitle: University of Texas at Austin; tianyuchen@utexas.edu

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p> White Sands, New Mexico </p>

news: true # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
---

I am a fourth-year PhD student at the University of Texas at Austin,
supervised by Professor [Mingyuan Zhou](https://mingyuanzhou.github.io/).
I am currently a Student Researcher at **Google DeepMind (Gemini)**,
and was previously a Research Scientist Intern at **Microsoft Research (MAI Superintelligence)**.
Before joining UT, I obtained my master's degree in Statistics from the University of Chicago,
where I closely collaborated with [Kevin Bello](https://kevinsbello.github.io/),
[Bryon Aragam](https://www.bryonaragam.com/), [Pradeep Ravikumar](https://www.cs.cmu.edu/~pradeepr/),
[Francesco Locatello](https://www.francescolocatello.com/),
and supervised by Professor [Jingshu Wang](https://jingshuw.org/).
I earned my Bachelor's degree in Statistics from Fudan University,
where I spent some of the most memorable moments of my life.

Research Interests: I build **reinforcement learning and distillation methods that make LLMs and multimodal agents reason, search, and evaluate reliably**, grounded in statistical rigor.

- **RL for LLM post-training**: algorithms for reasoning and alignment in both autoregressive and diffusion LLMs, including regression-aware policy gradients for LLM-as-a-Judge ([REAL](https://arxiv.org/abs/2603.17145), ICML 2026) and data-efficient GRPO via difficulty-targeted selection and rollout replay ([NeurIPS 2025](https://arxiv.org/abs/2506.05316)).
- **Reward design & agentic evaluation**: turning LLM/VLM judges, detectors, and rankers into trustworthy reward signals; e.g., [EdiVal-Agent](https://arxiv.org/abs/2509.13399) (ICLR 2026), an object-centric agent that autonomously synthesizes instructions and verifies multi-turn edits, and [MT-EditFlow](https://arxiv.org/abs/2606.01985), multi-turn RL with reward aggregation that resists reward hacking.
- **Agentic search & test-time adaptation**: RL-trained autoregressive retrievers for multi-hop retrieval over million-scale corpora (Google DeepMind), and reusing ranking rewards as test-time state for frozen embedding models ([TTT-Embed](https://arxiv.org/abs/2608.12569)).
- **Distillation beyond acceleration**: score and policy distillation as a mechanism to _improve_ models, from one-step policies for offline RL ([DTQL](https://arxiv.org/abs/2405.19690), NeurIPS 2024) to generative modeling from corrupted data ([ICLR 2026](https://arxiv.org/abs/2505.13377)) and causal estimation ([IWDD](https://arxiv.org/abs/2505.11444)).
- **Statistical foundations for reliable ML**: finite-sample tests for validating neural posterior estimators and generative models ([CoLT](https://arxiv.org/abs/2507.17030), NeurIPS 2025 Spotlight; [Conformal C2ST](https://arxiv.org/abs/2507.17026), ICML 2026) and identifiability of causal mechanism shifts ([iSCAN](https://arxiv.org/abs/2306.17361), NeurIPS 2023).
