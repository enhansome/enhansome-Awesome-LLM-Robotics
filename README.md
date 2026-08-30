# Awesome-LLM-Robotics with stars

This repo contains a curative list of **papers using Large Language/Multi-Modal Models for Robotics/RL**. Template from [awesome-Implicit-NeRF-Robotics](https://github.com/zubair-irshad/Awesome-Implicit-NeRF-Robotics) ⭐ 1,566 | 🐛 2 | 📅 2025-07-12 <br>

#### Please feel free to send me [pull requests](https://github.com/GT-RIPL/Awesome-LLM-Robotics/blob/main/how-to-PR.md) ⭐ 4,458 | 🐛 10 | 📅 2026-07-17 or [email](mailto:zkira-changetoat-gatech--changetodot-changetoedu) to add papers! Please make sure to put in reverse chronological order and follow the format carefully! <br>

If you find this repository useful, please consider [citing](#citation) and STARing this list. Feel free to share this list with others!

***

## Overview

* [Awesome-LLM-Robotics ](#awesome-llm-robotics-)
  * [Overview](#overview)
  * [Surveys](#surveys)
  * [Reasoning](#reasoning)
  * [Planning](#planning)
  * [Manipulation](#manipulation)
  * [Instructions and Navigation](#instructions-and-navigation)
  * [Simulation Frameworks](#simulation-frameworks)
  * [Safety, Risks, Red Teaming, and Adversarial Testing](#safety-risks-red-teaming-and-adversarial-testing)
  * [Libraries and Tools](#libraries-and-tools)
  * [Citation](#citation)

***

## Surveys

* "Foundation Models in Robotics: Applications, Challenges, and the Future", *arXiv, Dec 2023*, \[[Paper](https://arxiv.org/abs/2312.07843)] \[[Paper List](https://github.com/robotics-survey/Awesome-Robotics-Foundation-Models) ⭐ 1,401 | 🐛 3 | 📅 2024-10-07]
* "Toward General-Purpose Robots via Foundation Models: A Survey and Meta-Analysis", *arXiv, Dec 2023*. \[[Paper](https://arxiv.org/abs/2312.08782)] \[[Paper List](https://github.com/JeffreyYH/robotics-fm-survey) ⭐ 468 | 🐛 0 | 📅 2026-06-25] \[[Website](https://robotics-fm-survey.github.io/)]
* "Safety in Embodied AI: A Survey of Risks, Attacks, and Defenses", *arXiv, May 2026*, \[[Paper](https://arxiv.org/abs/2605.02900)] \[[Website](https://x-zheng16.github.io/Awesome-Embodied-AI-Safety/)]
* "A Survey of Robotic Language Grounding: Tradeoffs between Symbols and Embeddings", *IJCAI, Aug 2024*, [\[Paper\]](https://arxiv.org/abs/2405.13245)
* "A Superalignment Framework in Autonomous Driving with Large Language Models", *arXiv, Jun 2024*, \[[Paper](https://arxiv.org/abs/2406.05651)]
* "Neural Scaling Laws for Embodied AI", *arXiv, May 2024*. \[[Paper](https://arxiv.org/abs/2405.14005)]
* "On the Prospects of Incorporating Large Language Models (LLMs) in Automated Planning and Scheduling (APS)", *ICAPS, May 2024*, [\[Paper\]](https://ojs.aaai.org/index.php/ICAPS/article/view/31503) [\[Website\]](https://ai4society.github.io/LLM-Planning-Viz/)
* "Language-conditioned Learning for Robotic Manipulation: A Survey", *arXiv, Dec 2023*, \[[Paper](https://arxiv.org/abs/2312.10807)]
* "Robot Learning in the Era of Foundation Models: A Survey", *arXiv, Nov 2023*, \[[Paper](https://arxiv.org/abs/2311.14379)]
* "The Development of LLMs for Embodied Navigation", *arXiv, Nov 2023*, \[[Paper](https://arxiv.org/abs/2311.00530)]

***

## Reasoning

* **Code-As-Policies**: "Code as Policies: Language Model Programs for Embodied Control", *arXiv, Sept 2022*. \[[Paper](https://arxiv.org/abs/2209.07753)]  \[[Colab](https://github.com/google-research/google-research/tree/master/code_as_policies) ⭐ 38,655 | 🐛 1,989 | 🌐 Jupyter Notebook | 📅 2026-08-27] \[[Website](https://code-as-policies.github.io/)]
* **Generative Agents**: "Generative Agents: Interactive Simulacra of Human Behavior", *arXiv, Apr 2023*. \[[Paper](https://arxiv.org/abs/2304.03442v1) [Code](https://github.com/joonspk-research/generative_agents) ⭐ 22,021 | 🐛 146 | 📅 2024-08-05]
* **RT-1**: "RT-1: Robotics Transformer for Real-World Control at Scale", *arXiv, Dec 2022*. \[[Paper](https://arxiv.org/abs/2212.06817)]  \[[GitHub](https://github.com/google-research/robotics_transformer) ⚠️ Archived] \[[Website](https://robotics-transformer.github.io/)]
* **Robogen**: "A generative and self-guided robotic agent that endlessly propose and master new skills.", *arXiv, Nov 2023*. \[[Paper](https://arxiv.org/abs/2311.01455)] \[[Code](https://github.com/Genesis-Embodied-AI/RoboGen) ⭐ 1,227 | 🐛 6 | 🌐 Python | 📅 2024-05-31] \[[Website](https://robogen-ai.github.io/)]
* **ReKep**: "ReKep: Spatio-Temporal Reasoning of Relational Keypoint Constraints for Robotic Manipulation", *arXiv, Sep 2024*. \[[Paper](https://arxiv.org/abs/2409.01652)] \[[Code](https://github.com/huangwl18/ReKep) ⭐ 983 | 🐛 37 | 🌐 Python | 📅 2025-02-20] \[[Website](https://rekep-robot.github.io)]
* **TidyBot**: "Personalized Robot Assistance with Large Language Models",  *arXiv, May 2023*. \[[Paper](https://arxiv.org/abs/2305.05658)] \[[Pytorch Code](https://github.com/jimmyyhwu/tidybot/tree/main/robot) ⭐ 695 | 🐛 0 | 🌐 Python | 📅 2023-11-10] \[[Website](https://tidybot.cs.princeton.edu/)]
* **LEO**: "An Embodied Generalist Agent in 3D World", *arXiv, Nov 2023*. \[[Paper](https://arxiv.org/abs/2311.12871)] \[[Code](https://github.com/embodied-generalist/embodied-generalist) ⭐ 488 | 🐛 0 | 🌐 Python | 📅 2025-04-20] \[[Website](https://embodied-generalist.github.io/)]
* **Instruct2Act**: "Mapping Multi-modality Instructions to Robotic Actions with Large Language Model", *arXiv, May 2023*. \[[Paper](https://arxiv.org/abs/2305.11176)]  \[[Pytorch Code](https://github.com/OpenGVLab/Instruct2Act) ⭐ 374 | 🐛 0 | 🌐 Python | 📅 2024-06-23]
* **RoboRefer**: "RoboRefer: Towards Spatial Referring with Reasoning in Vision-Language Models for Robotics", *arXiv, June 2025*. \[[Paper](https://arxiv.org/abs/2506.04308)] \[[Code](https://github.com/Zhoues/RoboRefer) ⭐ 266 | 🐛 16 | 🌐 Python | 📅 2025-12-16] \[[Website](https://zhoues.github.io/RoboRefer/)]
* **RoboSpatial**: "RoboSpatial: Teaching Spatial Understanding to 2D and 3D Vision-Language Models for Robotics", CVPR, June 2025. \[[Paper](https://arxiv.org/abs/2411.16537)] \[[Code](https://github.com/NVlabs/RoboSpatial) ⭐ 150 | 🐛 0 | 🌐 Python | 📅 2026-06-17] \[[Website](https://chanh.ee/RoboSpatial/)]
* **MoMa-LLM**: "Language-Grounded Dynamic Scene Graphs for Interactive Object Search with Mobile Manipulation", *arXiv, Mar 2024*. \[[Paper](https://arxiv.org/abs/2403.08605)] \[[Code](https://github.com/robot-learning-freiburg/MoMa-LLM) ⭐ 109 | 🐛 0 | 🌐 Python | 📅 2024-07-31] \[[Website](http://moma-llm.cs.uni-freiburg.de/)]
* **RoboTracer**: "RoboTracer: Mastering Spatial Trace with Reasoning in Vision-Language Models for Robotics", *arXiv, Dec 2025*. \[[Paper](https://arxiv.org/abs/2512.13660)] \[[Code](https://github.com/Zhoues/RoboTracer) ⭐ 83 | 🐛 4 | 🌐 Python | 📅 2026-06-18] \[[Website](https://zhoues.github.io/RoboTracer/)]
* **Octopi**: "Octopi: Object Property Reasoning with Large Tactile-Language Models", *Robotics: Science and Systems (RSS), June 24*. \[[Paper](https://arxiv.org/abs/2405.02794)] \[[Code](https://github.com/clear-nus/octopi) ⭐ 76 | 🐛 1 | 🌐 Python | 📅 2026-06-19] \[[Website](https://octopi-tactile-lvlm.github.io/)]
* **PIGLeT**: "PIGLeT: Language Grounding Through Neuro-Symbolic Interaction in a 3D World", *ACL, Jun 2021*. \[[Paper](https://arxiv.org/abs/2201.07207)] \[[Pytorch Code](http://github.com/rowanz/piglet) ⭐ 57 | 🐛 1 | 🌐 Python | 📅 2021-10-29] \[[Website](https://rowanzellers.com/piglet/)]
* **Matcha**: "Chat with the Environment: Interactive Multimodal Perception using   Large Language Models", *IROS, Mar 2023*. \[[Paper](https://arxiv.org/abs/2303.08268)] \[[Github](https://github.com/xf-zhao/Matcha) ⭐ 29 | 🐛 0 | 🌐 Python | 📅 2024-08-25] \[[Website](https://matcha-model.github.io/)]
* **CoExp**: "Multimodal Coherent Explanation Generation of Robot Failures", IROS, 2024. \[[Paper](https://arxiv.org/abs/2410.00659)] \[[Code](https://github.com/pradippramanick/coexp-iros24) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-05-07] \[[Website](https://pradippramanick.github.io/coherent-explain/)]
* **RobotxR1**: "RobotxR1: Enabling Embodied Robotic Intelligence on Large Language Models through Closed-Loop Reinforcement Learning", *arXiv, May 2025*. \[[Paper](https://arxiv.org/abs/2505.03238)]
* **SPINE**: "SPINE: Online Semantic Planning for Missions with Incomplete Natural Language Specifications in Unstructured Environments", *International Conference on Robotics and Automation (ICRA), May 2025*. \[[Paper](https://arxiv.org/abs/2410.03035)] \[[Website](https://zacravichandran.github.io/SPINE/)]
* **ELLMER**: "Embodied large language models enable robots to complete long-horizon tasks in unpredictable settings", *Nature Machine Intelligence, Mar 2025*. \[[Paper](https://www.nature.com/articles/s42256-025-01005-x)] \[[Website](https://www.nature.com/articles/s42256-025-01005-x)]
* **AHA**: "AHA: A Vision-Language-Model for Detecting and Reasoning over Failures in Robotic Manipulation", *arXiv, Oct 2024*. \[[Paper](https://arxiv.org/abs/2410.00371)] \[[Website](https://aha-vlm.github.io/)]
* **CLEAR**: "Language, Camera, Autonomy! Prompt-engineered Robot Control for Rapidly Evolving Deployment", *ACM/IEEE International Conference on Human-Robot Interaction (HRI), Mar 2024*. \[[Paper](https://dl.acm.org/doi/10.1145/3610978.3640671)] \[[Code](https://github.com/MITLL-CLEAR)]
* **AutoRT**: "Embodied Foundation Models for Large Scale Orchestration of Robotic Agents", *arXiv, Jan 2024*. \[[Paper](https://arxiv.org/abs/2401.12963)] \[[Website](https://auto-rt.github.io/)]
* **LLM-State**: "LLM-State: Open World State Representation for Long-horizon Task Planning with Large Language Model", *arXiv, Nov 2023*. \[[Paper](https://arxiv.org/abs/2311.17406)]
* **SayPlan**: "Grounding Large Language Models using 3D Scene Graphs for Scalable Robot Task Planning", *Conference on Robot Learning (CoRL), Nov 2023*. \[[Paper](https://arxiv.org/abs/2307.06135)] \[[Website](https://sayplan.github.io/)]
* **\[LLaRP]** "Large Language Models as Generalizable Policies for Embodied Tasks", *arXiv, Oct 2023*. \[[Paper](https://arxiv.org/abs/2310.17722)] \[[Website](https://llm-rl.github.io)]
* **\[RT-X]** "Open X-Embodiment: Robotic Learning Datasets and RT-X Models", *arXiv, July 2023*. \[[Paper](https://arxiv.org/abs/2310.08864)] \[[Website](https://robotics-transformer-x.github.io/)]
* **\[RT-2]** "RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control", *arXiv, July 2023*. \[[Paper](https://arxiv.org/abs/2307.15818)] \[[Website](https://robotics-transformer2.github.io/)]
* **PaLM-E**: "PaLM-E: An Embodied Multimodal Language Model", *arXiv, Mar 2023*, \[[Paper](https://arxiv.org/abs/2303.03378)] \[[Webpage](https://palm-e.github.io/)]
* "Large Language Models as Zero-Shot Human Models for Human-Robot Interaction", *arXiv, Mar 2023*. \[[Paper](https://arxiv.org/abs/2303.03548v1)]
* **CortexBench** "Where are we in the search for an Artificial Visual Cortex for Embodied Intelligence?" *arXiv, Mar 2023*. \[[Paper](https://arxiv.org/abs/2303.18240)]
* "Translating Natural Language to Planning Goals with Large-Language Models", *arXiv, Feb 2023*. \[[Paper](https://arxiv.org/abs/2302.05128)]
* "PDDL Planning with Pretrained Large Language Models", *NeurIPS, Oct 2022*. \[[Paper](https://openreview.net/forum?id=1QMMUB4zfl)] \[[Github](https://tinyurl.com/llm4pddl)]
* **ProgPrompt**: "Generating Situated Robot Task Plans using Large Language Models", *arXiv, Sept 2022*. \[[Paper](https://arxiv.org/abs/2209.11302)]  \[[Github](https://github.com/progprompt/progprompt)] \[[Website](https://progprompt.github.io/)]
* **Say-Can**: "Do As I Can, Not As I Say: Grounding Language in Robotic Affordances", *arXiv, Apr 2021*. \[[Paper](https://arxiv.org/abs/2204.01691)]  \[[Colab](https://say-can.github.io/#open-source)] \[[Website](https://say-can.github.io/)]
* **Socratic**: "Socratic Models: Composing Zero-Shot Multimodal Reasoning with Language", *arXiv, Apr 2021*. \[[Paper](https://arxiv.org/abs/2204.00598)] \[[Pytorch Code](https://socraticmodels.github.io/#code)] \[[Website](https://socraticmodels.github.io/)]

***

## Planning

* **ReAct**: "ReAct: Synergizing Reasoning and Acting in Language Models", *ICLR, Apr 2023*. \[[Paper](https://arxiv.org/abs/2210.03629)] \[[Github](https://github.com/ysymyth/ReAct) ⭐ 4,134 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2024-02-06] \[[Website](https://react-lm.github.io/)]
* **LLM+P**:"LLM+P: Empowering Large Language Models with Optimal Planning Proficiency", *arXiv, Apr 2023*, \[[Paper](https://arxiv.org/abs/2304.11477)] \[[Code](https://github.com/Cranial-XIX/llm-pddl) ⭐ 462 | 🐛 5 | 🌐 SAS | 📅 2023-09-27]
* **ChatGPT-Prompts**: "ChatGPT Empowered Long-Step Robot Control in Various Environments: A Case Application", *arXiv, Apr 2023*, \[[Paper](https://arxiv.org/abs/2304.03893?s=03)] \[[Code/Prompts](https://github.com/microsoft/ChatGPT-Robot-Manipulation-Prompts) ⭐ 386 | 🐛 1 | 📅 2023-11-28]
* **Co-LLM-Agents**: "Building Cooperative Embodied Agents Modularly with Large Language Models", *arXiv, Jul 2023*. \[[Paper](https://arxiv.org/abs/2307.02485)] \[[Code](https://github.com/UMass-Foundation-Model/Co-LLM-Agents) ⭐ 307 | 🐛 6 | 🌐 Python | 📅 2025-03-30] \[[Website](https://vis-www.cs.umass.edu/Co-LLM-Agents/)]
* **ZSP**: "Language Models as Zero-Shot Planners: Extracting Actionable Knowledge for Embodied Agents", *ICML, Jan 2022*. \[[Paper](https://arxiv.org/abs/2201.07207)] \[[Pytorch Code](https://github.com/huangwl18/language-planner) ⭐ 280 | 🐛 6 | 🌐 Jupyter Notebook | 📅 2022-05-16] \[[Website](https://wenlong.page/language-planner/)]
* **GLAM**: "Grounding Large Language Models in Interactive Environments with Online Reinforcement Learning", *arXiv, May 2023*. \[[Paper](https://arxiv.org/abs/2302.02662)] \[[Pytorch Code](https://github.com/flowersteam/Grounding_LLMs_with_online_RL) ⭐ 275 | 🐛 11 | 🌐 Python | 📅 2025-10-27]
* **LM-Nav**: "Robotic Navigation with Large Pre-Trained Models of Language, Vision, and Action", *arXiv, July 2022*. \[[Paper](https://arxiv.org/abs/2207.04429)] \[[Pytorch Code](https://github.com/blazejosinski/lm_nav) ⭐ 270 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2025-01-14] \[[Website](https://sites.google.com/view/lmnav)]
* **LLM-planner**: "LLM-Planner: Few-Shot Grounded Planning for Embodied Agents with Large Language Models", *ICCV, Mar 2023*. \[[Paper](https://arxiv.org/abs/2212.04088)] \[[Pytorch Code](https://github.com/OSU-NLP-Group/LLM-Planner/) ⭐ 227 | 🐛 2 | 🌐 C | 📅 2025-03-26] \[[Website](https://dki-lab.github.io/LLM-Planner/)]
* "Reward Design with Language Models", *ICML, Feb 2023*. \[[Paper](https://arxiv.org/abs/2303.00001v1)] \[[Pytorch Code](https://github.com/minaek/reward_design_with_llms) ⭐ 223 | 🐛 3 | 🌐 Python | 📅 2023-06-06]
* **BTGenBot**: "BTGenBot: Behavior Tree Generation for Robotic Tasks with Lightweight LLMs", *IROS, Mar 2024*. \[[Paper](https://ieeexplore.ieee.org/document/10802304)]\[[Github](https://github.com/AIRLab-POLIMI/BTGenBot) ⭐ 135 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-05-26]
* **LID**: "Pre-Trained Language Models for Interactive Decision-Making", *arXiv, Feb 2022*. \[[Paper](https://arxiv.org/abs/2202.01771)] \[[Pytorch Code](https://github.com/ShuangLI59/Language-Model-Pre-training-Improves-Generalization-in-Policy-Learning) ⭐ 131 | 🐛 5 | 🌐 Python | 📅 2022-06-08] \[[Website](https://shuangli-project.github.io/Pre-Trained-Language-Models-for-Interactive-Decision-Making/)]
* **FILM**: "FILM: Following Instructions in Language with Modular Methods", *ICLR, Apr 2022*. \[[Paper](https://arxiv.org/abs/2110.07342)] \[[Code](https://github.com/soyeonm/FILM) ⭐ 128 | 🐛 24 | 🌐 Python | 📅 2023-04-09] \[[Website](https://soyeonm.github.io/FILM_webpage/)]
* **LLM3**: "LLM3: Large Language Model-based Task and Motion Planning with Motion Failure Reasoning", *IROS, Mar 2024*. \[[Paper](https://arxiv.org/abs/2403.11552)]\[[Code](https://github.com/AssassinWS/LLM-TAMP) ⭐ 99 | 🐛 1 | 🌐 Python | 📅 2024-05-30]
* **CALM**: "Keep CALM and Explore: Language Models for Action Generation in Text-based Games", *arXiv, Oct 2020*. \[[Paper](https://arxiv.org/abs/2010.02903)] \[[Pytorch Code](https://github.com/princeton-nlp/calm-textgame) ⭐ 74 | 🐛 2 | 🌐 Python | 📅 2021-02-22]
* **SayCanPay**: "SayCanPay: Heuristic Planning with Large Language Models Using Learnable Domain Knowledge", AAAI Jan 2024, \[[Paper](https://arxiv.org/abs/2308.12682)] \[[Code](https://github.com/RishiHazra/saycanpay) ⭐ 55 | 🐛 1 | 🌐 Python | 📅 2025-10-22] \[[Website](https://rishihazra.github.io/SayCanPay/)]
* **Housekeep**: "Housekeep: Tidying Virtual Households using Commonsense Reasoning", *arXiv, May 2022*. \[[Paper](https://arxiv.org/abs/2205.10712)] \[[Pytorch Code](https://github.com/yashkant/housekeep) ⭐ 52 | 🐛 1 | 🌐 Python | 📅 2023-04-27] \[[Website](https://yashkant.github.io/housekeep/)]
* **Attentive Support**: "To Help or Not to Help: LLM-based Attentive Support for Human-Robot Group Interactions", *arXiv, March 2024*. \[[Paper](https://arxiv.org/abs/2403.12533)] \[[Website](https://hri-eu.github.io/AttentiveSupport/)]\[[Code](https://github.com/HRI-EU/AttentiveSupport) ⭐ 38 | 🐛 0 | 🌐 Python | 📅 2025-08-01]
* **COWP**: "Robot Task Planning and Situation Handling in Open Worlds", *arXiv, Oct 2022*. \[[Paper](https://arxiv.org/abs/2210.01287)] \[[Pytorch Code](https://github.com/yding25/GPT-Planner) ⭐ 37 | 🐛 1 | 🌐 Python | 📅 2024-04-23] \[[Website](https://cowplanning.github.io/)]
* **FLARE**: "Multi-Modal Grounded Planning and Efficient Replanning For Learning Embodied Agents with a Few Examples", *AAAI, Mar 2025*. \[[Paper](https://arxiv.org/abs/2412.17288)] \[[Code](https://github.com/snumprlab/flare) ⭐ 34 | 🐛 4 | 🌐 Python | 📅 2025-11-27]
* **LABOR Agent**: "Large Language Models for Orchestrating Bimanual Robots", Humanoids, Nov. 2024. \[[Paper](https://arxiv.org/abs/2404.02018)] \[[Website](https://labor-agent.github.io/)], \[[Code](https://github.com/Kchu/LABOR-Agent) ⭐ 24 | 🐛 1 | 🌐 Python | 📅 2024-11-23]
* **LLM+MAP**: "LLM+MAP: Bimanual Robot Task Planning using Large Language Models and Planning Domain Definition Language", *arxiv, Mar 2025*. \[[Paper](https://arxiv.org/abs/2503.17309)] \[[Code](https://github.com/Kchu/LLM-MAP) ⭐ 23 | 🐛 1 | 📅 2025-03-24]
* **LLM-Personalize**: "LLM-Personalize: Aligning LLM Planners with Human Preferences via Reinforced Self-Training for Housekeeping Robots", *arXiv, Apr 2024*. \[[Paper](https://arxiv.org/abs/2404.14285)] \[[Website](https://donggehan.github.io/projectllmpersonalize/)] \[[Code](https://github.com/donggehan/codellmpersonalize/) ⭐ 19 | 🐛 1 | 🌐 Python | 📅 2024-08-09]
* **FLTRNN**: "FLTRNN: Faithful Long-Horizon Task Planning for Robotics with Large Language Models", *ICRA, May 17th 2024*, \[[Paper](https://ieeexplore.ieee.org/document/10611663)] \[[Code](https://github.com/tannl/FLTRNN) ⭐ 14 | 🐛 4 | 🌐 Python | 📅 2024-12-09] \[[Website](https://tannl.github.io/FLTRNN.github.io/)]
* **Wonderful Team**: "Solving Robotics Problems in Zero-Shot with Vision-Language Models", *arXiv, Jul 2024*. \[[Paper](https://www.arxiv.org/abs/2407.19094)] \[[Code](https://github.com/wonderful-team-robotics/wonderful_team_robotics) ⭐ 11 | 🐛 2 | 🌐 Python | 📅 2025-02-04] \[[Website](https://wonderful-team-robotics.github.io/)]
* **CoPAL**: "Corrective Planning of Robot Actions with Large Language Models", *ICRA, Oct 2023*. \[[Paper](https://arxiv.org/abs/2310.07263)] \[[Website](https://hri-eu.github.io/Loom/)]\[[Code](https://github.com/HRI-EU/Loom/tree/main) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2024-09-08]
* **PRED**: "Pre-emptive Action Revision by Environmental Feedback for Embodied Instruction Following Agents", *CoRL, Sept 2024*. \[[Paper](https://openreview.net/pdf?id=cq2uB30uBM)] \[[Code](https://github.com/snumprlab/pred) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2024-11-30]
* **Code-as-Monitor**: "Constraint-aware Visual Programming for Reactive and Proactive Robotic Failure Detection", CVPR, 2025. \[[Paper](https://arxiv.org/abs/2412.04455)] \[[Project](https://zhoues.github.io/Code-as-Monitor/)]
* **SELP**: "SELP: Generating Safe and Efficient Task Plans for Robot Agents with Large Language Models", *arXiv, Sept 2024*. \[[Paper](https://arxiv.org/abs/2409.19471)]
* **Embodied AI in Mobile Robots**: Coverage Path Planning with Large Language Models", *arXiV, Jul 2024*, \[[Paper](https://arxiv.org/abs/2407.02220)]
* **Beyond Text**: "Beyond Text: Improving LLM's Decision Making for Robot Navigation via Vocal Cues", *arxiv, Feb 2024*. \[[Paper](https://arxiv.org/abs/2402.03494)]
* **ViLa**: "Look Before You Leap: Unveiling the Power of GPT-4V in Robotic Vision-Language Planning", *arXiv, Sep 2023*, \[[Paper](https://arxiv.org/abs/2311.17842)] \[[Website](https://robot-vila.github.io/)]
* **LGMCTS**: "LGMCTS: Language-Guided Monte-Carlo Tree Search for Executable Semantic Object Rearrangement", *arXiv, Sep 2023*. \[[Paper](https://arxiv.org/abs/2309.15821)]
* **Prompt2Walk**: "Prompt a Robot to Walk with Large Language Models", *arXiv, Sep 2023*, \[[Paper](https://arxiv.org/abs/2309.09969)] \[[Website](https://prompt2walk.github.io)]
* **DoReMi**: "Grounding Language Model by Detecting and Recovering from Plan-Execution Misalignment", *arXiv, July 2023*, \[[Paper](https://arxiv.org/abs/2307.00329)] \[[Website](https://sites.google.com/view/doremi-paper)]
* **LLM-Reward**: "Language to Rewards for Robotic Skill Synthesis", *arXiv, Jun 2023*. \[[Paper](https://arxiv.org/abs/2306.08647)] \[[Website](https://language-to-reward.github.io/)]
* **LLM-BRAIn**: "LLM-BRAIn: AI-driven Fast Generation of Robot Behaviour Tree based on Large Language Model", *arXiv, May 2023*. \[[Paper](https://arxiv.org/abs/2305.19352)]
* **LLM-MCTS**: "Large Language Models as Commonsense Knowledge for Large-Scale Task Planning", *arXiv, May 2023*. \[[Paper](https://arxiv.org/abs/2305.14078v1)]
* **AlphaBlock**: "AlphaBlock: Embodied Finetuning for Vision-Language Reasoning in Robot Manipulation", *arxiv, May 2023*. \[[Paper](https://arxiv.org/abs/2305.18898)]
* **LLM-Brain**: "LLM as A Robotic Brain: Unifying Egocentric Memory and Control", arXiv, Apr 2023. \[[Paper](https://arxiv.org/abs/2304.09349v1)]
* "Foundation Models for Decision Making: Problems, Methods, and Opportunities", *arXiv, Mar 2023*, \[[Paper](https://arxiv.org/abs/2303.04129)]
* **Text2Motion**: "Text2Motion: From Natural Language Instructions to Feasible Plans", *arXiV, Mar 2023*, \[[Paper](https://arxiv.org/abs/2303.12153)] \[[Website](https://sites.google.com/stanford.edu/text2motion)]
* **GD**: "Grounded Decoding: Guiding Text Generation with Grounded Models for Robot Control", *arXiv, Mar 2023*. \[[Paper](https://arxiv.org/abs/2303.00855)] \[[Website](https://grounded-decoding.github.io/)]
* **PromptCraft**: "ChatGPT for Robotics: Design Principles and Model Abilities", *Blog, Feb 2023*, \[[Paper](https://arxiv.org/abs/2306.17582)] \[[Website](https://www.microsoft.com/en-us/research/group/autonomous-systems-group-robotics/articles/chatgpt-for-robotics/)]
* "Planning with Large Language Models via Corrective Re-prompting", *arXiv, Nov 2022*. \[[Paper](https://arxiv.org/abs/2311.09935)]
* **Don't Copy the Teacher**: "Don’t Copy the Teacher: Data and Model Challenges in Embodied Dialogue", *EMNLP, Oct 2022*. \[[Paper](https://arxiv.org/abs/2210.04443)] \[[Website](https://www.youtube.com/watch?v=qGPC65BDJw4\&t=2s)]
* **InnerMonlogue**: "Inner Monologue: Embodied Reasoning through Planning with Language Models", *arXiv, July 2022*. \[[Paper](https://arxiv.org/abs/2207.05608)] \[[Website](https://innermonologue.github.io/)]
* **MOO**: "Open-World Object Manipulation using Pre-Trained Vision-Language Models", *arXiv, Mar 2022*. \[[Paper](https://arxiv.org/abs/2303.00905)] \[[Website](https://robot-moo.github.io/)]
* "Collaborating with language models for embodied reasoning", *NeurIPS, Feb 2022*. \[[Paper](https://arxiv.org/abs/2302.00763v1)]
* "Visually-Grounded Planning without Vision: Language Models Infer Detailed Plans from High-level Instructions", *arXiV, Oct 2020*, \[[Paper](https://arxiv.org/abs/2009.14259)]

***

## Manipulation

* **VOYAGER**:"VOYAGER: An Open-Ended Embodied Agent with Large Language Models", *arXiv, May 2023*. \[[Paper](https://arxiv.org/abs/2305.16291)] \[[Pytorch Code](https://github.com/MineDojo/Voyager) ⭐ 7,168 | 🐛 8 | 🌐 JavaScript | 📅 2024-04-03] \[[Website](https://voyager.minedojo.org/)]
* **VIMA**:"VIMA: General Robot Manipulation with Multimodal Prompts", *arXiv, Oct 2022*, \[[Paper](https://arxiv.org/abs/2210.03094)] \[[Pytorch Code](https://github.com/vimalabs/VIMA) ⭐ 858 | 🐛 14 | 🌐 Python | 📅 2024-04-18] \[[Website](https://vimalabs.github.io/)]
* **CLIPort**: "CLIPort: What and Where Pathways for Robotic Manipulation", *CoRL, Sept 2021*. \[[Paper](https://arxiv.org/abs/2109.12098)] \[[Pytorch Code](https://github.com/cliport/cliport) ⭐ 549 | 🐛 16 | 🌐 Jupyter Notebook | 📅 2023-11-02] \[[Website](https://cliport.github.io/)]
* **Perceiver-Actor**:"A Multi-Task Transformer for Robotic Manipulation", *CoRL, Sep 2022*. \[[Paper](https://arxiv.org/abs/2209.05451)] \[[Pytorch Code](https://github.com/peract/peract) ⭐ 497 | 🐛 17 | 🌐 Python | 📅 2024-05-09] \[[Website](https://peract.github.io/)]
* **Scalingup**: "Scaling Up and Distilling Down: Language-Guided Robot Skill Acquisition", *arXiv, July 2023*. \[[Paper](https://arxiv.org/abs/2307.14535)] \[[Code](https://github.com/columbia-ai-robotics/scalingup) ⭐ 414 | 🐛 8 | 🌐 Python | 📅 2024-08-12] \[[Website](https://www.cs.columbia.edu/~huy/scalingup/)]
* **R3M**:"R3M: A Universal Visual Representation for Robot Manipulation", *arXiv, Nov 2022*, \[[Paper](https://arxiv.org/abs/2203.12601)] \[[Pytorch Code](https://github.com/facebookresearch/r3m) ⚠️ Archived] \[[Website](https://tinyurl.com/robotr3m)]
* **Octopus**:"Octopus: Embodied Vision-Language Programmer from Environmental Feedback", *arXiv, Oct 2023*, \[[Paper](https://arxiv.org/abs/2310.08588)] \[[PyTorch Code](https://github.com/dongyh20/Octopus) ⭐ 301 | 🐛 6 | 🌐 Python | 📅 2024-05-20] \[[Website](https://choiszt.github.io/Octopus/)]
* **DEPS**:"Describe, Explain, Plan and Select: Interactive Planning with Large Language Models Enables Open-World Multi-Task Agents", *arXiv, Feb 2023*. \[[Paper](https://arxiv.org/abs/2302.01560)] \[[Pytorch Code](https://github.com/CraftJarvis/MC-Planner) ⭐ 294 | 🐛 7 | 🌐 Python | 📅 2023-08-03]
* **RL4VLA**: "RL4VLA:What Can RL Bring to VLA Generalization? An Empirical Study", *NeurIPS, Sep 2025*.. \[[Paper](https://arxiv.org/abs/2505.19789)] \[[Code](https://github.com/gen-robot/RL4VLA) ⭐ 285 | 🐛 6 | 🌐 Python | 📅 2025-08-25] \[[Website](https://rlvla.github.io/)]
* **Plan4MC**:"Plan4MC: Skill Reinforcement Learning and Planning for Open-World Minecraft Tasks", *arXiv, Mar 2023*. \[[Paper](https://arxiv.org/abs/2303.16563)] \[[Pytorch Code](https://github.com/PKU-RL/Plan4MC) ⭐ 201 | 🐛 4 | 🌐 Python | 📅 2024-03-06] \[[Website](https://sites.google.com/view/plan4mc)]
* **CLIP-Fields**:"CLIP-Fields: Weakly Supervised Semantic Fields for Robotic Memory", *arXiv, Oct 2022*, \[[Paper](https://arxiv.org/abs/2210.05663)] \[[PyTorch Code](https://github.com/notmahi/clip-fields) ⭐ 190 | 🐛 1 | 🌐 Python | 📅 2024-03-02] \[[Website](https://mahis.life/clip-fields/)]
* **RoboSpatial**: "RoboSpatial: Teaching Spatial Understanding to 2D and 3D Vision-Language Models for Robotics", CVPR, June 2025. \[[Paper](https://arxiv.org/abs/2411.16537)] \[[Code](https://github.com/NVlabs/RoboSpatial) ⭐ 150 | 🐛 0 | 🌐 Python | 📅 2026-06-17] \[[Website](https://chanh.ee/RoboSpatial/)]
* **LIV**:"LIV: Language-Image Representations and Rewards for Robotic Control", *arXiv, Jun 2023*, \[[Paper](https://arxiv.org/abs/2306.00958)] \[[Pytorch Code](https://github.com/penn-pal-lab/LIV) ⭐ 135 | 🐛 9 | 🌐 Python | 📅 2023-10-19] \[[Website](https://penn-pal-lab.github.io/LIV/)]
* **Plan-Seq-Learn**:"Plan-Seq-Learn: Language Model Guided RL for Solving Long Horizon Robotics Tasks", *ICLR, May 2024*. \[[Paper](https://arxiv.org/abs/2405.01534)], \[[PyTorch Code](https://github.com/mihdalal/planseqlearn) ⭐ 131 | 🐛 6 | 🌐 Python | 📅 2024-08-21] \[[Website](https://mihdalal.github.io/planseqlearn/)]
* **Embodied-CLIP**: "Simple but Effective: CLIP Embeddings for Embodied AI", *CVPR, Nov 2021*. \[[Paper](https://arxiv.org/abs/2111.09888)] \[[Pytorch Code](https://github.com/allenai/embodied-clip) ⭐ 130 | 🐛 0 | 🌐 Python | 📅 2023-06-16]
* **A3VLM**: "A3VLM: Actionable Articulation-Aware Vision Language Model", *CoRL, Nov 2024*. \[[Paper](https://arxiv.org/abs/2406.07549)] \[[PyTorch Code](https://github.com/changhaonan/A3VLM) ⭐ 122 | 🐛 6 | 🌐 Python | 📅 2024-10-07]
* **ManipVQA**:"ManipVQA: Injecting Robotic Affordance and Physically Grounded Information into Multi-Modal Large Language Models", *IROS, Mar 2024*, \[[Paper](https://arxiv.org/abs/2403.11289)] \[[PyTorch Code](https://github.com/SiyuanHuang95/ManipVQA) ⭐ 102 | 🐛 0 | 🌐 Python | 📅 2024-08-22]
* **D2E**: "D2E: Scaling Vision-Action Pretraining on Desktop Data for Transfer to Embodied AI", *arXiv, Oct 2025*. \[[Paper](https://arxiv.org/abs/2510.05684)] \[[Code](https://github.com/worv-ai/D2E) ⭐ 92 | 🐛 1 | 🌐 Python | 📅 2026-07-16] \[[Website](https://worv-ai.github.io/d2e/)]
* **LaTTe**: "LaTTe: Language Trajectory TransformEr", *arXiv, Aug 2022*. \[[Paper](https://arxiv.org/abs/2208.02918)] \[[TensorFlow Code](https://github.com/arthurfenderbucker/NL_trajectory_reshaper) ⭐ 60 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2022-12-14] \[[Website](https://www.microsoft.com/en-us/research/group/autonomous-systems-group-robotics/articles/robot-language/)]
* **CoTPC**:"Chain-of-Thought Predictive Control", *arXiv, Apr 2023*, \[[Paper](https://arxiv.org/abs/2304.00776)] \[[Code](https://github.com/SeanJia/CoTPC) ⭐ 56 | 🐛 3 | 🌐 Python | 📅 2023-05-01]
* **LILAC**:"No, to the Right – Online Language Corrections for Robotic Manipulation via Shared Autonomy", *arXiv, Jan 2023*, \[[Paper](https://arxiv.org/abs/2301.02555)] \[[Pytorch Code](https://github.com/Stanford-ILIAD/lilac) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2022-12-13]
* **LLM-TALE**: "LLM-Guided Task- and Affordance-Level Exploration in Reinforcement Learning", *arXiv, Sep 2025*. \[[Paper](https://arxiv.org/pdf/2509.16615)] \[[Code](https://github.com/llm-tale/llm_tale) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2026-04-17] \[[Website](https://github.com/llm-tale/llm_tale) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2026-04-17]
* **Prompt2Act**: "Prompt2Act: Mapping Prompts into Sequence of Robotic Actions with Large Foundation Models", *arxiv, Sep 2025*. \[[Paper](https://arxiv.org/abs/2505.19789)] \[[Code](https://github.com/Zero-coder/Prompt2Act) ⭐ 3 | 🐛 1 | 📅 2025-09-29]
* **Meta-Control**: "Meta-Control: Automatic Model-based Control System Synthesis for Heterogeneous Robot Skills", *CoRL, Nov 2024*. \[[Paper](https://arxiv.org/abs/2405.11380)] \[[Website](https://meta-control-paper.github.io/)]
* **Manipulate-Anything**: "Manipulate-Anything: Automating Real-World Robots using Vision-Language Models", *CoRL, Nov 2024*. \[[Paper](https://arxiv.org/abs/2406.18915)] \[[Website](https://robot-ma.github.io/)]
* **RobiButler**: "RobiButler: Remote Multimodal Interactions with Household Robot Assistant", *arXiv, Sept 2024*. \[[Paper](https://arxiv.org/abs/2409.20548)] \[[Website](https://robibutler.github.io/)]
* **SKT**: "SKT: Integrating State-Aware Keypoint Trajectories with Vision-Language Models for Robotic Garment Manipulation", *arXiv, Sept 2024*.  \[[Paper](https://arxiv.org/abs/2409.18082)] \[[Website](https://sites.google.com/view/keypoint-garment/home)]
* **UniAff**: "UniAff: A Unified Representation of Affordances for Tool Usage and Articulation with Vision-Language Models", *arXiv, Sept 2024*.  \[[Paper](https://arxiv.org/abs/2409.20551)] \[[Website](https://sites.google.com/view/uni-aff)]
* **ExploRLLM**:"ExploRLLM: Guiding Exploration in Reinforcement Learning with Large Language Models", *arXiv, Mar 2024*. \[[Paper](https://arxiv.org/abs/2403.09583)] \[[Website](https://explorllm.github.io/)]
* **BOSS**: "Bootstrap Your Own Skills: Learning to Solve New Tasks with LLM Guidance", *CoRL, Nov 2023*. \[[Paper](https://openreview.net/forum?id=a0mFRgadGO)] \[[Website](https://clvrai.github.io/boss/)]
* **Lafite-RL**: "Accelerating Reinforcement Learning of Robotic Manipulations via Feedback from Large Language Models", *CoRL Workshop, Nov 2023*. \[[Paper](https://arxiv.org/abs/2311.02379)]
* **\[Text2Reward]** "Text2Reward: Automated Dense Reward Function Generation for Reinforcement Learning", *arXiv, Sep 2023*, \[[Paper](https://arxiv.org/abs/2309.11489)] \[[Website](https://text-to-reward.github.io/)]
* **PhysObjects**: "Physically Grounded Vision-Language Models for Robotic Manipulation", *arxiv, Sept 2023*. \[[Paper](https://arxiv.org/abs/2309.02561)]
* **\[VoxPoser]** "VoxPoser: Composable 3D Value Maps for Robotic Manipulation with Language Models", *arXiv, July 2023*, \[[Paper](https://arxiv.org/abs/2307.05973)] \[[Website](https://voxposer.github.io/)]
* **VoxPoser**:"VoxPoser: Composable 3D Value Maps for Robotic Manipulation with Language Models", *arXiv, Jul 2023*. \[[Paper](https://arxiv.org/abs/2307.05973)] \[[Website](https://voxposer.github.io/)]
* "Language Instructed Reinforcement Learning for Human-AI Coordination", *arXiv, Jun 2023*. \[[Paper](https://arxiv.org/abs/2304.07297)]
* **RoboCat**: "RoboCat: A self-improving robotic agent", *arxiv, Jun 2023*. \[[Paper](https://arxiv.org/abs/2306.11706)]  \[[Website](https://www.deepmind.com/blog/robocat-a-self-improving-robotic-agent)]
* **SPRINT**: "SPRINT: Semantic Policy Pre-training via Language Instruction Relabeling", *arxiv, June 2023*. \[[Paper](https://arxiv.org/abs/2306.11886)] \[[Website](https://clvrai.github.io/sprint/)]
* **Grasp Anything**: "Pave the Way to Grasp Anything: Transferring Foundation Models for Universal Pick-Place Robots", *arxiv, June 2023*. \[[Paper](https://arxiv.org/abs/2306.05716)]
* **LLM-GROP**:"Task and Motion Planning with Large Language Models for Object Rearrangement", *arXiv, May 2023*. \[[Paper](https://arxiv.org/abs/2303.06247)] \[[Website](https://sites.google.com/view/llm-grop)]
* **TIP**: "Multimodal Procedural Planning via Dual Text-Image Prompting", *arXiV, May 2023*, \[[Paper](https://arxiv.org/abs/2305.01795)]
* **ProgramPort**:"Programmatically Grounded, Compositionally Generalizable Robotic Manipulation", *ICLR, Apr 2023*, \[[Paper](https://arxiv.org/abs/2304.13826)] \[\[Website] (<https://progport.github.io/>)]
* **VLaMP**: "Pretrained Language Models as Visual Planners for Human Assistance", *arXiV, Apr 2023*, \[[Paper](https://arxiv.org/abs/2304.09179)]
* "Towards a Unified Agent with Foundation Models", *ICLR, Apr 2023*. \[[Paper](https://www.semanticscholar.org/paper/TOWARDS-A-UNIFIED-AGENT-WITH-FOUNDATION-MODELS-Palo-Byravan/67188a50e1d8a601896f1217451b99f646af4ac8)]
* **ELLM**:"Guiding Pretraining in Reinforcement Learning with Large Language Models", *arXiv, Feb 2023*. \[[Paper](https://arxiv.org/abs/2302.06692)]
* **DIAL**:"Robotic Skill Acquistion via Instruction Augmentation with Vision-Language Models", *arXiv, Nov 2022*, \[[Paper](https://arxiv.org/abs/2211.11736)] \[[Website](https://instructionaugmentation.github.io/)]
* **Gato**: "A Generalist Agent", *TMLR, Nov 2022*. \[[Paper](https://arxiv.org/abs/2205.06175)]  \[[Website](https://www.deepmind.com/publications/a-generalist-agent)]
* **NLMap**:"Open-vocabulary Queryable Scene Representations for Real World Planning", *arXiv, Sep 2022*, \[[Paper](https://arxiv.org/abs/2209.09874)] \[[Website](https://nlmap-saycan.github.io/)]
* **Robots Enact Malignant Stereotypes**: "Robots Enact Malignant Stereotypes", *FAccT, Jun 2022*. \[[Paper](https://arxiv.org/abs/2207.11569)] \[[Pytorch Code](https://github.com/ahundt/RobotsEnactMalignantStereotypes)] \[[Website](https://sites.google.com/view/robots-enact-stereotypes/home)] \[[Washington Post](https://www.washingtonpost.com/technology/2022/07/16/racist-robots-ai/)] \[[Wired](https://www.wired.com/story/how-to-stop-robots-becoming-racist/)] (code access on request)
* **ATLA**: "Leveraging Language for Accelerated Learning of Tool Manipulation", *CoRL, Jun 2022*. \[[Paper](https://arxiv.org/abs/2206.13074)]
* **ZeST**: "Can Foundation Models Perform Zero-Shot Task Specification For Robot Manipulation?", *L4DC, Apr 2022*. \[[Paper](https://arxiv.org/abs/2204.11134)]
* **LSE-NGU**: "Semantic Exploration from Language Abstractions and Pretrained Representations", *arXiv, Apr 2022*. \[[Paper](https://arxiv.org/abs/2204.05080)]
* **MetaMorph**: "METAMORPH: LEARNING UNIVERSAL CONTROLLERS WITH TRANSFORMERS", *arxiv, Mar 2022*. \[[Paper](https://arxiv.org/abs/2203.11931)]

***

## Instructions and Navigation

* **VLMaps**: "Visual Language Maps for Robot Navigation", *arXiv, Mar 2023*. \[[Paper](https://arxiv.org/abs/2210.05714)] \[[Pytorch Code](https://github.com/vlmaps/vlmaps) ⭐ 720 | 🐛 16 | 🌐 Python | 📅 2024-07-09] \[[Website](https://vlmaps.github.io/)]
* **Recurrent VLN-BERT**: "A Recurrent Vision-and-Language BERT for Navigation", *CVPR, Jun 2021* \[[Paper](https://arxiv.org/abs/2011.13922)] \[[Pytorch Code](https://github.com/YicongHong/Recurrent-VLN-BERT) ⭐ 209 | 🐛 2 | 🌐 Python | 📅 2022-08-13]
* **RoboSpatial**: "RoboSpatial: Teaching Spatial Understanding to 2D and 3D Vision-Language Models for Robotics", *CVPR, June 2025*. \[[Paper](https://arxiv.org/abs/2411.16537)] \[[Code](https://github.com/NVlabs/RoboSpatial) ⭐ 150 | 🐛 0 | 🌐 Python | 📅 2026-06-17] \[[Website](https://chanh.ee/RoboSpatial/)]
* **LLMxRobot**: "Autonomous Driving Systems with On-Board LLMs", *RSS, Apr 2025* \[[Paper](https://www.roboticsproceedings.org/rss21/p140.pdf)]\[[Code](https://github.com/ForzaETH/LLMxRobot) ⭐ 104 | 🐛 0 | 🌐 Python | 📅 2025-10-17]\[[Website](https://www.youtube.com/watch?v=4iGN1uBl4v4)]
* **OVSG**: "Context-Aware Entity Grounding with Open-Vocabulary 3D Scene Graphs", *CoRL, Nov 2023*. \[[Paper](https://openreview.net/forum?id=cjEI5qXoT0)] \[[Code](https://github.com/changhaonan/OVSG) ⭐ 73 | 🐛 1 | 🌐 Python | 📅 2023-12-30] \[[Website](https://ovsg-l.github.io/)]
* **VLN-BERT**: "Improving Vision-and-Language Navigation with Image-Text Pairs from the Web", *ECCV, Apr 2020* \[[Paper](https://arxiv.org/abs/2004.14973)] \[[Pytorch Code](https://github.com/arjunmajum/vln-bert) ⭐ 59 | 🐛 3 | 🌐 Python | 📅 2022-10-07]
* "The Unsurprising Effectiveness of Pre-Trained Vision Models for Control", *ICML, Mar 2022*. \[[Paper](https://arxiv.org/abs/2203.03580)] \[[Pytorch Code](https://github.com/sparisi/pvr_habitat) ⭐ 21 | 🐛 2 | 🌐 Python | 📅 2022-05-26] \[[Website](https://sites.google.com/view/pvr-control)]
* **CANVAS**: "CANVAS: Commonsense-Aware Navigation System for Intuitive Human-Robot Interaction", *ICRA, Oct 2024*. \[[Paper](https://arxiv.org/abs/2410.01273)] \[[Code](https://github.com/worv-ai/canvas) ⭐ 18 | 🐛 1 | 📅 2025-10-20] \[[Website](https://worv-ai.github.io/canvas/)]
* **LAMP**: "LAMP: Implicit Language Map for Robot Navigation", *RA-L, 2025*. \[[Paper](https://arxiv.org/abs/2602.11862)] \[[Website](https://lab-of-ai-and-robotics.github.io/LAMP/)]
* **GSON**: "GSON: A Group-based Social Navigation Framework with Large Multimodal Model", *arxiv, Sept 2024* \[[Paper](https://arxiv.org/abs/2409.18084)]
* **Navid**: "NaVid: Video-based VLM Plans the Next Step for Vision-and-Language Navigation", *arxiv, Mar 2024* \[[Paper](https://arxiv.org/abs/2402.15852)] \[[Website](https://pku-epic.github.io/NaVid)]
* "Interactive Language: Talking to Robots in Real Time", *arXiv, Oct 2022* \[[Paper](https://arxiv.org/abs/2210.06407)] \[[Website](https://interactive-language.github.io/)]
* **NLMap**:"Open-vocabulary Queryable Scene Representations for Real World Planning", *arXiv, Sep 2022*, \[[Paper](https://arxiv.org/abs/2209.09874)] \[[Website](https://nlmap-saycan.github.io/)]
* **ADAPT**: "ADAPT: Vision-Language Navigation with Modality-Aligned Action Prompts", *CVPR, May 2022*. \[[Paper](https://arxiv.org/abs/2205.15509)]
* **CoW**: "CLIP on Wheels: Zero-Shot Object Navigation as Object Localization and Exploration", *arXiv, Mar 2022*. \[[Paper](https://arxiv.org/abs/2203.10421)]

***

## Simulation Frameworks

* **GENESIS**: "A generative world for general-purpose robotics & embodied AI learning.", *arXiv, Nov 2023*. \[[Code](https://github.com/Genesis-Embodied-AI/Genesis) ⭐ 29,833 | 🐛 130 | 🌐 Python | 📅 2026-08-29]
* **Habitat 2.0**: "Habitat 2.0: Training Home Assistants to Rearrange their Habitat", *NeurIPS, Dec 2021*. \[[Paper](https://arxiv.org/abs/2106.14405)] \[[Code](https://github.com/facebookresearch/habitat-sim) ⭐ 3,803 | 🐛 269 | 🌐 C++ | 📅 2026-07-21] \[[Website](https://aihabitat.org/)]
* **ManiSkill3**: "ManiSkill3: GPU Parallelized Robotics Simulation and Rendering for Generalizable Embodied AI.", *arxiv, Oct 2024*. \[[Paper](https://arxiv.org/abs/2410.00425)] \[[Code](https://github.com/haosulab/ManiSkill) ⭐ 3,273 | 🐛 134 | 🌐 Python | 📅 2026-08-04] \[[Website](http://maniskill.ai/)]
* **MineDojo**: "MineDojo: Building Open-Ended Embodied Agents with Internet-Scale Knowledge", *arXiv, Jun 2022*. \[[Paper](https://arxiv.org/abs/2206.08853)] \[[Code](https://github.com/MineDojo/MineDojo) ⭐ 2,252 | 🐛 82 | 🌐 Java | 📅 2024-03-18] \[[Website](https://minedojo.org/)] \[[Open Database](https://minedojo.org/knowledge_base.html)]
* **OmniGibson**: "OmniGibson: a platform for accelerating Embodied AI research built upon NVIDIA's Omniverse engine".*6th Annual Conference on Robot Learning, 2022*. \[[Paper](https://openreview.net/forum?id=_8DoIe8G3t)] \[[Code](https://github.com/StanfordVL/OmniGibson) ⭐ 1,670 | 🐛 308 | 🌐 Python | 📅 2026-08-28]
* **iGibson 1.0**: "iGibson 1.0: a Simulation Environment for Interactive Tasks in Large Realistic Scenes", *IROS, Sep 2021*. \[[Paper](https://arxiv.org/abs/2012.02924)] \[[Code](https://github.com/StanfordVL/iGibson) ⭐ 810 | 🐛 139 | 🌐 Python | 📅 2024-06-26] \[[Website](https://svl.stanford.edu/igibson/)]
* **BabyAI**: "BabyAI: A Platform to Study the Sample Efficiency of Grounded Language Learning", *ICLR, May 2019*. \[\[<https://arxiv.org/abs/1810.08272>)] \[[Code](https://github.com/mila-iqia/babyai/tree/iclr19) ⭐ 765 | 🐛 14 | 🌐 Python | 📅 2023-10-01]
* **ALFRED**: "ALFRED: A Benchmark for Interpreting Grounded Instructions for Everyday Tasks", *CVPR, Jun 2020*. \[[Paper](https://arxiv.org/abs/1912.01734)] \[[Code](https://github.com/askforalfred/alfred) ⭐ 529 | 🐛 23 | 🌐 C | 📅 2026-02-05] \[[Website](https://askforalfred.com/)]
* **UnrealZoo**: "UnrealZoo: Enriching Photo-realistic Virtual Worlds for Embodied AI", *ICCV Highlight, 2025*. \[[Paper](https://arxiv.org/abs/2412.20977)] \[[Code](https://github.com/UnrealZoo/unrealzoo-gym) ⭐ 355 | 🐛 13 | 🌐 Python | 📅 2026-08-28] \[[Website](https://unrealzoo.site/)]
* **ARNOLD**: "ARNOLD: A Benchmark for Language-Grounded Task Learning With Continuous States in Realistic 3D Scenes", *ICCV, Apr 2023*. \[[Paper](https://arxiv.org/abs/2304.04321)] \[[Code](https://github.com/arnold-benchmark/arnold) ⭐ 188 | 🐛 8 | 🌐 Jupyter Notebook | 📅 2025-03-16] \[[Website](https://arnold-benchmark.github.io/)]
* **BEHAVIOR**: "BEHAVIOR: Benchmark for Everyday Household Activities in Virtual, Interactive, and Ecological Environments", *CoRL, Nov 2021*. \[[Paper](https://arxiv.org/abs/2108.03332)] \[[Code](https://github.com/StanfordVL/behavior)] \[[Website](https://behavior.stanford.edu/)]

***

## Safety, Risks, Red Teaming, and Adversarial Testing

* **Exploring the Adversarial Vulnerabilities of Vision-Language-Action Models in Robotics** *arXiv, Nov 2024* \[[arXiv](https://arxiv.org/abs/2411.13587)] \[[Code](https://github.com/William-wAng618/roboticAttack) ⭐ 83 | 🐛 8 | 🌐 Python | 📅 2026-03-26] \[[Website](https://vlaattacker.github.io/)]
* **BadVLA**: "Towards Backdoor Attacks on Vision-Language-Action Models via Objective-Decoupled Optimization", *arXiv, May 2025*. \[[Paper](https://www.arxiv.org/abs/2505.16640)] \[[Code](https://github.com/Zxy-MLlab/BadVLA) ⭐ 57 | 🐛 5 | 🌐 Python | 📅 2025-12-09] \[[Website](https://badvla-project.github.io/)]
* **Safe LLM-Controlled Robots with Formal Guarantees via Reachability Analysis** *arXiv, Mar 2025* \[[arXiv](https://arxiv.org/abs/2503.03911)] \[[Code](https://github.com/TUM-CPS-HN/SafeLLMRA) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2025-05-26]
* **RoboPAIR**: "Jailbreaking LLM-Controlled Robots", *International Conference on Robotics and Automation (ICRA) May 2025*. \[[Paper](https://arxiv.org/abs/2410.13691)] \[[Website](https://robopair.org/)]
* **RoboGuard**: "Safety Guardrails for LLM-Enabled Robots", *arXiv, April 2025*. \[[Paper](https://arxiv.org/abs/2503.07885)] \[[Website](https://robo-guard.github.io/)]
* **LLM-Driven Robots Risk Enacting Discrimination, Violence, and Unlawful Actions**: *arXiv, Jun 2024*. \[[Paper](https://arxiv.org/abs/2406.08824)]
* **Highlighting the Safety Concerns of Deploying LLMs/VLMs in Robotics**: *arXiv, Feb 2024*. \[[Paper](https://arxiv.org/abs/2402.10340)]
* **Robots Enact Malignant Stereotypes**: *FAccT, Jun 2022*. \[[arXiv](https://arxiv.org/abs/2207.11569)] \[[DOI](https://doi.org/10.1145/3531146.3533138)] \[[Code](https://github.com/ahundt/RobotsEnactMalignantStereotypes)] \[[Website](https://sites.google.com/view/robots-enact-stereotypes/home)]

***

## Libraries and Tools

* **VeRL-Omni**: Easy, fast, and stable RL training for diffusion and omni-modality models. \[[Code](https://github.com/verl-project/verl-omni) ⭐ 907 | 🐛 121 | 🌐 Python | 📅 2026-08-30] \[[Docs](https://verl-omni.readthedocs.io/en/latest/index.html)]

***

## Citation

If you find this repository useful, please consider citing this list:

```
@misc{kira2022llmroboticspaperslist,
    title = {Awesome-LLM-Robotics},
    author = {Zsolt Kira},
    journal = {GitHub repository},
    url = {https://github.com/GT-RIPL/Awesome-LLM-Robotics},
    year = {2022},
}
```

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-30._
