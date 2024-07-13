# GUI-Agent-Survey

This is the official repository for the paper "Empowering GUI Agent with Large Language Model: A Comprehensive Survey".

## Abstract

The Graphical User Interface (GUI) is a visual method that allows users to interact with computers and mobile electronic devices. Nowadays users rely on GUI for completing some tasks such as browsing web or using mobile applications. Users often face the challenge to handle tedious tasks within GUI, such as replying to a specific type mass emails in Gmail application. GUI Agent are designed to help users by automating tasks in the GUI environment. Traditional automation agents lack flexibility, are often limited to specific applications, and require significant manual intervention. Benefiting from the powerful planning and reasoning capabilities of Large Language Model (LLM), LLM-based Agent achieved significant success in some fields (healthcare and autonomous driving). Researchers have also begun to explore the potential of LLM-based GUI Agent to automate task. Fortunately, these GUI agents have overcome the limitations of traditional agents and demonstrated remarkable performance.  Our survey reviews recent relevant LLM-based GUI Agent research and defines GUI task automation flow,  we focus on three key issues : (1) GUI Environment Understanding;  (2) User Interaction Experience;  (3) Efficient automation task Key step.  We finally outline the challenge and future opportunity in this field. This paper aims to provide valuable insights for researchers and engineers. A comprehensive list of studies in this survey is available at [https://github.com/longzhaohuang/GUI-Agent-Survey](https://github.com/longzhaohuang/GUI-Agent-Survey).

## News

😊 This project is under development. You can hit the **STAR** and **WATCH** to follow the updates.

## Table of Contents

- [GUI-Agent-Survey](#GUI-Agent-Survey)
  - [Abstract](#abstract)
  - [News](#news)
  - [Table of Contents](#table-of-contents)
  - [Related Paper](#related-paper)
  - [GUI Environment Understanding](#GUI-Environment-Understanding)
    - [Text-Based Understanding Method](#Text-Based-Understanding-Method)
    - [Vision-Based Understanding Method](#Vision-Based-Understanding-Method)
    - [Hybrid Text-Vision Understanding Method](#Hybrid-Text-Vision-Understanding-Method)
  - [Device Control](#Device-Control)
    - [Code-Based Method](#Code-Based-Method)
    - [Ui-Based Method](#Ui-Based-Method)
    - [Code-Based 、 Ui-Based Method](#Code-Based-、-Ui-Based-Method)
  - [Dataset](#Dataset)

## Related Paper
* Personal LLM Agents: Insights and Survey about the Capability, Efficiency and Security
 [[paper]](https://arxiv.org/abs/2401.05459)
* The Rise and Potential of Large Language Model Based Agents: A Survey [[paper]](https://arxiv.org/abs/2309.07864)
* Large Language Model based Multi-Agents: A Survey of Progress and Challenges [[paper]](https://arxiv.org/abs/2402.01680)

## GUI Environment Understanding
### Text-Based Understanding Method
* Explore, Select, Derive, and Recall: Augmenting LLM with Human-like Memory for Mobile Task Automation [[paper]](https://arxiv.org/pdf/2312.03003)
* DroidBot-GPT: GPT-powered UI Automation for Android [[paper]](https://arxiv.org/pdf/2304.07061) 
* Enabling Conversational Interaction with Mobile UI using Large Language Models [[paper]](https://arxiv.org/abs/2209.08655)
* Mind2Web: Towards a Generalist Agent for the Web [[paper]](https://arxiv.org/abs/2306.06070)
* A Real-World WebAgent with Planning, Long Context Understanding, and Program Synthesis [[paper]](https://arxiv.org/abs/2307.12856)
* WebGPT: Browser-assisted question-answering with human feedback [[paper]](https://arxiv.org/abs/2112.09332)
* Language Models can Solve Computer Tasks [[paper]](https://arxiv.org/abs/2303.17491)
* Adaplanner: Adaptive planning from feedback with language model[[paper]](https://arxiv.org/pdf/2305.16653)

### Vision-Based Understanding Method
* GPT-4V in Wonderland: Large Multimodal Models for Zero-Shot Smartphone GUI Navigation [[paper]](https://arxiv.org/abs/2311.07562)
* WebWISE: Web Interface Control and Sequential Exploration with Large Language Models
[[paper]](https://arxiv.org/pdf/2310.16042)
* Spotlight: Mobile UI Understanding using Vision-Language Models with a Focus [[paper]](https://arxiv.org/abs/2209.14927)
* META-GUI: Towards Multi-modal Conversational Agents on Mobile GUI [[paper]](https://arxiv.org/pdf/2205.11029)
* You Only Look at Screens: Multimodal Chain-of-Action Agents [[paper]](https://arxiv.org/abs/2309.11436)
* Mobile-Agent: Autonomous Multi-Modal Mobile Device Agent with Visual Perception[[paper]](https://arxiv.org/pdf/2401.16158)
* Mobile-Agent-v2: Mobile Device Operation Assistant with Effective Navigation via Multi-Agent Collaboration [[paper]](https://arxiv.org/pdf/2406.01014)
* SeeClick: Harnessing GUI Grounding for Advanced Visual GUI Agents [[paper]](https://arxiv.org/abs/2401.10935)
* CoCo-Agent: A Comprehensive Cognitive MLLM Agent for Smartphone GUI Automation[[paper]](https://arxiv.org/pdf/2402.11941)
* Cogagent: A visual language model for gui agents[[paper]](https://openaccess.thecvf.com/content/CVPR2024/papers/Hong_CogAgent_A_Visual_Language_Model_for_GUI_Agents_CVPR_2024_paper.pdf)
* UFO: A UI-Focused Agent for Windows OS Interaction [[paper]](https://arxiv.org/pdf/2402.07939)
* MMAC-Copilot: Multi-modal Agent Collaboration Operating System Copilot [[paper]](https://arxiv.org/abs/2404.18074)
* From Pixels to UI Actions: Learning to Follow Instructions via Graphical User Interfaces [[paper]](https://arxiv.org/abs/2306.00245)

### Hybrid Text-Vision Understanding Method
* AppAgent: Multimodal Agents as Smartphone Users [[paper]](https://arxiv.org/abs/2312.13771)
* Multimodal Web Navigation with Instruction-Finetuned Foundation Models [[paper]](https://arxiv.org/abs/2305.11854)
* GPT-4V(ision) is a Generalist Web Agent, if Grounded[[paper]](https://arxiv.org/abs/2401.01614)
* Dual-View Visual Contextualization for Web Navigation [[paper]](https://arxiv.org/abs/2402.04476)
* WebVoyager: Building an End-to-End Web Agent with Large Multimodal Models [[paper]](https://arxiv.org/abs/2401.13919)
* Do BERTs Learn to Use Browser User Interface? Exploring Multi-Step Tasks with Unified Vision-and-Language BERTs [[paper]](https://arxiv.org/pdf/2203.07828)
* AutoWebGLM: Bootstrap And Reinforce A Large Language Model-based Web Navigating Agent [[paper]](https://arxiv.org/pdf/2404.03648)

## Device Control
### Code-Based Method
* WebWISE: Web Interface Control and Sequential Exploration with Large Language Models [[paper]](https://arxiv.org/abs/2310.16042)
* A Real-World WebAgent with Planning, Long Context Understanding, and Program Synthesis [[paper]](https://arxiv.org/abs/2307.12856)
* Adaplanner: Adaptive planning from feedback with language model [[paper]](https://arxiv.org/pdf/2305.16653)

### Ui-Based Method
* Spotlight: Mobile UI Understanding using Vision-Language Models with a Focus [[paper]](https://arxiv.org/abs/2209.14927)
* META-GUI: Towards Multi-modal Conversational Agents on Mobile GUI [[paper]](https://arxiv.org/pdf/2205.11029)
* You Only Look at Screens: Multimodal Chain-of-Action Agents [[paper]](https://arxiv.org/abs/2309.11436)
* Explore, Select, Derive, and Recall: Augmenting LLM with Human-like Memory for Mobile Task Automation [[paper]](https://arxiv.org/pdf/2312.03003)
* AppAgent: Multimodal Agents as Smartphone Users [[paper]](https://arxiv.org/abs/2312.13771)
* DroidBot-GPT: GPT-powered UI Automation for Android [[paper]](https://arxiv.org/pdf/2304.07061) 
* Mobile-Agent: Autonomous Multi-Modal Mobile Device Agent with Visual Perception[[paper]](https://arxiv.org/pdf/2401.16158)
* Mobile-Agent-v2: Mobile Device Operation Assistant with Effective Navigation via Multi-Agent Collaboration [[paper]](https://arxiv.org/pdf/2406.01014)
* SeeClick: Harnessing GUI Grounding for Advanced Visual GUI Agents [[paper]](https://arxiv.org/abs/2401.10935)
* CoCo-Agent: A Comprehensive Cognitive MLLM Agent for Smartphone GUI Automation[[paper]](https://arxiv.org/pdf/2402.11941)
* WebGPT: Browser-assisted question-answering with human feedback [[paper]](https://arxiv.org/abs/2112.09332)
* From Pixels to UI Actions: Learning to Follow Instructions via Graphical User Interfaces [[paper]](https://arxiv.org/abs/2306.00245)
* Multimodal Web Navigation with Instruction-Finetuned Foundation Models [[paper]](https://arxiv.org/abs/2305.11854)
* Mind2Web: Towards a Generalist Agent for the Web [[paper]](https://arxiv.org/abs/2306.06070)
* GPT-4V(ision) is a Generalist Web Agent, if Grounded [[paper]](https://arxiv.org/abs/2401.01614)
* WebVoyager: Building an End-to-End Web Agent with Large Multimodal Models [[paper]](https://arxiv.org/abs/2401.13919)
* Dual-View Visual Contextualization for Web Navigation [[paper]](https://arxiv.org/abs/2402.04476)
* UFO: A UI-Focused Agent for Windows OS Interaction [[paper]](https://arxiv.org/pdf/2402.07939)
* AutoWebGLM: Bootstrap And Reinforce A Large Language Model-based Web Navigating Agent [[paper]](https://arxiv.org/pdf/2404.03648)

### Code-Based 、 Ui-Based Method
* MMAC-Copilot: Multi-modal Agent Collaboration Operating System Copilot [[paper]](https://arxiv.org/abs/2404.18074)

## Dataset
* Mapping Natural Language Instructions to Mobile UI Action Sequences [[paper]](https://arxiv.org/abs/2005.03776)
* World of Bits: An Open-Domain Platform for Web-Based Agents [[paper]](https://proceedings.mlr.press/v70/shi17a)
* META-GUI: Towards Multi-modal Conversational Agents on Mobile GUI [[paper]](https://arxiv.org/abs/2205.11029)
* Explore, Select, Derive, and Recall: Augmenting LLM with Human-like Memory for Mobile Task Automation [[paper]](https://arxiv.org/abs/2312.03003)
* SeeClick: Harnessing GUI Grounding for Advanced Visual GUI Agents [[paper]](https://arxiv.org/abs/2401.10935)
* Mind2Web: Towards a Generalist Agent for the Web [[paper]](https://arxiv.org/abs/2306.06070)
* WebVoyager: Building an End-to-End Web Agent with Large Multimodal Models [[paper]](https://arxiv.org/abs/2401.13919)
* WebLINX: Real-World Website Navigation with Multi-Turn Dialogue [[paper]](https://arxiv.org/abs/2402.05930)
* Grounding Open-Domain Instructions to Automate Web Support Tasks [[paper]](https://arxiv.org/abs/2103.16057)
* A Dataset for Interactive Vision-Language Navigation with Unknown Command Feasibility [[paper]](https://arxiv.org/abs/2202.02312)
* UGIF: UI Grounded Instruction Following [[paper]](https://arxiv.org/abs/2211.07615)
* MobileAgentBench: An Efficient and User-Friendly Benchmark for Mobile LLM Agents [[paper]](https://arxiv.org/abs/2406.08184)
* AutoDroid: LLM-powered Task Automation in Android [[paper]](https://arxiv.org/abs/2308.15272)
* Mobile-Env: Building Qualified Evaluation Benchmarks for LLM-GUI Interaction [[paper]](https://arxiv.org/abs/2305.08144)
* WebArena: A Realistic Web Environment for Building Autonomous Agents [[paper]](https://arxiv.org/abs/2307.13854)
* VisualWebArena: Evaluating Multimodal Agents on Realistic Visual Web Tasks [[paper]](https://arxiv.org/abs/2401.13649)
* WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents [[paper]](https://arxiv.org/abs/2207.01206)
* Mapping Natural Language Commands to Web Elements [[paper]](https://arxiv.org/abs/1808.09132)
* UIBert: Learning Generic Multimodal Representations for UI Understanding [[paper]](https://arxiv.org/abs/2107.13731)
* ASSISTGUI: Task-Oriented Desktop Graphical User Interface Automation [[paper]](https://arxiv.org/abs/2312.13108)
* Android in the Wild: A Large-Scale Dataset for Android Device Control [[paper]](https://arxiv.org/abs/2307.10088)
